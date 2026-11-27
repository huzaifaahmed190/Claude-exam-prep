# FDE Track: A Pod of One, and the Bus-Factor Test

Source: `roles-this-book-trains`, section `the-forward-deployed-engineer-fde-the-vendor-neutral/a-pod-of-one`. Everything below comes from that page. The page cites Bai's single-point-of-failure remark to its own footnote 24, which I have not checked independently. Process notes: I could not call `begin_session` (the connector exposes no such tool), and the connector has no tool for reading the learner's current course. I therefore chose this topic by comparing the connector's outline of the FDE page against the existing files in `lessons/`: no existing lesson covers this section. Read-only run: no learner record was changed.

## 1. What it is

The page starts from what AWS sends a client: a pod of five or six engineers, on-site for about forty-five days. That is what forward deployment looks like "when people still do the building by hand."

The book changes who is in the pod:

- A graduate carries the same work into the client **alone**.
- The people who used to sit beside them are now **Digital FTEs**, the Workers the engineer builds and runs.
- So the team of five or six shrinks to "one human commanding a workforce of Workers."

The page's summary line is: "The job is the same. What fills the pod is not." The pod now has two halves:

1. The **Workers replace the people.**
2. The **two Systems of Record replace the vendor's platform** (the previous lesson).

The page links this to the product-to-engineer ratio: each person's output keeps rising while the number of people falls. It points to "How the team got this small" for the full arc, legacy pod → compressed pod → pod of one. I did not read that page, so this lesson doesn't cover it.

## 2. Why it works that way

- **Power comes from a different place.** The page says it "no longer comes from adding people. It comes from the method, and the Workers it produces."
- **The risk is real, and the page says so.** Asked whether several FDEs should work one project, Bai says it is a good pattern. His reason is that you don't want a single point of failure: one person holding all the information, going on vacation, and the engagement stalling behind them. The page says a pod of one "is that risk in its purest form, and pretending otherwise would be dishonest."
- **The book's answer is that the risk moves, not that it disappears.** What a second engineer gives you is *redundancy of knowledge*. In this method the knowledge is already written down as artifacts: the spec, the evals, the governed corpus, the deployed Worker and its runbook. The claim is "redundancy through artifacts rather than headcount."
- **The claim comes with a test.** If you were unreachable for two weeks, could another graduate of this book pick up your engagement from your repository alone?

## 3. What breaks without it

- If the knowledge lives only in the engineer's head, the engagement has a single point of failure. One vacation stalls the client, which is exactly Bai's concern.
- If the artifacts are missing or incomplete, you fail the two-weeks test. The page's verdict: "you do not have a pod of one. You have a bus factor of one."
- If you only shrink the team and don't change what fills the pod, you have fewer people doing the same hand-built work. The page's point is that Workers and the Systems of Record take the place of the people and the platform.
- Limit to keep in mind: the page presents "redundancy through artifacts" as a claim plus a self-test. It gives no measurement showing the claim holds in practice.

## 4. Worked example (applying the page's test)

An engineer runs a solo engagement and applies the two-weeks test.

1. She imagines being unreachable for two weeks. Another graduate of the book gets only her repository.
2. She checks it for the artifacts the page names: the **spec**, the **evals**, the **governed corpus**, and the **deployed Worker with its runbook**.
3. Suppose the runbook is missing, and the reason a threshold was chosen exists only in her memory. The stand-in graduate can't continue without calling her.
4. By the page's standard, that engagement has a bus factor of one. The fix is to write the missing knowledge into the artifacts, not to add a second person.
5. Once the stand-in could pick the engagement up from the repository alone, the page would say she has a pod of one.

(This scenario applies the page's own test. The page does not describe this particular case.)

## 5. Quiz

**Q1. According to the page, what does a typical AWS engagement send a client?**
- A. A single engineer for a year.
- B. A pod of five or six engineers, on-site for about forty-five days.
- C. A team of Digital FTEs.
- D. Only remote support staff.

**Q2. In the pod of one, what replaces what?**
- A. Workers replace the people, and the two Systems of Record replace the vendor's platform.
- B. The people replace the Workers, and the vendor's platform stays.
- C. The client's staff replace the Workers.
- D. Headcount replaces the Systems of Record.

**Q3. Why does the page say a pod of one is the "purest" form of Bai's risk?**
- A. Because Workers are unreliable.
- B. Because one person holds all the information, and if they go on vacation the engagement can stall behind them.
- C. Because the client refuses solo engineers.
- D. Because the Systems of Record are closed.

**Q4. What is the page's answer to that risk, and its test?**
- A. Hire a second engineer. The test is whether the client approves.
- B. The risk disappears entirely, so no test is needed.
- C. The risk moves from the human's head into written artifacts (spec, evals, governed corpus, Worker and runbook). The test is whether another graduate could pick up the engagement from the repository alone after you were unreachable for two weeks.
- D. Keep knowledge in the engineer's head, since it is the fastest route. The test is delivery speed.

## Answers

1. **B.** The page gives "a pod of five or six engineers, on-site for about forty-five days."
2. **A.** "The Workers replace the people, and the two Systems of Record replace the vendor's platform."
3. **B.** That is the single point of failure Bai describes: one person holding all the information.
4. **C.** The page says the risk "moves out of the human's head" into artifacts. If another graduate can't take over from your repository in two weeks, you have a bus factor of one.
