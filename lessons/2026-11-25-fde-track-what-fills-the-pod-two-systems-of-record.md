# FDE Track: What Fills the Pod — Two Systems of Record

Source: `roles-this-book-trains`, section `the-forward-deployed-engineer-fde-the-vendor-neutral/what-fills-the-pod-two-systems-of-record`. Everything below comes from that page. The page itself labels its second half as "this book's reasoning, in the same class as Aggarwal's arithmetic," not a measurement. It cites Bai's rule on what a vendor keeps to its footnote 24, which I have not checked independently. I could not call `begin_session` (the connector has no such tool), and it exposes no tool for reading the learner's current course. So I did not check the learner's progress through the connector. I chose this topic because no existing lesson in `lessons/` covers this section. Read-only run: no learner record was changed.

## 1. What it is

Earlier sections say *where* an FDE works. This one answers what the engineer *brings through the door* once the vendor is removed.

- A vendor's FDE (the page's example is Palantir) arrives with the vendor's ontology and tooling, built by someone else. That is real leverage. The page also calls it a cage: the client stays free to keep building, as long as they keep building there.
- A vendor-neutral FDE has no platform. If all she has is "the method, in her head," she is selling hours of human execution. The page calls that the services pyramid she was supposed to replace.
- The page says a "pod of one" survives only on **assets that travel from one client to the next**. It names two, and both are Systems of Record:
  1. **The method, which she did not build.** This is the book itself, "deep and already governed," served as a website for humans and over MCP for agents. It covers how to specify an outcome, manufacture a Worker, run the loop, trust the checker, and prove the result in production. It is identical at every client and in every domain.
  2. **The profession, which she built herself.** This is one vertical in one jurisdiction, governed by her and licensed from a committed domain expert. It holds the law, the standards, the expert's derived procedures, the invariants, and the decision map. It starts at one professional outcome covered completely and thickens engagement by engagement. "Nobody else has this one."

Both speak MCP, so her agent reads both at once. One source says how to build a Worker and the other says what the profession requires. The page says no integration work is needed.

## 2. Why it works that way

- **It answers the dev-shop objection.** Bai's condition (see the previous lesson, "Without a platform, you are a dev shop") is shared primitives, so the engineer never starts from scratch. The method is the primitive layer for *how work gets built*. The profession is the primitive layer for *what the work must obey*. Neither is code forked per customer. What gets maintained is "a governed corpus, and the code around it is regenerated rather than nursed."
- **Specialization has to land somewhere.** A vendor's FDE specializes by platform. Without a platform, the axis becomes the **profession**. The page asks what actually travels from client two to client three:
  - The *shape of the work* travels free. Reading a document against a rule, citing the rule, and escalating what is unclear is method, and it is already in the first System of Record. Nobody pays a premium for it.
  - What a buyer pays for is the part that does *not* generalize: which standard governs this question, which version was effective in this period, which country's regulator owns the rule, what the partner must sign personally. That is professional and jurisdictional, and it lives only in the second System of Record.
- **How the second one thickens.** Bai's rule is that anything bespoke to one customer stays with that customer and anything generalizable gets generalized over time (forward deployment as a scouting function). The vendor version sends what generalizes into the vendor's platform. The vendor-neutral version sends it into the **vertical System of Record**. Examples are the standard that governed three clients, the procedure the expert signs off everywhere, and the invariant that held at every firm in the jurisdiction. That is why the second client costs less to serve than the first.
- **Build first, sell second.** The page says the slice "is the step that produces" a customer. Its reasons are that the portfolio is the credential, the résumé is screened on shipped systems, and a buyer who has been shown nothing will not share his own baseline number.

## 3. What breaks without it

- Without either System of Record, the vendor-neutral FDE is "a generalist consultant with nothing to reuse," selling hours. That is the services model, and a client who says "we're understaffed" is asking for exactly that.
- Without the *method* SoR, there is no shared primitive layer for how work gets built, and the dev-shop objection stands.
- Without the *profession* SoR, there is nothing a buyer will pay a premium for. Method alone is free, because it travels at no cost.
- If she skips build-first, she walks in with nothing to show, and the buyer won't disclose his baseline.
- Honest limits the page states:
  - The cost did not vanish, it **moved**. You maintain a corpus instead of repositories, and someone must fund that before the first client pays.
  - The claim that a governed corpus flattens the maintenance curve "is a claim, not yet a measurement."
  - No verified count yet exists of vendor-neutral graduates who converted a governed corpus into a first client.
  - The client does **not** end up owning the vertical System of Record. It is held by the domain startup she and her expert built and contains the expert's material and third-party sources under licence. What the client keeps is "a working system you can change, on a stack you chose, with the option to hire me outright."

## 4. Worked example (built from the page's own illustrations)

A vendor-neutral FDE has built one governed page for an accounting firm's profession: one standard, one jurisdiction, one professional outcome covered completely.

1. She walks into a mid-size accounting firm in Karachi carrying that governed page of *the firm's own profession*. The page says the next question then comes from the buyer's side.
2. Her agent reads the method System of Record, which says how to specify the outcome, manufacture the Worker, run the loop, trust the checker, and prove it in production. It also reads her profession System of Record, which says which standard governs, which version was effective in the period, and what the partner must sign.
3. The page says the method is "identical at a Karachi accounting firm and a Chicago one." The profession content is what is specific to her vertical and jurisdiction.
4. Another firm in the same jurisdiction hits a procedure the expert already wrote. It gets reused and now signs off everywhere, so the second client costs less to serve.
5. When the client asks what they keep when she leaves, her answer is a working system on a stack they chose, plus the option to hire her. It does not include a licence to the vertical System of Record.

## 5. Quiz

**Q1. According to the page, why can't a vendor-neutral FDE rely on "the method, in her head"?**
- A. The method is secret to the vendor.
- B. It makes her a seller of hours of human execution, the services pyramid she was meant to replace.
- C. Clients cannot understand the method.
- D. The method changes completely between domains.

**Q2. Which pair of assets does the page name as the two Systems of Record?**
- A. The vendor's platform and the client's data.
- B. The method (which she did not build) and the profession (which she built herself).
- C. A code library and a prompt template set.
- D. The résumé and the portfolio.

**Q3. What does the page say a buyer actually pays a premium for?**
- A. Reading a document against a rule and citing it.
- B. Escalating unclear items.
- C. The part that does not generalize across professions: which standard governs, which version applied, whose regulator, what the partner signs.
- D. The method, because it is identical at every client.

**Q4. Which statement matches the page's honest caveats?**
- A. The client ends up owning the vertical System of Record.
- B. The maintenance cost disappeared once a corpus replaced repositories.
- C. The cost moved: you maintain a corpus instead of repositories, and someone must fund it before the first client pays.
- D. Many verified graduates have already converted a governed corpus into a first client.

## Answers

1. **B.** Without portable assets she sells hours, which is the services pyramid.
2. **B.** The method is given to her and the profession is built by her, and both speak MCP.
3. **C.** The shape of the work is method and travels free. The premium is for the professional and jurisdictional specifics, which are not in the method System of Record.
4. **C.** The page says the cost moved rather than vanished. The client does not own the vertical System of Record, and no verified count of such graduates exists yet.
