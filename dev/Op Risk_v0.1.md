# Operational Resource Attribution and Operational Risk

## A Unified Framework for IFRS 17 Expense Attribution and Operational Risk Capital in General Insurance

# Abstract

Operational expense attribution and operational risk capital are currently treated as separate problems in general insurance practice. IFRS 17 requires the systematic and rational attribution of directly attributable expenses to insurance contract groups but does not prescribe a methodology for doing so. Operational risk frameworks separately estimate capital requirements for operational failure without connecting those estimates to the operational expense base they are intended to protect. Despite both measuring consequences of the same underlying operational system, no common framework currently links them.

This paper proposes a unified operational resource framework grounded in a single first principle: an insurance contract is not only a financial obligation but also an operational obligation, requiring the consumption of resources across acquisition, maintenance, fulfilment and governance activities. These obligations are delivered through two distinct layers: an Insurance Service Layer comprising activities directly attributable to individual contract groups, and an Operational Support Layer comprising institution-level activities required to sustain service delivery across the portfolio.

Within this framework, expected resource consumption gives rise to operational expense attribution. Operational risk arises when realised resource consumption deviates from the level required to sustain the intended delivery of insurance services. The tail of that deviation distribution gives rise to operational risk capital. Operational expense attribution and operational risk capital therefore emerge from the same underlying resource measurement framework rather than from separate frameworks. 

As a consequence, the framework derives expected operational cost and operational risk capital from the same underlying operational resource framework, producing a consistency relationship between expense attribution and operational risk measurement.

The framework operates across both insurance service and reinsurance activities, providing a consistent basis for attributing operational costs associated with policy fulfilment, reinsurance placement and recovery. It also makes visible and attributable sources of operational uncertainty that are currently embedded implicitly within technical assumptions, including parameter risk loadings in stochastic reserving and process risk adjustments in actuarial assumptions.

The framework is illustrated across major operational structures in general insurance, including broker distribution, delegated underwriting authority, fronting arrangements, facultative reinsurance placement and third-party capital structures, without requiring 
structural modification to the underlying framework. A three-phase implementation roadmap is provided, progressing from IFRS 17 expense attribution using existing cost-centre data through operational deviation measurement and capital attribution to state-based stochastic operational risk modelling and internal model integration. The framework further provides a foundation for future extensions into strategic 
capital planning, where theoretical capital derived from the same contractual and operational state may be used to assess latent capital commitments before they emerge in reported capital metrics.

---

# 1. Introduction

## 1.1 The Operational Attribution Problem

Insurance entities operating under IFRS 17 are required to attribute directly attributable expenses to groups of insurance contracts on a systematic and rational basis. This requirement applies to acquisition costs, maintenance expenses and the operational costs of fulfilling contractual obligations across the coverage period.

In practice, the attribution of operational expenses to contract groups presents a significant implementation challenge. Directly attributable expenses are frequently incurred at portfolio level or above, requiring allocation downward to contract groups through methods that are not prescribed by the standard. 

Non-directly attributable general and administrative expenses fall outside the insurance service result entirely under current guidance, creating a structural gap between the operational cost of running the business and the reported cost of fulfilling insurance contracts.

[REFERENCE REQUIRED:
IFRS 17 implementation guidance,
TRG discussions,
or practitioner surveys showing
variation in attribution approaches]

The consequence is that fulfilment cash flows used in the measurement of insurance contract liabilities, the identification of onerous contracts, and the determination of the contractual service margin are systematically incomplete. Contract groups whose fulfilment requires high operational intensity carry insufficient expense in their measured cost. Contract groups whose fulfilment is operationally straightforward carry excess allocation. The onerous contract test is performed on a cost base that does not reflect the true operational 
burden of each contract group.

No systematic actuarial methodology currently exists for attributing operational expenses to contract groups in a manner that reflects the operational intensity of specific relationships, business types and fulfilment activities in general insurance.

---

## 1.2 The Operational Risk Capital Disconnection

Operational risk capital in general insurance is currently estimated through approaches that share a common structural limitation: they measure realised operational loss events rather than the underlying operational state from which those events emerge.

Scenario-based assessments construct hypothetical loss events and score their severity and frequency. Loss distribution approaches fit statistical distributions to historical loss data. Premium and reserve proxies apply uniform loadings derived from industry averages. In each case the capital charge is derived from observed or hypothesised loss outcomes rather than from the operational processes and relationships that generate those outcomes.

[ANCHOR: Insert brief literature anchors — Basel II definition, 
Solvency II SCR operational risk formula, BMA equivalents, 
LDA limitations from Frachot et al and Dutta and Perry]

Consider a reinsurer operating a mature casualty portfolio. No major operational failure has occurred. Claims continue to be processed. Regulatory obligations continue to be met. Financial reporting remains timely. Internal audits identify no material control breaches.

Over time, however, small operational deteriorations begin to accumulate. Experienced staff leave and are replaced with less experienced personnel. Legacy systems become increasingly difficult to maintain. Claims volumes grow faster than operational capacity. Management reporting becomes progressively more manual. Governance reviews continue to be completed, but with increasing effort and reduced depth of challenge.

Viewed independently, each deterioration appears manageable. Staff turnover remains within acceptable limits. Service levels remain broadly compliant. System outages remain infrequent. Governance processes continue to operate. No individual indicator is sufficiently severe to trigger management intervention.

Collectively, however, these deteriorations alter the operational state of the organisation. The deterioration is not caused by a single operational failure. Rather, it emerges from the cumulative interaction of changes in operational relationships, capability, structure and governance, each of which remains individually within acceptable limits. Additional staff are required to sustain existing service levels. Training, supervision and coordination requirements increase. Operational expenses rise while organisational responsiveness declines. The organisation becomes progressively less capable of identifying and responding to emerging issues before they materialise.

The resulting deterioration may emerge through increased expense ratios, claims leakage, service failures, broker dissatisfaction, regulatory findings or reduced profitability. Such outcomes are often recognised only after they become visible in financial or operational results. Existing operational risk frameworks are generally calibrated to discrete events and realised losses. They provide limited visibility into the gradual accumulation of operational deterioration that precedes those outcomes.

Three structural limitations follow from this approach.

### Retrospective

The capital charge is calibrated from loss history that is sparse, inconsistently recorded and dominated by low-severity  high-frequency events that bear limited relationship to the tail losses the model is intended to capture. 

### Undifferentiated  

The same loading is applied regardless of the operational quality of specific functions, the friction generated by specific 
counterparty relationships, or the direction of miscalibration. An institution that is operationally over-extended in one area and under-resourced in another carries the same capital charge as one that is uniformly well-managed.

### Unattributable

The capital number produced cannot be traced to the organisational processes, functions or relationships responsible for 
generating it. It satisfies a regulatory requirement without informing a management decision.

