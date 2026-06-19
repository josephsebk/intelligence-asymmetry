# From Information Asymmetry to Intelligence Asymmetry

*The web made information free. AI makes intelligence cheap. The second shift is bigger than the first, and it hits specific markets with predictable force.*

**Joseph Sebastian · February 2026**

---

Two concepts have caught my eye regarding AI recently,

## 1) The Perez Transition, A Familiar Pattern, a New Question

> *You can see the computer age everywhere but in the productivity statistics.*
> — Robert Solow, New York Times Book Review, 1987

Every major technological revolution follows the same arc. Capital floods into infrastructure first. Then, after a turning point that usually involves a financial crisis and a reckoning with overbuilt capacity, value migrates from the builders of infrastructure to the users of it.

The railways made more money for Standard Oil and Sears Roebuck than they did for most railway companies. The internet made more money for Google and Amazon than it did for Cisco and Level 3 Communications. Carlota Perez documented this pattern rigorously across five technological revolutions spanning two and a half centuries. It is among the most reliable patterns in the history of capitalism.

AI is currently deep in its infrastructure phase. Nvidia earned 73% gross margins on its GPU business in Q3 FY2025. Hyperscaler capex is projected to exceed $300 billion in 2025. Infrastructure spending outpaces application revenue by roughly 10:1. Menlo Ventures estimates companies spent $37 billion on generative AI in 2025, of which $18 billion went to infrastructure: foundation model APIs, training compute, and AI tooling.

Textbook Perez installation-phase dynamics.

But the Perez framework has a gap. It tells you that value will migrate from infrastructure to applications. It leaves open the question of *which* applications. Downstream uses of a technology revolution don't all capture value equally. A company that uses electricity to light its offices captures far less than one that uses electricity to reinvent manufacturing.

The question that matters for anyone allocating capital or building companies:

> Among all the industries that will use AI, where does it create structural change rather than incremental efficiency? Where does it go beyond making existing players faster and fundamentally restructure who captures margin and why?

I believe we are in the early stages of transition away from infrastructure to application. Which application would this move to? I believe the answer lies in intelligence asymmetry, and in a specific mechanical sequence through which AI disrupts markets where that asymmetry is wide.

*[Diagram: Perez tells you value migrates downstream. Intelligence asymmetry tells you which downstream markets.]*

---

## 2) Information Asymmetry to Intelligence Asymmetry

Economics has long understood that markets fail when participants possess different information. The theory of information asymmetry, formalized by Akerlof, Spence, and Stiglitz, earned its architects a Nobel Prize and provided the dominant lens for understanding why intermediaries exist, why markets for used cars and insurance suffer from adverse selection, and why vast pools of economic margin accumulate wherever one party in a transaction knows things the other does not.

Perhaps the single biggest value the web created was the disruption of structural information asymmetry. The web attacked this problem with devastating effectiveness. Job search portals, Craigslist, search engines, price comparison portals, review platforms, and digital marketplaces made information freely available to participants who previously had no access. Travel agents who profited from knowing flight schedules and seat availability lost their reason to exist. Ticket touts outside Indian cinema halls, who profited from knowing which shows had seats and which did not, disappeared. Stockbrokers who added value primarily through access to price data saw their commissions collapse.

But here is the puzzle that should bother anyone thinking about where AI creates real economic value:

**In many markets, the information is now freely available, yet the gap in outcomes between sophisticated and unsophisticated participants remains wide. In some cases it has widened.**

An Indian salaried professional can download an insurance product brochure, read the fine print, and access every commission disclosure mandated by the regulator. The information exists. Yet that professional still cannot decompose the effective internal rate of return on a unit-linked insurance plan, compare it against a term-plus-SIP alternative, evaluate mortality charge structures, or model the impact of different premium allocation ratios on terminal wealth.

A cardamom farmer in Kerala can see auction prices on a government app. They cannot integrate that price with monsoon forecasts, global demand from Guatemala, the futures curve on the Multi Commodity Exchange, and warehouse inventory levels across India.

