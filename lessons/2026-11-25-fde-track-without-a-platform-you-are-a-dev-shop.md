# FDE Track: Without a Platform, You Are a Dev Shop

Source: `roles-this-book-trains`, section `the-forward-deployed-engineer-fde-the-vendor-neutral/the-hardest-objection-without-a-platform-you-are-a-dev-shop`. Everything below comes from that page. The page attributes the argument to the practitioner Bai and cites it to its own footnote (24), which I have not checked independently. I could not call `begin_session` (no such tool was available), so I did not check the learner's current course through the connector. I chose this topic because no existing lesson in `lessons/` covers this section.

## 1. What it is

The page calls this "the hardest objection" to the FDE role. The objection is that an FDE function cannot survive in an enterprise. Building something custom for every customer leaves you "herding dozens of repositories nobody can maintain," and engineers who "quit rather than learn them."

Bai agrees, with one condition. If every FDE builds entirely from scratch, then "you do not have an FDE function, you have a dev shop." The page calls a dev shop "a profitable business, possibly, and not the same business."

What makes it an FDE function is this: **the engineers never write software from scratch.** A set of **shared primitives** already exists, and the engineer assembles them into something arbitrarily valuable to the customer.

On how granular the primitives should be, Bai gives no universal answer:
- In some industries the application is 60% built and the customer customizes the rest.
- In others the domain demands granular tooling.
- The comparison he uses is AWS, which hands you DynamoDB so nobody has to invent a database, because it serves an extremely broad set of customers.

## 2. Why it works that way

- **Maintenance cost scales with bespoke code.** Every from-scratch engagement adds a codebase someone has to keep alive. The page says the maintenance cost "will eat your profit and loss statement."
- **Reuse is the difference between the two businesses.** Assembling shared primitives spreads their cost across customers. Writing from scratch does not.
- **The page makes this the bill for vendor-neutrality.** Its preceding argument is that a vendor platform is a cage. A vendor-neutral FDE leaves the cage, but "strip out the vendor and you have removed the shared primitives along with the cage."
- **The honest self-test.** Bai's question to turn on yourself: "Do I have a platform, or am I willing to invest in building one?"
- **The page says the answer comes next.** The vendor-neutral FDE does carry shared primitives. They are "simply not code owned by a vendor." The page says the next section ("What fills the pod: two Systems of Record") covers this, and I have not read it for this lesson.

## 3. What breaks without it

- **A "pod of one" becomes "a dev shop of one."** The page's words are: bespoke code at every client, nothing reused.
- **The maintenance load grows with each engagement** until it eats the margin.
- **Staff turnover.** Engineers who have to learn many unmaintainable repositories may resign. The page says this applies "assuming your engineers have not all resigned first."
- **You may still have a business, but the wrong one.** It may be profitable, but it is not an FDE function.

## 4. Worked example

This example applies the page's logic and is not taken from it. The numbers are invented for illustration.

An FDE serves three customers.

**Scenario A (dev shop):** For each customer the FDE writes a new integration from nothing. After three engagements there are three separate repositories. Each one has to be maintained and each one has to be learned by anyone who takes it over. The next customer adds a fourth.

**Scenario B (FDE function):** The FDE starts each engagement from shared primitives that already exist. The customer-specific work is assembling them into something valuable for that customer. A new engagement adds an assembly, not a new foundation.

The page's test applies to both scenarios: "Do I have a platform, or am I willing to invest in building one?" Scenario A answers no. Scenario B answers yes.

## 5. Quiz

**Q1. According to the page, what makes an engineering function an FDE function rather than a dev shop?**
A. Its engineers work only for large enterprises
B. Its engineers never write software from scratch, because shared primitives already exist
C. Its engineers write every customer's software in a single repository
D. Its engineers avoid customer contact

**Q2. What does the page say happens if every FDE builds entirely from scratch?**
A. The customer pays less
B. The business stops being profitable under every circumstance
C. You have a dev shop, and the maintenance cost will eat your profit and loss statement
D. The vendor takes over maintenance

**Q3. Why does the page call this objection "the bill for vendor-neutrality"?**
A. Vendors charge a fee for neutrality
B. Stripping out the vendor removes the shared primitives along with the cage
C. Vendor-neutral FDEs are not allowed to reuse code
D. Vendor platforms are cheaper than custom builds

**Q4. Which question does the page offer as the honest test to turn on yourself?**
A. "Can I write this faster than the last engineer?"
B. "Is my customer larger than the last one?"
C. "Do I have a platform, or am I willing to invest in building one?"
D. "Can I avoid maintaining anything?"

### Answers

1. **B.** The page says the engineers "never write software from scratch" and assemble shared primitives instead.
2. **C.** The page says that without shared primitives "you have a dev shop" and "the maintenance cost will eat your profit and loss statement."
3. **B.** The page says that stripping out the vendor "removed the shared primitives along with the cage."
4. **C.** This is Bai's own test, quoted on the page.
