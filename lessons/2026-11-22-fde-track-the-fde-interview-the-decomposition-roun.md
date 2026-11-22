# FDE Track: The FDE Interview, the Decomposition Round and the Client Simulation

Source: `roles-this-book-trains`, section `appendix-b-the-fde-interview-the-loop-and-the-trap`. Everything below comes from that page. The page cites its interview-loop details to its own footnotes (20, 21), and I have not checked them independently.

## 1. What it is

The FDE interview loop runs five to eight stages over three to six weeks. The page lists these stages: recruiter screen, hiring-manager screen, a practical coding round, a system-design round, the decomposition case study, a client simulation and a behavioral round. Some AI labs add a take-home built on their APIs.

The page says two rounds decide the outcome, and "neither is the one engineers prepare for":

- **The decomposition round (the filter).** You get a vague, real enterprise problem and about sixty minutes. The page's example: "a major city wants to cut emergency response times; they have call data, traffic data, and ambulance GPS."
- **The client simulation (the second filter).** An interviewer role-plays a customer, sometimes frustrated and sometimes non-technical. You deliver bad news, push back on a request that would compromise governance, or explain why the system cannot promise 100% accuracy.

A newer format, the **live build**, is also spreading. The page describes one documented three-hour loop:

1. 30 minutes turning a vague use case into requirements under cross-examination.
2. 90 minutes building the working solution with an AI coding assistant, validating every suggestion and debugging live.
3. 60 minutes presenting the result to a role-played stakeholder in pure business language.

No LeetCode appeared at any stage.

## 2. Why it works that way

- **The decomposition round tests scoping, not answers.** The page says the round "is not testing whether you know the answer. It is testing whether you write the spec before you let anyone, human or agent, execute." It calls the winning sequence "spec-driven development performed verbally."
- **The scoring sequence.** What scores is the order of steps:
  1. Clarify the actual goal.
  2. Name the stakeholders and the success metric.
  3. Map what data exists and who owns it.
  4. Decompose into subproblems sequenced by risk.
  5. Propose the thinnest end-to-end skeleton first.

  Throughout, state assumptions out loud, surface failure modes unprompted and narrate your thinking continuously.
- **The client simulation tests the customer-facing half of the role.** You have to communicate without jargon and without promising what you cannot keep.
- **The live build tests Mode 1 discipline under observation.** The page describes this as: direct the agent, verify everything it produces and narrate the loop.
- **Company flavor matters only at the margin.** Palantir leans on data engineering, ontology thinking and the decomposition round it invented. OpenAI leans on building and evaluating systems against its APIs, with "how do you know it's actually working?" as the differentiator question. Anthropic, which titles the role Applied AI Engineer, leans on production LLM systems, evals and mission alignment.

## 3. What breaks without it

- **Solve before you scope.** The page calls answering the problem "the single most common rejection." A candidate who opens with "I'd build a predictive model using XGBoost" has failed, "because they solved before they scoped."
- **The five red flags.** Interviewers name these consistently:
  1. Solving before clarifying.
  2. Ignoring cost and constraints.
  3. A thin deployment story, with no account of what happened when an API failed in production.
  4. Zero compliance vocabulary in regulated domains.
  5. No customer instinct.
- **Preparing only for the coding round.** The page says the deciding rounds are not the ones engineers prepare for. Its advice is a four-to-six-week discipline: fundamentals and stories first, then system design, then timed decomposition practice with a partner (recorded), and company-specific tuning last. It says most candidates are shocked at how quickly they jump to solutions.

## 4. Worked example

The page's own prompt is the city emergency-response problem. The steps below apply the page's scoring sequence to it. The specific questions and phrasing are my illustration, not text from the page.

1. **Clarify the goal.** Ask what "cut response times" means. Is it the median, the worst-case tail, or particular neighborhoods?
2. **Stakeholders and metric.** Name who is involved (the city, dispatchers, ambulance crews) and agree on one success metric before touching a model.
3. **Map the data.** The prompt lists call data, traffic data and ambulance GPS. Ask who owns each and what state each is in.
4. **Decompose by risk.** Break the problem into subproblems and take the riskiest first, for example whether the data sources can be joined at all.
5. **Thinnest skeleton.** Propose a minimal end-to-end path first, with assumptions and failure modes stated out loud.

Notice what is missing: any mention of XGBoost. The model choice comes after the scoping, not before.

## Quiz

**Q1.** According to the page, what is the single most common reason candidates are rejected in the decomposition round?
- A. They run out of time on the coding exercise
- B. They answer the problem before scoping it
- C. They ask too many clarifying questions
- D. They propose a skeleton that is too thin

**Q2.** The page describes the winning decomposition sequence as the equivalent of which practice?
- A. Test-driven development performed on a whiteboard
- B. Spec-driven development performed verbally
- C. Pair programming with the interviewer
- D. Agile sprint planning

**Q3.** Which of the following is NOT one of the five red flags the page names?
- A. Ignoring cost and constraints
- B. Zero compliance vocabulary in regulated domains
- C. No customer instinct
- D. Failing to memorize the vendor's pricing tiers

**Q4.** In the live-build loop the page describes, what happens in the final sixty minutes?
- A. Debugging the solution live with an AI coding assistant
- B. Turning a vague use case into requirements
- C. Presenting the result to a role-played stakeholder in pure business language
- D. A LeetCode-style algorithm round

## Answers

1. **B.** The page says the candidate who opens with "I'd build a predictive model using XGBoost" has "solved before they scoped."
2. **B.** The page says the sequence is "spec-driven development performed verbally."
3. **D.** The five named flags are solving before clarifying, ignoring cost and constraints, thin deployment stories, zero compliance vocabulary in regulated domains and no customer instinct.
4. **C.** The loop is 30 minutes of requirements, 90 minutes of building and 60 minutes of presenting to a role-played stakeholder. The page says no LeetCode appeared at any stage.
