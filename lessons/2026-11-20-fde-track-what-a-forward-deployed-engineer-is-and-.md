# FDE Track: What a Forward Deployed Engineer Is, and the Test for When You Need One

Source: `roles-this-book-trains`, section `the-forward-deployed-engineer-fde-the-vendor-neutral` (including "FDE 101: why Palantir needed the role"). Everything below comes from that page. The figures are the page's own and are not independently checked. The page labels Kevin Bai's framework as a practitioner's view, "not audited research."

## 1. What it is

A Forward Deployed Engineer (FDE) is an engineer embedded at the customer's workplace. They sit with the people doing the work, find the real problem, and build working software in the customer's real environment. The page says the output is "Not a demo. Not a slide deck."

The page gives two compact definitions:

- **Palantir's framing:** a regular developer has "one capability, many customers." An FDE has "one customer, many capabilities."
- **Bai's hiring test:** an FDE is "a customer-facing software engineer." That means someone you would hire on the engineering bar alone and would also trust in front of a customer. Both halves must hold.

**FDE vs. Solutions Architect.** A Solutions Architect advises, runs demos and builds proof-of-concept prototypes on sample data, and usually winds down after the deal closes. An FDE writes production code on the customer's infrastructure with real data and stays until the customer gets value. The page's test: if the role is accountable for making customer-specific work function in production, it is closer to an FDE. If it is accountable for proving or explaining the product, it is closer to a solutions architect.

## 2. Why it works that way

Palantir created the role in the early 2010s, first calling the engineers "Deltas." Bai's account of why it was needed:

- The problem "was never the software." Foundry organizes a customer's data into an ontology. A business leader's reaction is "you have made my data organized, and what does that do for my business?"
- If the vendor only sells software, the customer pays twice. They pay for the platform, then pay again to train their own people to build on it.
- The fix is to sell the outcome, not software or hours. Send people who understand the customer's business, let them build the solution on the platform, and hand over the result.
- The buyers who needed this were Fortune 500 firms, such as oil and gas, that lack deep in-house engineering. For them FDEs were "engineers on loan." The client doesn't have to hire, manage or retain them.
- Bai cites average contract value as the evidence. Palantir is about $4M, ServiceNow about $1.2M and Workday about $600K, and no other public SaaS company is above $500K. He says selling outcomes prices differently from selling seats.

## 3. What breaks without it (the need test)

Bai's two-by-two screens whether a company needs an FDE function at all. The axes are how technical the product is and how technical the buyer is.

| Product | Buyer | Right motion |
|---|---|---|
| Technical | Technical (GitHub, Datadog) | Documentation and developer relations |
| Configurable | Technical | Self-serve or sales-led |
| Configurable | Non-technical (Rippling, Jira, Slack) | Traditional sales-led |
| **Technical** | **Non-technical** | **FDE, the only cell where it is necessary** |

What breaks without the screen:

- **If you skip the role when you're in the fourth cell,** you have a complicated product and a buyer who cannot implement it. The value never lands and the customer pays twice.
- **If you build an FDE function outside that cell,** you are chasing fashion. Bai says plainly that developer engagement or a sales-led motion fits better.
- **If you drop either half of the hiring test,** you get an account manager who cannot build, or an engineer who has to be kept away from the customer.

The page adds that because nearly every platform is now agentic and customizable, vendors are being pushed into the fourth cell. It gives this as the reason demand for the role grew in 2026. It also says Bai's square is a vendor's build-or-not decision, while Brunet's matrix (later on the same page) scopes a single engagement.

## 4. Worked example

A vendor sells an agent-building platform to a regional logistics firm. The firm's COO wants fewer late shipments and has no engineers.

1. **Screen:** the product is technical (an agent platform) and the buyer is non-technical, so this is the fourth cell and an FDE is warranted.
2. **Define the job:** the FDE does not demo the platform. They sit in the dispatch office, watch how late-shipment decisions are made, and find the real problem.
3. **Build:** they ship working software on the customer's real data and infrastructure, and stay until the COO sees the result.
4. **Check the role:** an engineer who only built a sample-data prototype and left after signing was acting as a solutions architect, not an FDE.

Contrast case: the same vendor selling to a bank's platform-engineering team is a technical product with a technical buyer. The screen points to documentation and developer relations, not an FDE.

## Quiz

**Q1.** Which phrase captures the difference between a regular developer and an FDE in Palantir's framing?
- A. Front-end vs. back-end
- B. One capability, many customers vs. one customer, many capabilities
- C. Remote vs. in-office
- D. Prototype vs. documentation

**Q2.** In Bai's two-by-two, which combination is the only one where forward deployment is necessary?
- A. Configurable product, technical buyer
- B. Technical product, technical buyer
- C. Configurable product, non-technical buyer
- D. Technical product, non-technical buyer

**Q3.** What is the simplest test the page gives for telling an FDE from a solutions architect?
- A. Who has the more senior title
- B. Whether they work for the vendor or the customer
- C. Whether the role is accountable for making customer-specific work function in production, or for proving and explaining the product
- D. Whether they write any code at all

**Q4.** According to Bai, what problem arises when a vendor only sells software to a non-technical buyer?
- A. The customer pays twice, once for the platform and again to train its people to build on it
- B. The customer can't afford the license
- C. The vendor's contract values rise too fast
- D. The platform cannot store the customer's data

## Answers

1. **B.** The page attributes "one capability, many customers" versus "one customer, many capabilities" to Palantir.
2. **D.** Technical product with a non-technical buyer is "the only cell where FDE is necessary."
3. **C.** The page frames it as accountability for production function versus accountability for proving or explaining the product.
4. **A.** The page says the vendor's success then depends on the customer's ability to use the software, so the customer pays twice. Bai's fix is to sell the outcome.
