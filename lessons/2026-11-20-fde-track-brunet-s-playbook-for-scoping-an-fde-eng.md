# FDE Track: Brunet's Playbook for Scoping an FDE Engagement

Source: `roles-this-book-trains`, section `the-forward-deployed-engineer-fde-the-vendor-neutral/the-services-industry-sees-the-same-math-from-the-other-side` (the paragraph "The playbook, from inside a vendor"), plus the "Two matrices, two different questions" note in the Bai section. Everything below comes from that page. The page labels this as one vendor's playbook, "her framework, not a measurement."

## 1. What it is

Pauline Brunet runs the global FDE team at Cursor after ten years of enterprise AI deployment. She presented her playbook at the AI Engineer World's Fair in June 2026. The page keeps four of her rules:

1. **The fit test.** Score every engagement on two axes: how digitally mature the customer is, and how customizable the product is.
2. **The staff-augmentation line.** Decline "we're understaffed" requests, and ask: "who will be the working team?"
3. **Directional scope.** Name the problem, name the KPI baseline, commit to a phased six-week directional plan, and expect to pivot.
4. **ROI in three questions.** Every engagement must end on at least one: did we increase revenue, decrease costs, or mitigate risk?

**How it differs from Bai's square.** The page says the two matrices answer different questions. Bai's square is a vendor's build-or-not decision: should this company have an FDE function at all. Brunet's matrix is per engagement: is this client an FDE client. Bai's tells a vendor-neutral reader which clients to walk toward. Brunet's tells them how to scope the engagement once in the room.

## 2. Why it works that way

- **The fit band.** A mature customer with a simple product needs documentation, not an FDE. An immature customer with a simple product needs a traditional rollout, not an FDE. The FDE lives in the band between: *embedded transformation* where the customer cannot staff the work, and *acceleration* where the customer is capable but the build is deep. The page notes this is how the buyer already thinks.
- **The one-question test.** A client who says "we're understaffed" is asking to rent hours, not transfer capability. If the client cannot name the people who will build alongside you, the engagement is body-shopping in disguise. The page calls this the field test for the difference between the FDE and the services pyramid.
- **Why the plan is only directional.** Brunet refuses both open-ended engagements ("take two FDEs for six months") and fixed waterfall promises. Her stated reason: she has not yet seen the customer's data, processes or systems, so "precision before contact is a lie." The page ties this to spec-driven development: the spec hardens as ground truth arrives.
- **Why the ROI questions.** The page's example: a client was alarmed that an agent cost $2,000 a day, until Brunet asked what it was doing. It dispatched the right technician to failing equipment, and the client conceded it was cheap. The client had measured cost and never measured return.

## 3. What breaks without it

- **Skip the fit test:** you put an FDE where documentation or a traditional rollout would do, or you send documentation where the customer cannot staff the work.
- **Accept "we're understaffed":** you sell hours and no capability transfers. That is body-shopping.
- **Promise a fixed plan before contact:** the promise is false, because you have not seen the real systems. **Take an open-ended engagement:** there is no baseline and nothing to judge success against.
- **Measure cost and not return:** a useful agent looks too expensive, as in the $2,000-a-day case.

One caveat the page makes explicit: "no precision before contact" is not "arrive with nothing." What cannot be precise is the plan for this client. What must exist beforehand is the profession's own governed knowledge, which does not vary by client.

## 4. Worked example

The page's own example is the baseline format: "this process takes three hours; success is twenty minutes." Here it is applied to a hypothetical client (invented for illustration, not from the page).

A regional insurer asks for "two FDEs for six months because we're understaffed."

1. **Fit:** the insurer has a deep customization need and little capacity to build it, so it falls in the FDE band (embedded transformation).
2. **Staffing question:** ask "who will be the working team?" If they name no one, decline, because this is body-shopping.
3. **Scope:** name the problem (claims triage), set the baseline (a triage takes three hours, success is twenty minutes), and commit to a phased six-week directional plan. Pivot as the real systems teach you.
4. **Close:** report against revenue, cost or risk, for example cost per claim triaged.

## Quiz

**Q1.** Which two axes does Brunet use to score an engagement?
- A. Contract value and team size
- B. Customer digital maturity and product customizability
- C. Buyer technicality and product technicality
- D. Engagement length and number of FDEs

**Q2.** Per the page, which question is Brunet's test for staff augmentation in disguise?
- A. How much is the budget?
- B. Which cloud do you run on?
- C. Who will be the working team?
- D. When does the contract end?

**Q3.** Why does Brunet refuse to promise a fixed plan up front?
- A. Fixed plans are not legal
- B. She has not yet seen the customer's data, processes or systems, so precision before contact is a lie
- C. Clients prefer open-ended deals
- D. FDEs bill hourly

**Q4.** How does the page distinguish Bai's square from Brunet's matrix?
- A. Bai's is a vendor's build-or-not decision on an FDE function. Brunet's scopes a single engagement.
- B. They are the same matrix with different names
- C. Bai's covers pricing and Brunet's covers hiring
- D. Bai's is per engagement and Brunet's is per company

## Answers

1. **B.** Digital maturity of the customer against how customizable the product is.
2. **C.** If the client cannot name the people who will build alongside you, it is body-shopping in disguise.
3. **B.** Her stated reason is that she has not seen the client's real systems yet. Her format is a phased six-week directional plan with a KPI baseline.
4. **A.** The page says "Two matrices, two different questions": Bai's is a vendor's build-or-not decision, and Brunet's is per engagement.