A small manufacturer in Rajkot can read every line of a working capital loan agreement. They cannot decompose the effective annual cost, benchmark the spread against prevailing rates, evaluate whether the prepayment penalty is standard or punitive, or calculate the cost of the collateral requirement in forgone liquidity.

In each case, the data is right there. What's missing is the analytical capability to make sense of it.

This distinction, between **information asymmetry** (knowing what the facts are) and **intelligence asymmetry** (knowing what to do with them), goes well beyond semantics. It is the central economic question of the AI era.

*[Diagram: The web closed the first gap. AI closes the second. The second gap is wider, more persistent, and more economically significant.]*

One way to think about this is that reduction of intelligence asymmetry widens the bounds of Herbert Simon's concept of bounded rationality. The bounded rationality framework acknowledged that all human decision-makers have finite cognitive capacity. But Simon treated it as a roughly uniform condition. What we observe in practice is something more like *differential* rationality: the distance between effective analytical capability can be enormous. A Cargill commodity trading desk and a cardamom farmer in Idukki are both boundedly rational. But the distance between where their bounded rationality lands them is vast.

The web gave the farmer a smartphone with prices. It did not give them Cargill's analytical infrastructure. AI can.

---

### Example I
## The Farmer and the Trader

Consider the supply chain for cardamom in Kerala. A smallholder farmer with two or three acres of cardamom-producing land harvests and brings their crop to a local auction. Between that farmer and the global buyer, whether Cargill, Olam, or a large domestic spice processor, there are multiple layers of intermediation: local trader, regional aggregator, exporter, end buyer. At each layer, the participant closer to the global market has a substantial analytical advantage over the one further from it.

The farmer can see auction prices on the spices board website. The information is available. But the farmer cannot integrate that day's auction price with global cardamom supply from Guatemala (the world's largest producer), monsoon forecasts for the coming two months, the futures curve for small cardamom on the Multi Commodity Exchange, warehouse inventory levels across India, and the purchasing patterns of the three largest domestic processors.

The local trader can approximate some of this. Cargill's trading desk can do all of it, in real time, across dozens of commodities. The intelligence gradient from farmer to Cargill is enormous, and at every step along it, margin is extracted.

The farmer doesn't need to become Cargill. They need to go from making pricing decisions based on immediate cash needs and the local trader's offer to making decisions informed by a rough synthesis of the same factors Cargill considers. That leap, from the 5th percentile to the 50th percentile of commodity pricing decision quality, transforms the farmer's operation in all kinds of decisions. They may now choose not to expand their cultivation during periods of high price (every shortage led to a glut precisely because of this). But now the farmer can use a service that helps them analyse past data and ask the question on whether they should plant this year when prices are very high (the answer is no). This changes the bounds of rationality within which the farmer operated and will have significant impact on the value chain.

This isn't just theory. I have actually built a tool that helps cardamom farmers with precisely these kind of questions: [CardamomPulse](https://josephsebk.github.io/CardamomPulse/).

---

### Domain II
## The Small Business Owner and the Bank

A fifteen-person auto parts manufacturer in Rajkot needs working capital. The owner walks into a bank branch, talks to a relationship manager, and receives a loan offer: 14% interest, collateral requirement of 1.5x the loan value, a processing fee, and a prepayment penalty buried in the fine print. The owner has no basis for evaluating this offer. They have seen one, maybe two loan offers in their life. So they negotiate on the headline interest rate number and then they accept the offer.

Meanwhile, a large corporate borrower with a dedicated treasury team and relationships across six banks can decompose the all-in cost of each offer, benchmark it against the prevailing AAA corporate bond yield, negotiate away the prepayment penalty, evaluate whether a working capital loan or a receivables factoring facility is cheaper, and play lenders against each other for better terms. Two comparable large corporates borrowing from the same type of bank will see offers within 20 to 30 basis points of each other. Two comparable SME borrowers, same city, same sector, similar financials, can be paying rates 500 to 800 basis points apart. The corporate loan market prices on fundamentals. The SME loan market prices on whatever the borrower will accept. That dispersion is the intelligence tax made visible.