The operational risk capital charge and the operational expense base are typically estimated through separate processes. Operational expenses are recognised through budgeting, planning and financial reporting frameworks. Operational risk capital is estimated through scenario assessments, loss distributions or regulatory formulae. While some entities may implicitly allow for expected operational losses within planned expenses, there is generally no formal mechanism linking the operational state reflected in the expense base to the operational state assumed by the capital framework.

As a result, operational expenses and operational risk capital are often treated as separate measurements despite both arising from the same underlying operational system. The framework proposed in this paper establishes a common measurement basis by treating expected operational resource consumption as the expression of the current operational state and operational risk as deviation from that state. Operational expense attribution and operational risk capital therefore emerge from the same underlying measurement framework rather than from independent assumptions.

---

## 1.3 The Operational Structure Attribution Gap

Current operational risk measurement approaches are not only disconnected from the expense base — they are structure-dependent. Different approaches are applied to different business types, different counterparty structures and different operational arrangements, without a common measurement basis across them.

A general insurer writing direct business, a syndicate operating through binding authorities, a reinsurer managing a portfolio of facultative placements, and a captive fronted through a carrier each face operationally distinct arrangements. 

Current frameworks treat each as requiring separate modelling assumptions, separate scenario libraries and separate capital loadings. The operational cost of a fronting arrangement, a delegated underwriting authority, an adverse development cover, or a sidecar structure is not systematically captured within any current operational risk framework.

[ANCHOR: Insert one concrete example here of a current practice 
gap — e.g. how fac placement operational costs are currently 
treated in a Lloyd's syndicate internal model, or how coverholder 
operational risk is captured in a binding authority arrangement]

The consequence is that as business structures become more complex — greater use of delegated authority, increased reliance on third-party capital, more sophisticated reinsurance structures — the operational risk framework becomes progressively less complete rather than adapting to the changing operational reality of the business.

A measurement framework that is genuinely useful to a general insurance actuary must operate consistently across the full spectrum of operational structures without requiring structural modification to its underlying logic.

---

## 1.4 Objectives of this Paper

This paper has four objectives.

First, to establish a first-principle measurement basis for attributing operational expenses to insurance contract groups. The framework is designed to satisfy the systematic and rational attribution requirement of IFRS 17 while reflecting the operational intensity of individual contracts, relationships and fulfilment activities.

Second, to derive an operational risk capital methodology from the same operational resource framework, establishing a consistent measurement basis for both operational expense attribution and operational risk capital.

Third, to demonstrate that the framework operates across the principal operational structures of general insurance practice, including delegated underwriting, reinsurance structures, and third-party capital arrangements.

Fourth, to provide a practical implementation roadmap that enables progressive adoption by general insurance actuaries, beginning with existing cost-centre data and extending to stochastic state-based calibration of the framework.

---

## 1.5 Summary of Contributions

This paper makes four principal contributions to general insurance actuarial 
practice.

It establishes operational resource consumption as the common measurement 
basis for both IFRS 17 expense attribution and operational risk capital, 
resolving the structural disconnection between two frameworks that currently 
measure consequences of the same underlying operational system independently.

It derives the consistency identity — expected operational risk equals expected 
operational cost — as a consistency identity from first principles rather than an accounting 
observation, with direct implications for the coherence of internal models that 
estimate the two quantities independently.

It demonstrates structural invariance across the principal operational 
arrangements of general insurance practice, providing a single framework that 
attributes operational cost and capital consistently across direct, delegated, 
reinsurance and third-party capital structures without modification.

It provides a three-phase implementation roadmap that makes the framework 
accessible to a general insurance actuary using existing data infrastructure, 
with a defined progression to state-based stochastic modelling for entities 
with more advanced operational risk measurement ambitions.

This paper presents the framework through the practical problems of operational 
expense attribution and operational risk capital in general insurance. The 
underlying measurement basis is more general. By establishing a common basis 
for expected operational resource consumption and its deviations, the framework 
provides a foundation for future extensions into strategic capital planning, 
portfolio emergence analysis and long-term capital management. These extensions 
are discussed briefly in Section 10 but are not required for implementation of 
the framework presented here.

The framework developed in this paper does not begin with operational risk. It begins by identifying the underlying object that operational risk acts upon. Section 2 therefore establishes the first-principle basis of that object before deriving the subsequent measurement framework.

---

## 1.6 Structure of the Paper

Section 2 establishes the first principles from which the framework is derived. 
Section 3 presents the operational obligation framework across its four 
categories. Section 4 defines the resource framework distinguishing internal, 
external, shared governance and capital support resources. Section 5 reviews 
current practice and identifies the specific gaps the framework addresses. 
Section 6 provides the formal statement of the framework including the 
operational resource measure, deviation distribution and capital emergence 
structure. Section 7 establishes the governance architecture. Section 8 
illustrates the framework across the principal operational structures of general 
insurance practice. Section 9 provides the three-phase implementation roadmap. 
Section 10 discusses extensions. Section 11 concludes.

# 2. First Principles

2.0 Emergence of the Operational Layer

Insurance did not begin as an institution. It began as an agreement between people who understood the same risk.

In the coffeehouses of late seventeenth-century London, merchants, ship owners and sea captains gathered not to transact within a formal insurance market but to exchange reliable information about voyages, vessels, trade routes and counterparties. Edward Lloyd’s establishment became known for the quality of its maritime intelligence, attracting those involved in shipping and overseas trade. As confidence in that information grew, the coffee house became a natural meeting place where merchants seeking protection for voyages met individuals willing to subscribe portions of those risks. The market emerged from the concentration of information and commercial knowledge before it became a formal insurance institution.  

In this setting, the person accepting a share of the risk was typically also the person who bore the financial consequence of that decision. Knowledge of the voyage, the judgement to accept the risk, the capital standing behind that judgement, and accountability for the outcome remained closely aligned. The credibility of the insurance promise rested primarily on the judgement and financial capacity of those subscribing the risk, and comparatively little operational infrastructure was required because these functions had not yet become institutionally separated.

As insurance markets expanded, that unity gradually dissolved. Risks became larger, more specialised and more geographically dispersed. Capacity was increasingly pooled across multiple participants. Professional underwriters assessed risks on behalf of capital providers. Brokers emerged as specialist intermediaries. Claims handling, actuarial analysis, accounting, legal support and regulatory oversight developed as distinct professional functions. The person providing capital was no longer necessarily the person assessing the risk, administering the contract or managing the claim. The insurance promise increasingly depended upon a growing operational system rather than solely upon the judgement and wealth of a single individual.

For much of Lloyd’s history, unlimited personal liability continued to provide a powerful alignment mechanism. Individual Names ultimately remained responsible for the obligations undertaken in their name, creating strong incentives for underwriting discipline and prudent management. However, the market itself had already become operationally sophisticated, relying on specialised functions that extended far beyond the original coffeehouse model.

