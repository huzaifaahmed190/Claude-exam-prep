# FDE Track: The Third Door — The Freelance FDE

Source: `roles-this-book-trains`, section `the-forward-deployed-engineer-fde-the-vendor-neutral/the-third-door-the-freelance-fde`. Everything below comes from that page. The rates are the page's own figures, which it cites to its footnotes 17–19. I have not checked them independently. Process notes: I could not call `begin_session` (the connector exposes no such tool), and the connector has no tool for reading the learner's current course. I chose this topic by comparing the page's section list with the `Source:` lines of the existing files in `lessons/`: no existing lesson covers this section. Read-only run: no learner record was changed.

## 1. What it is

The page says the FDE has had two addresses so far: the vendor's payroll and the independent firm's. A **third door** is the open freelance market.

- **Published project bands (Upwork FDE category):** about $2,000–5,000 for a first integration, $5,000–15,000 for a custom implementation, $15,000 and up for enterprise deployments, $4,000–10,000 a month for ongoing support, and $150–250 an hour for strategic consulting.
- **UK contract day rates:** £600–750 mid-level, £750–1,200 senior, £1,200–2,000 principal. The page adds that a specialist FDE recruiter reports senior FDEs choosing contract work over permanent roles.
- **Fractional platforms** now match FDEs, and "Fractional Forward-Deployed Engineering Lead" postings fill within days.

The page's honest reading: **the category exists, but the supply under it does not.** Profiles listed as FDEs are mostly capable generalists (full-stack, DevOps, app builders) who do not describe embedded delivery or an end-to-end pipeline. The marketplace "built the shelf before anyone stocked it." For a trained reader, that empty shelf is the opening.

The page then makes a second, related point about **direct hire**. "FDE" describes *where* someone works (embedded inside a client's company, as an outsider, carrying the whole line end to end), not their skills. Hire the engineer directly and the client's company becomes their own, so they are "no longer forward deployed: just deployed." The title falls away and they become the internal core again, which the page names the **AI-Native Company Architect** (usually running the Cloud AI Engineer role too).

## 2. Why it works that way

The page gives three reasons this door differs from the other two:

1. **It is the vendor-neutral FDE's native market.** A vendor's FDE cannot freelance, because the role exists only inside the vendor's payroll, welded to the vendor's platform. So every genuine freelance FDE is vendor-neutral by construction. On the open market, vendor-neutrality is the entry requirement, not a differentiator.
2. **The retainer tier is not disguised maintenance.** It is the Digital FTE subscription model the book teaches, run from outside. The monthly fee pays you to operate the Workers you manufactured, which is "the pod of one converted into recurring revenue."
3. **It has no border.** The salaried FDE market largely requires a US or European work address. The freelance and fractional market "requires a portfolio and a connection." The page says the same contract clears from Karachi, Lagos, or Bangalore.

Direct hire works for the same underlying reason: "the discipline lives in the person, not in any vendor's platform," so it walks in the door with them.

## 3. What breaks without it

- **Vendor-welded FDEs lose their leverage.** The day they leave Palantir or OpenAI, the platform the job was built on stays behind. The page calls them "on permanent loan": useful while embedded, gone when the vendor relationship ends. A client can rent a vendor-neutral FDE and later hire them in-house "and never lose a step."
- **Remote embedding done badly.** The page names two constraints. Embedding is the essence of the job, and remote embedding is harder than remote coding. The freelance FDE wins by over-communicating, holding client-timezone hours, and treating occasional on-site presence as part of the price of the premium.
- **An unproven profile stays at generalist rates.** The premium is "earned, not listed." What moves an engineer up the bands is demonstrated outcomes: a deployed Worker, a shipped plugin, a live connector app, one governed slice of a profession. On this market, those are the credential.
- **Assuming everything transfers on direct hire.** One asymmetry survives. The first System of Record (the Agent Factory System of Record) is open and goes wherever she goes. The second (her domain startup's) rests on her expert's licence and third-party terms, so a direct hire is "a conversation about that business rather than an automatic transfer." In the page's words: "The discipline is always portable. The asset has an owner."

## 4. Worked example

Following the page's logic, with a hypothetical engineer (the engineer and the numbers are mine, illustrating the page's bands):

1. Amina, a graduate in Lagos, has a deployed Worker and a live connector app from her capstones. She lists them as her portfolio on a freelance marketplace.
2. A client posts a custom implementation. The page's band is $5,000–15,000. Amina embeds remotely: she keeps the client's timezone hours and communicates heavily.
3. The Worker runs well. The client moves her to ongoing support, the $4,000–10,000-a-month band. This is the Digital FTE subscription model: she is paid to operate the Worker she built.
4. Later, the client offers her a full-time job. She is no longer forward deployed, just deployed, and the same work continues as the AI-Native Company Architect. If the offer also covers her domain startup's governed profession data, that part is a negotiation about the business, not an automatic transfer.

## 5. Quiz

**Q1. According to the page, why can a vendor's FDE (for example at Palantir) not freelance?**
A. Freelance platforms ban them.
B. Their role exists only inside the vendor's payroll, welded to the vendor's platform.
C. They are paid too little to freelance.
D. They lack a portfolio.

**Q2. What does the page say about the supply side of the Upwork FDE category?**
A. It is oversupplied with trained FDEs.
B. It is full of FDEs who describe embedded, end-to-end delivery.
C. The category exists but the supply does not: listed profiles are mostly capable generalists.
D. It is limited to the US and Europe.

**Q3. What is the page's explanation of the monthly retainer tier?**
A. Maintenance work in disguise.
B. The Digital FTE subscription model, run from the outside: being paid to operate the Workers you manufactured.
C. A signing bonus for new clients.
D. A fee for strategic consulting only.

**Q4. A client directly hires a vendor-neutral FDE. Which statement matches the page?**
A. The FDE title stays, and the engineer must relearn the work.
B. Everything, including her domain startup's asset, transfers automatically.
C. The engineer becomes the internal core again (the AI-Native Company Architect). The discipline travels, but the second System of Record has an owner and is negotiated.
D. The engineer loses access to the Agent Factory System of Record.

### Answers

1. **B.** The role is welded to the vendor's platform, so "a vendor's FDE cannot freelance at all."
2. **C.** "The category exists. The supply under it does not."
3. **B.** The page says it "is not maintenance work in disguise" but the Digital FTE subscription model run from the outside.
4. **C.** "The discipline is always portable. The asset has an owner."