The information infrastructure exists. RBI mandates that banks publish their benchmark lending rates. Credit scores are available. Government portals list SME lending schemes. The Rajkot manufacturer can access all of it. But they cannot synthesize a bank's marginal cost of lending, compare it against the quoted rate, identify whether the processing fee is market-standard or inflated, or calculate the effective annual cost once prepayment penalties are factored in.

It is only a matter of time before AI lending advisors enter into this gap. The Reserve Bank of India's Account Aggregator framework, now reaching critical mass with over 100 million linked accounts, provides the data rails that AI advisory needs to function: a small business owner can consent to share their financial data across lenders, and an AI intermediary can evaluate all available offers in minutes.

The pattern extends well beyond lending. A shopkeeper signing a commercial lease, a family navigating a property transaction, an individual in an employment dispute: in each case the intelligence gap with the counterparty's professional advisors is extreme. The contract text sits in front of both parties. The ability to evaluate it often belongs to one side.

---

### Domain III
## The Patient and the Specialist

A patient diagnosed with stage II breast cancer sits across from an oncologist. The patient can access the same medical literature the oncologist has. PubMed is free. Clinical trial databases are public. NCCN treatment guidelines are published online. The information asymmetry that once characterized medicine has been substantially reduced.

The intelligence asymmetry remains vast.

The patient cannot synthesize their specific tumor pathology (ER-positive, HER2-negative, Ki-67 of 22%, tumor size 2.3 cm with one positive lymph node) with relevant clinical evidence, model the trade-offs between adjuvant chemotherapy and endocrine therapy alone, estimate the marginal survival benefit of adding four cycles of TC chemotherapy, or weigh that benefit against the toxicity profile and their personal values around quality of life.

This domain illustrates something important: the oncologist's intelligence advantage is *real and genuinely earned*, unlike in some of our other examples where the intermediary's analytical superiority serves their margin more than the customer's interest. But even here, the intelligence asymmetry has consequences. Patients who cannot evaluate their options are unable to participate meaningfully in shared decision-making. They accept what is recommended without understanding the trade-offs. In systems with fee-for-service incentives, the recommendation may be influenced by reimbursement structures.

AI treatment navigation tools are entering this space. Systems that ingest a patient's complete record and produce a structured analysis of options with supporting evidence are being piloted at academic medical centers. The patient doesn't become an oncologist. They cross a threshold: from passive acceptance to informed participation. They can ask, "What is the absolute survival benefit of adding chemotherapy in my specific case?" and understand the answer well enough to make a genuine choice.

Two features of the mechanism are visible here. First, intelligence asymmetry reduction only requires the unsophisticated party to cross a threshold of functional competence, not to reach the analytical frontier. Second, the trust and relational value of the oncologist remain high. The mechanism compresses the analytical component of the gap while leaving the relational component largely intact.

---

## Two Forces That Shape the Transition

The three domains above illustrate the mechanism. But they don't explain why the structural direction favors gap compression rather than gap preservation. Two opposing forces determine this.

### Force I: The Concavity of Returns

The returns to AI-augmented analysis are concave. The marginal benefit of AI is substantially larger for a participant starting at a low level of analytical sophistication than for one starting at a high level.

*[Diagram: The concavity of returns to AI. The marginal benefit is highest where analytical capability was previously most scarce. This is the structural reason the gap compresses rather than persists.]*

The cardamom farmer who goes from pricing decisions based on the local trader's offer to decisions based on an AI-generated synthesis of weather, demand, and inventory data experiences a transformative leap. Cargill's trading desk, which already integrates all these signals and more, gets a marginal improvement: slightly faster analysis, slightly broader coverage. The farmer's decision quality jumps from the 10th percentile to the 55th. Cargill's moves from the 92nd to the 94th.

There is growing empirical support. Brynjolfsson, Li, and Raymond (2023) studied AI-augmented customer service workers and found that productivity gains were concentrated among the least experienced and lowest-performing workers. The top performers saw minimal improvement; the bottom performers saw dramatic gains. Research using Chinese firm-level data found the same pattern at the enterprise level. A study in the Journal of Monetary Economics found that when the Transformer architecture made processed data widely accessible, it substituted for advanced proprietary AI, enabling lower-AI firms to narrow the gap with high-AI counterparts.