The transition following the Lloyd’s crisis of the late 1980s and early 1990s accelerated this structural evolution. Corporate and institutional capital entered the market on a much larger scale, while unlimited personal liability ceased to be the dominant mechanism supporting the insurance promise. The credibility of that promise became increasingly dependent upon institutional capability: underwriting discipline, actuarial reserving, governance oversight, regulatory compliance, capital management, claims operations and the wider operational infrastructure required to sustain the insurer throughout the life of the contract.

This historical development does not create operational obligations; rather, it makes them visible. The activities required to establish, maintain and fulfil insurance contracts had always existed in some form, but as insurance evolved from personal underwriting to institutional risk-bearing, those activities became increasingly specialised, measurable and economically significant. The operational system ceased to be an incidental feature of the insurance business and became an essential component of the promise itself.

This transition gives rise to the measurement problem addressed in this paper. Financial obligations have long been recognised, valued and reported through established actuarial and accounting frameworks. The operational obligations required to create, sustain and discharge those financial obligations remain comparatively fragmented, appearing across expense allocations, governance activities, operational processes and capital management without a unified measurement basis.

The framework developed in the sections that follow treats those operational obligations as measurable objects. It does not replace the financial obligation created by the insurance contract. Rather, it makes explicit the operational system through which that financial obligation is continuously established, maintained and ultimately fulfilled.

## 2.1 Insurance Contracts as Operational Obligations

An insurance contract is conventionally measured as a financial obligation: a promise to pay contingent amounts in defined circumstances, valued through the expected present value of its cash flows. This account is complete as a description of what the contract pays. It is silent on what the contract does.

What the contract does is effect a transfer. The insured carries an exposure whose materialisation would impose a loss exceeding what it can absorb from its own resources. The contract relocates the financial consequence of that materialisation to the insurer. In exchange for a premium, the insurer assumes the exposure in whole or in part, such that the originating party's risk of ruin from any single adverse event is reduced or eliminated. The contract does not prevent the loss from occurring. It determines who bears it when it does.

The decisive observation is that this transfer is not lossless. It does not take effect at the moment the premium is paid and lie dormant until a claim arises. It requires an operational system to come into being — and to persist, actively consuming resource, for as long as the obligation endures. That system does not appear fully formed at the point of contract. It must be built, stage by stage, before the contract exists, and it must be sustained, continuously and at cost, until every obligation under it is discharged.

The construction of that system begins earlier than the accounting record suggests. An exposure must first be identified — by the insured recognising a risk it cannot retain, by a broker identifying a coverage gap in a client's programme, or by a market participant actively developing demand for a class of risk not yet widely placed. A distribution channel must be activated. A submission must be prepared and presented. A counterparty relationship must be initiated and assessed: the creditworthiness, background and suitability of the specific insured must be evaluated before any terms are offered. The risk itself must be underwritten — analysed, modelled, priced and structured. Coverage terms must be negotiated, documented and agreed. Reinsurance must be arranged where the written exposure exceeds the insurer's intended net retention. Capital must be allocated against the obligation being assumed. Only then is the contract bound, and only at that point does it enter the accounting record as a recognised liability.

From that point, a further and more extended set of obligations begins. The contract must be administered across its full coverage period. Premiums must be collected and applied. Policy documentation must be maintained. Endorsements, amendments and mid-term adjustments must be processed. Claims must be notified, assessed and settled — some promptly and without dispute, others requiring extended investigation, expert involvement, legal coordination and negotiated resolution over months or years. Reserves must be established, maintained and reviewed as information develops. Regulatory reporting obligations must be met. Governance processes must be sustained. The reinsurance programme supporting the written portfolio must be actively managed, and recoveries pursued where claims fall within its scope. In long-tail classes, these obligations may persist for years or decades beyond the expiry of the original coverage period.

At no point in this sequence is the contract operationally passive. Resource is consumed before the contract exists, at the moment it is bound, and continuously throughout its life. The early consumption is real but unrecorded: the system must operate for a considerable period before it is recognised as a system, and the resource consumed in bringing a contract into existence is consumed whether or not any accounting entry is made against it. The later consumption is recorded, but conventionally as undifferentiated expense rather than as the discharge of specific obligations attached to specific contracts.

It follows that an insurance contract is an operational obligation at every stage of its emergence and continuation, not only at the point of claim. The financial obligation is the promise to pay. The operational obligation is everything the institution must do, and every resource it must consume, to keep that promise. These are not two descriptions of the same thing. The financial obligation can be stated without reference to the operational system that delivers it. The operational obligation cannot be understood without tracing every activity, every function and every resource commitment that fulfilment of the financial promise requires.

Because the system that keeps the promise is one of people, processes and relationships rather than a frictionless mechanism, its resource consumption can deviate from what fulfilment requires. That deviation — its measurement, its attribution and its consequences for both operational expense and capital — is the subject of this paper.

## 2.2 Operational Obligations and Resource Consumption

Every stage of the operational sequence established in 2.1 consumes resource. That consumption is the subject of this section — not what the obligation requires in terms of activity, but what it requires in terms of resource, and why the full range of that resource matters for measurement.

Operational resource is not limited to what appears in the insurer's own cost base. It takes four distinct forms, each corresponding to a dimension of the obligation that must be sustained for the contractual promise to remain deliverable.

The first is **relational** resource: the effort invested in initiating, maintaining and renewing the cooperative relationships on which the contract depends. A submission does not arrive without a broker relationship. A claim does not settle without counterparty engagement. A renewal does not occur without a continuing dialogue between insured, broker and underwriter. These relationships must be actively cultivated and sustained. They are not free. They consume time, judgement and presence — and they deteriorate if not maintained.

The second is **structural** resource: the frameworks, arrangements and commitments that organise how the obligation is held and discharged. Reinsurance structures must be placed and maintained to support the capacity being offered. Delegated underwriting authorities must be established, governed and monitored. Legal frameworks must be in place to enforce the terms of the contract. Documentation must be produced and maintained in a form that supports the obligation across its full life. These structural commitments are themselves operational obligations — arrangements that must be entered into, managed and renewed, each consuming resource in their own right.

The third is **legitimacy** resource: the institutional standing that makes the promise credible to the parties who rely on it. Regulatory authorisation must be obtained and maintained. Actuarial sign-off must be provided on reserving and pricing assumptions. External audit must be completed. Rating agency assessments must be supported and managed. Professional standards must be met. These are not administrative burdens peripheral to the insurance contract. They are the conditions under which the promise is recognised as valid by the policyholder, the capital provider and the wider system within which the contract operates. A promise made by an institution that cannot demonstrate regulatory standing, actuarial integrity and governance discipline is not a credible promise, however well-funded it may be.

The fourth is **capacity** resource: the human effort, systemic capacity and capital deployed in the direct execution of the obligation. Underwriting judgement, claims expertise, actuarial analysis, legal coordination and management oversight constitute the human dimension. Policy administration platforms, claims management infrastructure and reporting environments constitute the systemic dimension. Capital deployed as a risk-support resource — occupying capacity that cannot simultaneously be applied elsewhere and released only as obligations are discharged — constitutes the financial dimension.

Each form shares three properties that are fundamental to the measurement framework that follows. Resource is real: it exists and is consumed independently of whether it is recorded, attributed or recognised in any accounting framework. Resource is finite: the same unit of relational effort, structural commitment, legitimacy standing or capacity cannot be simultaneously applied to two obligations. And resource is consumed: it is expended in the act of fulfilment and does not accumulate or carry forward.

The source of the resource does not alter any of these properties. Whether a given obligation is discharged internally — by the insurer's own staff, systems and capital — or externally, through a broker, a reinsurer, a third-party administrator, a managing agent, an auditor, a legal panel, a rating agency or a regulator, the resource consumed is equally real, equally finite and equally expended. A broker commission and an internal acquisition function discharge the same relational obligation. An external audit and an internal compliance review discharge the same legitimacy obligation. A reinsurance premium and an internally held capital reserve discharge the same structural obligation. The channel differs. The consumption does not.

This equivalence has a direct and material consequence for measurement. The operational cost of a contract cannot be assessed by reference to the insurer's internal cost base alone. A contract placed through a delegated underwriting authority, supported by a reinsurance structure, administered by a third-party claims handler, validated by an external actuary and governed under a regulated framework consumes resource across all four dimensions and across both internal and external sources. That consumption is real whether it appears in the insurer's own expense account or in the fees, commissions, premiums and regulatory costs paid to external parties. A measurement framework that captures only internally incurred operational expense is incomplete by construction — and its incompleteness is not random. It systematically understates the operational burden of precisely those contracts and structures where external resource is most heavily used.

It follows that the full operational resource consumed across the life of an insurance contract — in all four forms, from all sources, at every stage of the obligation — is a measurable object. Identifying it, attributing it to the specific obligations it serves, and connecting it to the specific contracts those obligations attach to is the task the framework developed in this paper is designed to perform.

The four resource forms identified above are universal: every insurance contract, at every stage of its life, consumes relational, structural, legitimacy and capacity resource in some combination. What varies is the configuration. The relative weight of each form, the stage at which it is most intensively consumed, and the degree to which it is sourced internally or externally differs materially across provider types, business lines, distribution structures and counterparty relationships. That variation is not noise in the measurement. It is the signal. Understanding why the configuration varies — and what drives that variation — is the necessary step before expected resource consumption can be defined as a measurement object.

## 2.3 Why the Operational Obligation Varies

The operational obligation does not vary randomly. It varies because the system that holds and discharges it is not a fixed mechanism. It is a living arrangement of people, relationships, commitments and processes — each element dependent on the others, each subject to its own pressures, and each capable of transmitting stress through the system when it deteriorates.

Consider what it actually takes to keep a single insurance promise. A shared understanding must exist between the parties — the risk described in the submission must be the risk the underwriter priced, and the coverage written must mean the same thing to the person who wrote it and the person who relies on it at the point of loss. The architecture of commitments surrounding the contract must hold — the reinsurance structure must respond as intended, the delegated authority must operate within its boundaries, the relationships between insurer, broker, coverholder and administrator must remain clear about who carries what obligation. The institution must continue to operate within the conditions that give its promise legal and professional standing — regulatory authorisation maintained, governance processes followed, actuarial standards met. And across all of this, the system must execute — claims settled correctly, reserves established accurately, recoveries pursued, returns filed, policies administered without error.

None of these requirements operates independently of the others. A submission that misrepresents the risk creates a meaning problem that becomes a structural problem when the reinsurance does not respond and an execution problem when the claim is disputed. A departure of a key underwriter is a structural disruption that degrades execution quality and may create a regime risk if that person carried a controlled function. A governance failure that allows an underwriting decision to be taken outside the agreed authority does not remain a regime failure — it propagates into structural gaps and eventually into realisation shortfalls when the exposure develops in ways the capital allocation did not anticipate. A compliance breach does not sit in isolation — it consumes management attention, generates remediation resource, and disrupts the relational environment with regulators and counterparties simultaneously.

This is the nature of a complex operational system. Failures do not arrive in labelled categories. They emerge from the interaction of elements that were each individually within acceptable limits, accumulating through the system until the combined effect becomes visible — often in a form quite different from the original source of stress. The operational obligation varies not because its components vary independently but because the system as a whole is sensitive to the state of every element within it, and the deterioration of any element changes the resource required to sustain all the others.

What follows from this is a measurement requirement, not a categorisation requirement. The question is not which type of failure occurred. The question is what state the operational system is in — across all its elements and all their interdependencies — and how far that state deviates from the condition required to discharge the obligation at the level the contract demands. That deviation, and the resource required to correct it, is the origin of operational risk. Expected resource consumption — the subject of the next section — must therefore be defined as a property of the system in its full complexity, not as a sum of independently estimated components.

## 2.4 Expected Resource Consumption and Expense Discipline

Underwriting discipline is the practice of not accepting the class loss ratio as the correct loss assumption for every contract within that class. The underwriter looks at the specific risk, the specific counterparty, the specific terms — and makes a judgement that the standard assumption does not adequately reflect what this contract will cost in claims. The loss ratio varies by contract because the underwriter's assessment of the specific risk varies. That variation is not noise. It is the signal that underwriting discipline is working.

Expense discipline is the exact parallel. The expense ratio should not be fixed at class level and applied uniformly to every contract within that class. Two contracts in the same class, carrying the same exposure and the same contract structure, may have materially different operational resource demands — and therefore materially different true expense ratios. The contract that required three rounds of information requests, a specialist referral, two mid-term endorsements and a disputed claim consumed more operational resource than the contract that was a clean renewal through an established broker relationship. Both carry the same class expense ratio. Neither is correctly measured.

Recognising that difference — and acting on it in pricing, in portfolio management and in the assessment of contract profitability — is expense discipline. It requires no model beyond what underwriting discipline already demands. It requires the same judgement-based awareness applied to the operational cost dimension of the contract rather than to its loss expectation. An experienced underwriter already knows implicitly that a difficult cedant, a complex placement or an operationally intensive relationship costs more to service. Expense discipline makes that implicit knowledge explicit and gives it a place in the pricing conversation alongside the loss ratio assumption.

The absence of expense discipline is not evenly distributed across markets. In personal lines, where products are standardised and individual underwriting touchpoints are minimal, the within-class variation in operational resource consumption is real but relatively contained. The uniform expense ratio is a reasonable approximation with corrections needed primarily at the channel and segment level. In commercial direct lines, bespoke coverage terms, variable servicing intensity and individual claims complexity produce material within-class variation that the uniform ratio cannot capture. The operational cost of writing a large complex commercial property policy and a small straightforward SME policy in the same class are not the same — and pricing both at the same expense ratio misrepresents the economics of each. In reinsurance the absence of expense discipline is most consequential. A proportional treaty with a well-governed cedant, clean bordereaux and a long renewal history consumes a fraction of the operational resource required by a complex facultative placement, a poorly governed cedant relationship or a structure requiring active claims coordination across multiple parties and jurisdictions. The gap between the uniform class expense ratio and the true operational cost of each contract is not a calibration imprecision. It is a structural misrepresentation of the economics of the book — with direct consequences for pricing adequacy, cedant relationship profitability and capital allocation.