Concavity follows from the mathematical structure of the capability-to-outcome function. Decisions made with very little analysis are often very bad. Decisions made with moderate analysis are usually adequate. Decisions made with expert analysis are marginally better. The low-hanging fruit of decision improvement is captured first. This is why the farmer benefits more than Cargill, the SME borrower more than the bank's treasury desk, and the patient more than the oncologist.

### Force II: The Walmart Problem

But there is a countervailing force. In practice, the sophisticated party almost always adopts AI first.

Cargill integrates satellite imagery and machine learning into its commodity models years before the average farmer gets an AI crop advisor. Banks deploy AI credit scoring and dynamic pricing before SME borrowers get AI-powered loan comparison tools. Walmart deployed AI negotiation bots against 20,000 small suppliers, extracting better terms at scale, before those suppliers had access to comparable tools.

In the near term, AI can actually *widen* intelligence asymmetry. A bank RM equipped with an AI-generated propensity score becomes more effective at selling suboptimal products. An insurance company using AI for lead scoring targets the most susceptible customers with greater precision.

**So which force wins?**

The Walmart problem is transitional. AI tools are commoditizing rapidly; the cost of deploying capable analysis has fallen by orders of magnitude since 2022 and continues to fall. There is a powerful commercial incentive to build consumer-side tools, because the margin pool being disrupted represents a large addressable market for whoever captures even a fraction of it on the consumer's behalf.

Concavity is structural. It derives from the mathematical properties of the capability-to-outcome function, which does not change with deployment patterns. However fast the sophisticated side adopts, the marginal gain from moving a naive participant to "good enough" will always exceed the marginal gain from moving an expert to "slightly better."

The Walmart problem determines the path and the speed. Concavity determines the destination.

---

## Predicting Where the Mechanism Hits Hardest

Given the mechanism and the forces that shape it, we can build a framework for prediction. Two dimensions matter:

*[Diagram: The two-dimensional framework. Markets in the upper right, where intelligence gaps are wide and intermediary value is primarily analytical, face maximum disruption. Healthcare sits slightly left because the doctor's relational value is genuinely high.]*

**Dimension 1: How wide is the intelligence gap** between the participants in a typical transaction? Agricultural commodities (Cargill vs. smallholder farmer) and retail insurance (bank RM vs. salaried professional) have extreme gaps. Institutional FX trading has a narrow gap. Wider gaps mean more margin attributable to intelligence asymmetry and more margin exposed to compression.

**Dimension 2: How much of the intermediary's value derives from analytical sophistication versus other sources?** An insurance agent who helps customers understand products provides analytical value: AI replaces this. An agent who assists with claims and provides reassurance provides relational value: AI doesn't. A notary whose existence is legally mandated provides compliance value: AI can't bypass this.

The maximum disruption zone: wide gap, primarily analytical intermediary value.

**Buyer sophistication, not the B2C/B2B label, determines gap width.** Some B2B transactions have intelligence gaps as wide as any consumer transaction. The Rajkot manufacturer we discussed is, for analytical purposes, as unsophisticated as a retail borrower. They see one or two bank offers and accept. The 400–600 basis point spread between SME and large corporate borrowing rates is partly credit risk, partly an intelligence tax. Screen on buyer analytical infrastructure, not on buyer category.

---

## Where the Mechanism Does Not Apply

A framework earns credibility by specifying its limits. Four boundary conditions:

**Regulatory moats.** Insurance distribution requires a license. Legal advice requires bar membership. These create delays, not barriers. Discount brokers became thin wrappers around algorithmic strategies despite regulatory requirements for licensed intermediation.

**Trust and behavioral value.** A mutual fund distributor who talks a panicking client out of redeeming during a crash provides value that is relational, emotional, and behavioral. AI can simulate empathy, but it cannot replicate trust built through years of interaction, particularly in contexts where financial literacy is low and communication happens via WhatsApp and phone calls rather than apps.

**Agency asymmetry.** Even when the intelligence gap closes, action may be constrained. The farmer who knows to wait cannot wait if they need cash to repay a loan. The SME owner who knows they're overpaying cannot switch lenders if their bank holds cross-collateralized security. Intelligence improves in theory while remaining unrealized in practice.

**Non-analytical intermediary value.** An investment banker's M&A value is that they know who the buyers are and have their phone numbers. A luxury brand's margin derives from social signaling. A notary's value is legal mandate. The mechanism doesn't operate where margin isn't built on an analytical gap.

---

## The Three-Layer Investment Lens

Assembling the argument into a unified framework:

*[Diagram: Three-layer screening lens. Each layer narrows the field. The intersection of all three identifies the highest-conviction structural opportunities.]*

**Layer 1: The Perez direction.** Value migrates from AI infrastructure to AI applications. Look downstream, not upstream. The infrastructure buildout is well-understood and increasingly priced in. The application layer, where AI meets specific industries and restructures their economics, is where the largest risk-adjusted returns lie.

**Layer 2: The intelligence asymmetry filter.** Among all industries that will use AI, the largest value redistribution occurs where intelligence asymmetry is wide and intermediary margins are built on that asymmetry. The 2x2 (gap width times analytical content of intermediary value) is the screening tool. Agricultural intermediation, retail insurance, SME lending, small-business professional services: upper-right quadrant.

**Layer 3: The concavity filter.** Within those sectors, the biggest delta accrues to products and companies that serve the less sophisticated party. This is the most counterintuitive filter. A company building AI tools for bank RMs to sell more effectively is an arms race play. A company building a fiduciary AI advisor that helps consumers evaluate insurance products is a structural play. A company building AI crop advisory for smallholder farmers disrupts agricultural intermediation margins far more than a company optimizing Cargill's already-sophisticated models.

The concavity of returns means the marginal benefit is largest when AI reaches the unsophisticated side of the transaction. That is where the structural value lies.

---

## The Force, Not the Forecast

This essay has described a force, and deliberately avoided making a forecast. I don't claim to know the precise timing of the transition in any sector, the exact share of intermediary margin attributable to intelligence asymmetry, or the specific path through which consumer-side AI advisory will reach the Indian smallholder farmer or the first-time insurance buyer.

What I have done is identify a mechanism, describe its steps, demonstrate that it is already operating in multiple domains, and establish the structural reasons that determine its direction.

The web made information free. AI makes intelligence cheap.

The economic consequences of the second shift are at least as large as the first. They are concentrated in sectors and transactions where one party's inability to analyze freely available information has been the primary source of the other party's margin.

Intelligence asymmetry will be compressed. That much is certain. The real questions are who builds the tools, which side of the transaction they serve, how quickly they reach the unsophisticated party, and whether the regulatory environment accelerates or retards that deployment.

The largest welfare gains, and the largest investment returns, lie with whoever answers those questions first.

---

*If you found this useful, subscribe for more at the intersection of AI, economics, and emerging markets. Share it with someone who's thinking about where to allocate capital in the AI era.*

---

## Appendix: The Tinder Problem — What Happens After the Gap Closes

There is a tempting implication in everything above: that intelligence asymmetry compression leads to a flatter, more equal economic landscape. It doesn't. It leads to a more efficient one. And efficient markets are generous to the best participants, not the average ones.

The web era proved this. Before the internet, information asymmetry protected thousands of mediocre businesses. A local travel agent survived because customers couldn't easily compare prices across airlines. A middling stockbroker kept clients because they had no convenient alternative for accessing price data. A decent restaurant in a small town thrived because potential competitors had no low-cost way to advertise. The fog of information asymmetry created a kind of artificial equality: it hid the gap between the best and the rest.

The web lifted that fog. And rather than creating a thousand equally successful competitors, it created Booking.com, Robinhood, and Amazon. When search costs fall to zero, the actually-best offering becomes visible to everyone simultaneously, and everyone picks it. The market clears toward a handful of winners.

Scott Galloway makes this point about dating apps. Before Tinder and Hinge, dating markets were local and informationally constrained. You met people through friends, work, your neighborhood, your religious community. Friction created a rough equality of opportunity. Dating apps made the market efficient, and efficient markets concentrate: the top 20% of men receive roughly 80% of the right swipes. This is what happens when you remove search costs from any matching market.

The pattern, stated abstractly: asymmetry compression produces market efficiency, and market efficiency produces winner-take-most outcomes. The question is where this shows up in the three domains we have discussed.

In agricultural commodities: if every farmer gets AI-powered pricing and demand forecasting, the local trader's margin disappears. But the farmers aren't made equal. The ones who combine AI intelligence with better land, better logistics, better cooperative structures, and better access to credit will capture disproportionate share. The "efficient" market reveals which farmers were genuinely productive versus which ones were merely well-connected or lucky.

In SME lending: if AI makes loan comparison and term benchmarking free, the business owners who were always sharp operators but simply lacked financial analysis capability will secure far better terms than before. The ones who were weak operators hiding behind relationship banking will be exposed. The intelligence tax paid to banks gets partially redistributed, but unevenly. The best-run businesses capture most of the surplus.

In healthcare: if patients can all access AI second opinions, the truly excellent oncologists become visible and in higher demand. The mediocre ones who survived partly on information asymmetry, partly on patients' inability to evaluate their recommendations, lose patients to the recognized best.

This isn't a dystopian outcome. The pre-compression world wasn't fair either; it was merely opaque. The farmer who got a bad price, the SME owner who signed a terrible loan agreement, the patient who received a suboptimal treatment recommendation: they weren't being protected by intelligence asymmetry. They were being taxed by it. Compression removes the tax. It also removes the fog that allowed mediocre participants on both sides to muddle through.

For investors, the Tinder Problem adds a refinement to the concavity argument. Concavity tells you that AI benefits the unsophisticated party more than the sophisticated party. The Tinder Problem tells you that *among* the newly empowered unsophisticated parties, the gains will concentrate. The farmer who uses AI *and* has good land *and* joins a well-run cooperative captures far more value than the farmer who just uses AI. The SME owner who uses AI loan comparison *and* runs a tight operation *and* has strong receivables captures far more than the one who just has the comparison tool.

The concavity of returns tells you the gap compresses. The Tinder Problem tells you what the post-compression landscape looks like: a new set of peaks, not a flat field.

---

## Appendix 2: Six Steps from Intelligence Gap to Market Restructuring

The intelligence asymmetry thesis identifies a specific, traceable, step-by-step causal chain through which AI restructures a market. The sequence has six steps:

**1. An existing equilibrium sustained by an intelligence gap.**
An intermediary captures margin between two parties. The stated justification is advisory or expertise. In practice, the intermediary's analytical capability is at least partly deployed in service of their own margin rather than the customer's interest. The gap is wide enough that the less sophisticated party cannot evaluate whether the advice is good, conflicted, or wrong.

**2. Information infrastructure has been built, but hasn't solved the problem.**
The web, regulation, or digital platforms have made data available. The less sophisticated party can access prices, disclosures, or terms. But they cannot analyze this information effectively. The information layer is necessary groundwork, not the disruption.

**3. AI enters on the unsophisticated side.**
An AI system is deployed that serves the less sophisticated party. It can decompose pricing, compare alternatives, identify conflicts of interest, model outcomes. The party's analytical capability jumps from roughly the 5th percentile to the 60th percentile of decision quality in that domain.

**4. The intermediary's analytical advantage erodes.**
The intermediary's value proposition, to the extent it was genuinely analytical, is now redundant. The portion that was analytical theater, justifying commissions rather than serving the customer, is exposed.

**5. The margin compresses.**
Through two channels: direct substitution (parties move to lower-cost channels) and informed negotiation (parties benchmark intermediary recommendations against AI analysis, eroding the ability to steer toward suboptimal-but-high-margin products).

**6. New equilibrium.**
Intermediaries whose value was primarily analytical lose margin. Those whose value was relational, behavioral, or regulatory (trust, hand-holding, compliance) survive and may see their value proposition clarified. The margin pool shifts in composition: less payment for analytical superiority, more for relational value.

This sequence is abstract by design. Its power is its generality: it applies, with variations in speed, wherever the preconditions are met.