The principle extends beyond general insurance. Any contract that creates an obligation requiring sustained operational performance across time generates expected resource consumption that is measurable at the obligation level. In long-tail general insurance, the duration of the liability begins to introduce an investment dimension — the float generated by the premium held between receipt and claims payment earns a return that is implicitly part of the contract economics, and the operational resource required to manage reserving, actuarial review and claims development across years or decades is material. In guaranteed annuity business, the investment dimension is not supplementary but central — the ALM function that matches asset cash flows to annuity payments across thirty or forty years is the primary operational obligation, and the investment return is not separable from the cost of keeping the promise but is the mechanism through which the promise is kept. Across this full spectrum — from short-tail property through long-tail casualty to guaranteed annuity — the principle holds: expected resource consumption is derived from what the specific obligation requires, at the specific stage of its lifecycle, through the specific operational structure through which it is held and discharged. The configuration of that resource varies with the duration, certainty and complexity of the liability. The principle of derivation does not.

In practice, expected resource consumption at the contract level aggregates upward — to contract group as the attribution unit for IFRS 17 purposes, and from there to the management accounting reporting layer at which performance is assessed, pricing adequacy is reviewed and capital is allocated. Full granularity at the individual contract level is implemented where the data infrastructure supports it. Structured approximation using observable resource intensity proxies — renewal history, distribution channel, counterparty complexity, mid-term activity, claims history, reinsurance involvement — is applied where it does not. What is non-negotiable at every point on that spectrum is that the expense ratio is derived from what the specific obligation demands, not from what the class average implies.

Expected resource consumption, so defined, is the cost of running the business. It is not a risk charge. It is not a capital requirement. It is not a stress or a scenario. It is the ordinary, expected, unavoidable cost of honouring every operational obligation the institution has assumed — across every contract, every counterparty relationship, every governance requirement and every fulfilment activity that keeping the promise demands. When that cost is correctly derived from the obligation downward and attributed to the contracts that created it, it becomes the baseline from which all subsequent measurement in the framework proceeds. Operational expense attribution is derived from it. Operational risk arises when realised resource consumption deviates from it. And operational risk capital is determined by the distribution of that deviation. The cost of running the business and the capital required to protect against operational failure are therefore not two separate measurements. They are two expressions of the same underlying quantity — one describing what fulfilment is expected to cost, the other describing what happens when it costs more or less than expected. That relationship, and its consequences for both expense attribution and capital, is the subject of the section that follows.

## 2.5 Deviation from Expected Fulfilment

Deviation arises when realised resource consumption departs from the level the operational obligation requires. It is measured as the difference between what the system actually consumed and what fulfilment of the specific obligation demanded under normal operating conditions.

Deviation is symmetric. It runs in both directions and both directions are real. Upward deviation — realised consumption exceeding expected — means the system absorbed more resource than the obligation required. Downward deviation — realised consumption falling below expected — means the system either delivered less than the obligation demanded, or has genuinely improved in efficiency such that the same obligation can now be discharged at lower cost. The direction is diagnostic. It informs the investigation of cause and the nature of the state change that produced the departure. It does not change the classification. Departure from the expected state in either direction is deviation.

Deviation is not primarily a financial event. It is a state condition. The operational system is either in the state required to discharge its obligations at the standard they demand, or it is not. A system that is consuming more resource than expected is under strain — absorbing the cost of failures, inefficiencies or capacity mismatches that the obligation did not require. A system that is consuming less may be improving — or it may be degrading, substituting junior resource for senior, bypassing governance steps, or reducing the depth of review without reducing its nominal frequency. In both cases the financial consequence may not be immediately visible. The state has changed. The financial outcome follows later.

This is why deviation cannot be measured through loss events alone. A regulatory fine, a claims handling error, a reserving shortfall — each is a financial expression of an operational state that had already departed from its expected condition before the loss crystallised. The state change preceded the financial outcome. Measuring deviation through its financial consequences captures the arrival of the outcome, not the accumulation of the condition that produced it. A complete measurement framework must track the state of the operational system directly — as a leading indicator of financial deviation, not only as a lagging record of financial loss.

## 2.6 Operational Risk

Operational risk is the uncertain operational cost — the distribution of realised resource consumption across the full life of the institution's obligations. It is not an event category. It is not a residual after market and credit risk have been measured. It is a primary property of the operational system — present whenever realised resource consumption departs from what the obligation demands, in either direction, for any reason.

Expected resource consumption is not operational risk. It is the cost of running the business — the ordinary, unavoidable expenditure required to discharge the institution's obligations under normal operating conditions. Operational risk is the deviation from that cost. A system operating exactly at its expected consumption level is not bearing operational risk in the sense the framework defines — it is bearing operational cost. Operational risk begins the moment the system departs from that level.

The mean of that distribution is expected resource consumption — the cost of running the business, recovered through the expense loading in premium. The variance of that distribution reflects the stability of the operational system. The tail above the mean is the portion that cannot be recovered through pricing — and it is this tail that gives rise to operational risk capital. 

Its distribution — the range and likelihood of departures from the expected state in both directions — is the operational risk profile of the institution. The variance of that distribution reflects the stability of the operational system. The tail reflects exposure to severe disruption — the events that consume resource at multiples of the expected level, or that reveal sustained state deterioration that has been accumulating invisibly before surfacing as a financial outcome.

Capital is required because the tail of that distribution cannot be recovered through pricing alone. The expense loading in premium recovers expected operational cost. It does not protect against severe deviation. The capital held against operational risk is therefore not a charge against the cost of running the business. It is a charge against the risk that the business will not run as expected — and that the consequences of that failure will exceed what the expense base can absorb.

Because expected cost and operational risk capital are both derived from the same obligation-referenced baseline — one measuring the centre of the deviation distribution, the other measuring its tail — they are not independent quantities. They are two expressions of the same underlying measurement. Because the mean of the operational risk distribution is expected resource consumption, expected operational risk equals expected operational cost. This is not an assumption. It is true by construction — the mean identity follows directly from defining operational risk as the full distribution of realised resource consumption rather than as a separate capital charge estimated independently of the expense base."

This is not an assumption embedded in the framework. It is a structural consequence of deriving both quantities from the same first principle: that an insurance contract is an operational obligation, that discharging it requires resource, and that the deviation of realised from expected resource consumption is the origin of operational risk.

This equality — expected operational risk equals expected operational cost — is the consistency identity the framework establishes. It is absent from current practice, where operational expenses and operational risk capital are estimated through separate processes with no formal connection between them. The framework proposed in this paper closes that gap — not by assertion, but by deriving both quantities from the same obligation-referenced baseline that the first principles of this section have established.

---

# 3. Operational Obligation Framework

The preceding chapter established that every insurance contract creates both a financial obligation and an operational obligation. This chapter develops the operational obligation framework used throughout the remainder of the paper.

The framework is founded on a simple observation. An insurance contract cannot be created, sustained or fulfilled without operational activity. Every operational activity performed by a general insurer exists because it contributes, directly or indirectly, to the establishment, continuation or discharge of contractual obligations.

Rather than viewing operational activities through organisational structures such as departments, reporting lines or cost centres, the framework classifies activities according to the operational obligation they fulfil. This provides a stable measurement basis that remains valid irrespective of organisational design.

## 3.1 Four Operational Obligations

Every insurance contract simultaneously creates four operational obligations.

Acquisition

The obligation to establish an insurable relationship and obtain sufficient information to enter the contract.

Maintenance

The obligation to preserve the capability required to administer and support the contract throughout its lifetime.

Fulfilment

The obligation to execute the contractual promises made to policyholders and counterparties when contractual events occur.

Governance

The obligation to preserve the legitimacy, solvency and regulatory standing required for the insurer to continue honouring contractual promises.

These four obligations exist simultaneously. They are not sequential phases of a contract, nor are they mutually exclusive. A single operational activity may contribute to more than one obligation, but every activity can ultimately be attributed to one or more of these four categories.

The framework therefore treats these four obligations as collectively exhaustive for the purposes of operational resource attribution within general insurance.

## 3.2 Continuity Principle

Operational obligations do not necessarily terminate at the contractual boundary.

The financial obligation created by an insurance contract normally concludes when contractual obligations expire or are discharged. The operational relationship, however, frequently continues beyond that point.

Renewal negotiations, customer servicing, broker relationships, delegated authority oversight and historical underwriting knowledge all persist across successive policy periods. The operational state established during one contract therefore influences the operational resources required for subsequent contracts.

A renewal should therefore not be viewed as an entirely new operational event. It represents the continuation of an existing operational relationship whose accumulated history affects future operational resource consumption.

## 3.3 Seasoning Principle

Operational resource consumption generally declines as operational relationships mature.

New business requires the establishment of an entirely new operational relationship. Information must be gathered, validated and assessed. Counterparties are unfamiliar. Internal processes are initiated for the first time.

As the relationship develops, much of this information has already been acquired. Operational effort progressively shifts from establishment towards maintenance.

Consequently, expected operational resource consumption for an established renewal relationship is generally lower than for otherwise equivalent new business.

This reduction does not arise from commercial pricing strategy. It arises because less operational resource is required to establish confidence in a relationship that has already accumulated operational history.

## 3.4 Information Accumulation Principle

Information accumulated through prior operational activity represents an operational asset.

Credit assessments, underwriting reviews, policy administration, broker interactions, delegated authority oversight and historical claims experience all contribute to reducing future operational effort.

The insurer has already consumed operational resources to acquire this information in previous periods. Future renewals therefore benefit from operational knowledge that does not require complete recreation.

The framework treats accumulated operational information as reducing future expected operational resource consumption while recognising that significant changes in exposure, counterparties or external conditions may require renewed acquisition effort.

## 3.5 Adverse Selection Principle

Operational resource consumption depends not only upon insured risk but also upon relationship behaviour.

A policyholder who changes insurer at every renewal requires repeated acquisition activities, including information gathering, underwriting assessment and relationship establishment.

A long-standing renewal relationship requires substantially less acquisition effort because much of the operational information already exists.

Two policyholders may therefore exhibit identical expected claims costs while generating materially different operational resource requirements.

The framework recognises this distinction by separating insurance risk from operational resource consumption.

## 3.6 Contract Boundary Principle

Financial contract boundaries and operational boundaries are not identical.

IFRS 17 defines contract boundaries for the measurement of financial obligations. Operational relationships frequently extend beyond those boundaries through continuing customer relationships, broker engagement, delegated authority arrangements and accumulated institutional knowledge.

Accordingly, financial obligations may reset at contract renewal while operational relationships continue.

This distinction provides the conceptual basis for recognising operational resource consumption independently from the financial obligation itself.

## 3.7 Institutional Governance Seasoning

The seasoning principle applies not only to policyholder relationships but also to institutional relationships.

A newly established insurer generally incurs substantial governance resource consumption associated with regulatory approval, capital model development, governance establishment, audit arrangements, rating agency engagement and supervisory interaction.

As institutional relationships mature, many of these activities become routine. Governance effort increasingly shifts from establishment towards ongoing maintenance and incremental enhancement.

The framework therefore treats governance obligations as dynamic rather than constant throughout the institutional lifecycle.

## 3.8 Collateral Analogy

Collateral requirements provide a practical illustration of governance seasoning.

A newly established insurer frequently faces higher collateral requirements because counterparties and regulators possess limited operational history upon which to assess institutional capability.

As operational credibility develops through demonstrated performance, governance relationships mature and collateral requirements may decline.

The reduction reflects neither reduced financial obligation nor reduced insurance risk alone. It reflects increased confidence in the insurer’s operational capability to fulfil its contractual commitments.

This illustrates a broader principle of the framework: operational history itself possesses measurable economic value because it reduces future operational resource consumption.

---

# 4. Resource Framework

Core principle:
Resources are consumed in fulfilling operational obligations. Resources are either internal or external. External resources are not less operational because they are purchased — broker commission, fac placement costs, TPA fees are all externalised operational resource consumption.
Internal resources     →    People, systems, capital
External resources     →    Brokers, TPAs, advisers
Shared governance      →    Actuarial, finance, compliance
Capital support        →    Cost of risk-bearing capacity
Attribution follows consumption. Resources consumed in fulfilling a specific contract group are attributed to that contract group. Resources consumed at portfolio or entity level are attributed through the Operational Support Layer.

## 4.1 Internal Resources

## 4.2 External Resources

## 4.3 Shared Governance Resources

## 4.4 Capital Support Resources

## 4.5 Resource Attribution

---

# 5. Current Practice

Core principle:
Current practice has three structural failures.
Retrospective     →    Measures loss after crystallisation
                       not condition before it

Undifferentiated  →    Same loading regardless of
                       counterparty, function, direction

Unattributable    →    Capital number cannot be traced
                       to the process that generated it
Parameter risk loadings in stochastic reserving, process risk adjustments in actuarial assumptions, and entity-level risk register entries are all implicit operational deviation measurements. The framework makes them explicit and attributed.
---

# 6. Formalisation

Core principle:
The framework produces a closed-form operational loading applicable to any existing risk measure:
Adjusted Risk
=
Base Risk
× (1 + R)(1 + Y)(1 + S)(1 + I)^(1+r+y+s+i)
Where R, Y, S, I are dimensional deviation states across acquisition, maintenance, fulfilment and governance, and r, y, s, i are interaction terms capturing propagation between dimensions.
At optimal calibration all deviations are zero and the expression equals base risk. No operational loading. Cost neutral.

[ANCHOR: RYSI introduced here as the state assignment mechanism producing R, Y, S, I parametrically in Phase 1 and stochastically in Phase 3]

Regulatory capital applies a floor at zero — no credit for over-calibration, consistent with Solvency II SCR treatment. Economic capital is unbounded in both directions, capturing the real cost of over-calibration as well as under-calibration.
The consistency identity follows directly:
E[Operational Risk] = E[Operational Cost]

Capital charge = Tail above E[Operational Cost]
The mean of the operational risk distribution is already sitting in the expense base. The capital model and the IFRS 17 expense attribution are two readings of the same measurement.
[ANCHOR: Reserve risk by cohort application — formula applied to reserve risk producing operationally adjusted development factors]
[ANCHOR: Premium risk application — formula applied to loss ratio producing operationally adjusted combined ratio]
[ANCHOR: Credit risk application — formula applied to reinsurance counterparty exposure]

## 6.1 Operational Resource Measure

## 6.2 Expected Operational Resource Consumption

## 6.3 Operational Cost Attribution

## 6.4 Operational Deviation Measure

## 6.5 Operational Loss Emergence

## 6.6 Operational Loss Distribution

## 6.7 Capital Emergence from Tail Deviation

## 6.8 Mean and Tail Interpretation

## 6.9 Expected Operational Cost and Expected Operational Risk

## 6.10 Sources of Operational Deviation
Degradation
Shock
Representation Error
Expectation Failure

---

# 7. Governance Framework

## 7.1 Ownership of Operational Activities

## 7.2 Attribution Governance

## 7.3 Resource Governance

## 7.4 Operational Risk Governance

## 7.5 Monitoring and Escalation

## 7.6 Model Governance

---

# 8. Practical Applications

Ex-Ante Reinsurance Structures
Portfolio Construction Decisions
    ↓
What operational state
am I choosing to write into?
What operational obligations
am I transferring?

Ex-Post Reinsurance Structures
Legacy Portfolio Management
    ↓
What operational state
already exists?
What latent uncertainty remains?

Direct Insurance Operations

## 8.1 Broker Commission and Distribution Costs

### 8.1.1 Broker Commission

### 8.1.2 Acquisition Resource Consumption

### 8.1.3 Expected and Unexpected Distribution Costs

---

## 8.2 Fronting Arrangements

### 8.2.1 Operational Obligations Retained by the Fronting Carrier

### 8.2.2 Operational Obligations Delegated to the Fronted Party

### 8.2.3 Governance Resource Consumption

### 8.2.4 Operational Deviation and Counterparty Failure

---

## 8.3 Binding Authority and Coverholder Arrangements

### 8.3.1 Delegated Acquisition and Underwriting Activities

### 8.3.2 Externalised Operational Resources

### 8.3.3 Operational Deviation from Underwriting Quality

### 8.3.4 Governance and Oversight Costs

---

## 8.4 Facultative Reinsurance

### 8.4.1 Placement Activities

### 8.4.2 Broking and Negotiation Resources

### 8.4.3 Expected Placement Cost

### 8.4.4 Resource Consumption Under Market Dislocation

---


8.5 Legacy Portfolio Management
    ↓
8.5.1 The Ex-Post Decision Framework
8.5.2 Adverse Development Covers
8.5.3 Loss Portfolio Transfers
8.5.4 Run-off Covers and Sidecars



## 8.5 Adverse Development Covers
Here is the first draft of Section 8.5.

---

## 8.5 Adverse Development Covers

### 8.5.1 Reserve Deterioration as Prior Operational Deviation

An adverse development cover is a reinsurance structure under which the reinsurer agrees to absorb reserve deterioration beyond an agreed attachment point. The purchasing decision is conventionally framed as a question of reserve stability: if carried reserves are adequate and development patterns are mature, the ADC premium appears to be the cost of transferring a risk the cedant's own actuarial analysis considers remote.

This framing contains a structural limitation. Reserve stability is an actuarial judgment derived from a methodology that is itself subject to model risk. The cases where ADC purchases appeared wasteful in hindsight are observable precisely because the reserves did not deteriorate. The cases where they proved prescient share an identical prior condition — the actuary also assessed reserves as stable, until systematic deterioration emerged across the book simultaneously.

The relevant question is therefore not whether reserves are stable. It is whether the structural assumptions underlying the stability assessment are themselves correctly calibrated. Latent liability emergence, judicial inflation, and correlated claims handling optimism are not random deviations from an otherwise sound methodology. They are structural failures — deterioration in the So dimension of the external operational state — that affect entire cohorts simultaneously before appearing in any individual development triangle.

Under the operational resource framework, the need for an ADC is not primarily a signal of known reserve inadequacy. It is a signal of prior structural operational deviation that has not yet crystallised in reported metrics. The ADC is the financial response to an operational condition.

---

### 8.5.2 Operational Obligations Created by ADC Structures

The execution of an ADC creates ongoing operational obligations that current frameworks do not systematically measure.

The cedant retains obligations to the ADC provider across the full run-off period of the covered reserves. These include periodic reserve reporting, claims development notifications, settlement approvals above defined thresholds, commutation negotiations, and collateral management where required. Each obligation consumes operational resource in the actuarial, finance, legal, and governance functions.

Under the operational resource framework, these obligations are attributed as follows. Reserve reporting and development notification obligations are fulfilment obligations attributable to the portfolio covered by the ADC. Settlement approval and commutation obligations are governance obligations attributable at entity level where they require board or senior management involvement. Collateral management obligations are capacity obligations consuming treasury and finance resource continuously across the cover period.

The ADC premium is therefore not the complete cost of the structure. The full operational cost includes the present value of the resource consumption required to service the ongoing obligations across the run-off period. An ADC covering a long-tail casualty portfolio with a fifteen-year run-off horizon carries substantially more operational obligation cost than one covering a short-tail property portfolio with a three-year horizon. Current practice does not distinguish between them on this basis.

---

### 8.5.3 Steady-State Capital and the Optimal Purchase Window

The operational resource framework provides a precise timing signal for ADC purchase decisions through the steady-state capital measure.

Steady-state capital is the capital requirement implied by the current portfolio structure when projected to a mature operating state. Where steady-state capital exceeds available capital, the portfolio has already committed more capital on a forward basis than is currently available to support it — a latent capital deficit not yet visible in reported metrics.

Three capital perspectives are relevant to the ADC purchase decision:

```
Actual Capital
    ↓
Current reported position
Incorporates reported reserve
at carried level
Development patterns as booked

Projected Capital
    ↓
Balance sheet rolled forward
under business plan assumptions
Reserve emergence at expected
development factors

Steady-State Capital
    ↓
Capital requirement at maturity
of current portfolio
Including systematic model risk
across the full reserve cohort
```

Where steady-state capital materially exceeds projected capital, the gap represents the capital required to absorb systematic methodology error — the correlated deterioration that affects the entire book simultaneously rather than individual claims. This is the capital that the ADC transfers to the reinsurer.

The optimal ADC purchase window is therefore identified by the steady-state capital signal rather than by observed reserve deterioration:

```
Buy when:

Steady-state capital
exceeds available capital
AND the gap is not yet visible
in reported development patterns

AND the So dimension
shows early structural signal —
methodology assumptions drifting,
pricing cycle optimism
not yet in development factors,
judicial inflation not yet
reflected in tail factors

AND market conditions are soft —
ADC market pricing on
reported stability
not on steady-state capital gap
```

This window typically precedes visible reserve deterioration by two to four years. The ADC market prices on reported conditions. The steady-state capital framework sees the latent strain before the market does.

---

### 8.5.4 Investment Return and the Transfer of Model Risk

The conventional objection to ADC purchase in a stable reserve environment is that the investment return on the covered reserves remains with the cedant — why transfer it to the reinsurer through a premium?

Under the steady-state capital framework this objection is reframed precisely. Where steady-state capital equals available capital, reserves are genuinely stable in forward terms. The investment return belongs to the cedant with confidence. The ADC premium is optionality the cedant does not need.

Where steady-state capital exceeds available capital, the investment return on covered reserves is not the cedant's to retain with confidence. It belongs economically to the latent liability not yet recognised in the carried reserve. The ADC premium converts an uncertain investment return into a certain cost. The cedant is not giving away investment return. The cedant is crystallising a liability uncertainty into a known premium.

```
Steady-state capital = available capital
    ↓
Reserves genuinely stable
Investment return retained with confidence
ADC is expensive optionality

Steady-state capital > available capital
    ↓
Latent strain exists
Investment return belongs to
unrecognised latent liability
ADC converts uncertainty to known cost
Premium is justified
by the steady-state gap
```

The So dimension loading in the operational state framework provides the mechanism. A structural dimension under stress indicates that the reserve methodology is drifting from correct calibration. The loading quantifies the capital implied by that drift. The ADC premium, correctly priced, should approximate the present value of the expected steady-state capital gap above the attachment point.

---

### 8.5.5 Attribution of ADC Cost under IFRS 17

Under IFRS 17, the ADC is a reinsurance contract held and is measured separately from the underlying insurance contracts issued. The reinsurance contract asset is the present value of expected recoveries net of the premium ceded.

Under the operational resource framework, the ADC premium is attributed as a fulfilment cost of the portfolio covered by the structure. It is not a general overhead or an entity-level governance cost. It is the cost of transferring the model risk associated with a specific reserve cohort, and it is attributable to the contract groups within that cohort in proportion to their contribution to the steady-state capital gap.

This attribution produces a more complete fulfilment cash flow for the covered contract groups than current practice achieves. The onerous contract test applied to those groups includes not only the carried reserve and expected claims development but also the cost of the structural model risk that the ADC is purchased to transfer. Contract groups whose reserves carry high So dimension loading — long-tail casualty, latent liability, emerging risk classes — attract a higher attributed ADC cost than short-tail classes with low structural loading, correctly reflecting their contribution to the latent capital strain.

The reinsurance outwards RYSI state conditions the expected recovery efficiency of the ADC. A reinsurer whose own Io and So dimensions are deteriorating — governance under stress, contract wording disputes increasing — carries a higher recovery friction loading. The net reinsurance asset under IFRS 17 is reduced accordingly, producing a more conservative fulfilment cash flow than a model that treats recovery as certain.

---

## 8.6 Sidecars and Third-Party Capital

### 8.6.1 Investor Reporting Obligations

### 8.6.2 Collateral Management

### 8.6.3 Capital Provider Resource Consumption

### 8.6.4 Operational Equilibrium of Capacity Structures

---

## 8.7 Claims Operations

### 8.7.1 Expected Claims Resource Consumption

### 8.7.2 Complex and Litigated Claims

### 8.7.3 Operational Loss Emergence

---

## 8.8 Capital Management Activities

### 8.8.1 Capital as a Risk-Support Resource

### 8.8.2 Expected Capital Consumption

### 8.8.3 Rating Agency Operational Assessments

### 8.8.4 Capital Strain and Operational Deviation

## 8.9 Reinsurance Recoveries and Outwards Operational Attribution.

---

# 9. Implementation Roadmap

## Phase 1 — Operational Expense Attribution

### 9.1 Existing Cost Centre Mapping

### 9.2 Resource Consumption Mapping

### 9.3 IFRS 17 Expense Attribution

### 9.4 Management Reporting

### 9.5 Performance Attribution

---

## Phase 2 — Operational Risk Attribution

### 9.6 Operational Deviation Measurement

### 9.7 Operational Loss Attribution

### 9.8 Operational Risk Metrics

### 9.9 Operational Capital Attribution

---

## Phase 3 — Advanced Operational Risk Modelling

### 9.10 State-Based Operational Models

### 9.11 Operational Signal Sets

### 9.12 Transition Structures

### 9.13 Stochastic Simulation

### 9.14 Internal Model Integration

### 9.15 SCR Attribution

---

# 10. Extensions

## 10.1 IFRS 17 Reporting

## 10.2 GAAP Expense Allocation

## 10.3 Tax Attribution

## 10.4 Amortisation Frameworks

## 10.5 Rating Agency Capital

## 10.6 Enterprise Performance Management

## 10.7 Strategic Extension: Steady-State Capital and GI Balance-Sheet Emergence

The operational resource framework may be extended to support strategic capital planning through a Steady-State Capital measure. Steady-State Capital is the capital requirement produced by the existing capital model when applied to the premium, reserve and margin profile implied by the current written portfolio at maturity. It is not a regulatory stress and does not replace existing one-year capital requirements.

Three capital perspectives may be considered simultaneously. Actual Capital reflects the current reported position, incorporating both current strategy and the continuing emergence of prior underwriting and operational decisions. Projected Capital reflects management expectations by rolling the current balance sheet forward under business plan assumptions — capturing the evolution of the current portfolio over the next few years as premium earns, reserves develop and new business is written. Steady-State Capital isolates the long-term capital commitment implied by current underwriting, pricing and portfolio decisions — independent of legacy obligations — providing an ex-ante view of future capital need before it emerges in reported metrics.

Comparing these three measures allows management to identify latent capital commitments, distinguish future portfolio obligations from legacy reserve emergence, and assess capital headroom deterioration prospectively rather than retrospectively. Steady-State Capital also provides a general insurance analogue to asset-liability management: catastrophe business resolves rapidly while casualty and liability classes require capital support over substantially longer horizons, producing materially different emergence profiles that uniform one-year measures do not capture.

The framework maintains consistency between operational expense attribution, operational risk capital and long-term capital commitment, as all three derive from the same underlying contractual and operational measurement framework.

---

# 11. Conclusions

## 11.1 Summary of Findings

## 11.2 Practical Benefits

## 11.3 Limitations

## 11.4 Future Research
