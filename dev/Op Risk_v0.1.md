# Operational Resource Attribution and Operational Risk

## A Unified Framework for IFRS 17 Expense Attribution and Operational Risk Capital in General Insurance

# Abstract

Operational expense attribution and operational risk capital are currently treated as separate problems in general insurance practice. IFRS 17 requires the systematic and rational attribution of directly attributable expenses to insurance contract groups but does not prescribe a methodology for doing so. Operational risk frameworks separately estimate capital requirements for operational failure without connecting those estimates to the operational expense base they are intended to protect. Despite both measuring consequences of the same underlying operational system, no common framework currently links them.

This paper proposes a unified operational resource framework grounded in a single first principle: an insurance contract is not only a financial obligation but also an operational obligation, requiring the consumption of resources across acquisition, maintenance, fulfilment and governance activities. These obligations are delivered through two distinct layers: an Insurance Service Layer comprising activities directly attributable to individual contract groups, and an Operational Support Layer comprising institution-level activities required to sustain service delivery across the portfolio.

Within this framework, expected resource consumption gives rise to operational expense attribution. Operational risk arises when realised resource consumption deviates from the level required to sustain the intended delivery of insurance services. The tail of that deviation distribution gives rise to operational risk capital. Operational expense attribution and operational risk capital therefore emerge from the same underlying resource measurement framework rather than from separate frameworks. As a consequence, expected operational risk equals expected operational cost, providing a consistency relationship that is absent from current practice.

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

The consequence is that as business structures become more complex — 
greater use of delegated authority, increased reliance on third-party capital, 
more sophisticated reinsurance structures — the operational risk framework 
becomes progressively less complete rather than adapting to the changing 
operational reality of the business.

A measurement framework that is genuinely useful to a general insurance 
actuary must operate consistently across the full spectrum of operational 
structures without requiring structural modification to its underlying logic.

---

## 1.4 Objectives of this Paper

This paper has four objectives.

First, to establish a first-principle basis for the attribution of operational 
expenses to insurance contract groups that satisfies the systematic and rational 
requirement of IFRS 17 and reflects the operational intensity of specific 
contracts, relationships and fulfilment activities.

Second, to derive an operational risk capital measurement from the same 
underlying resource consumption framework, ensuring consistency between the 
operational expense base and the capital charge intended to protect against 
unexpected operational losses.

Third, to demonstrate that the framework operates without structural 
modification across the principal operational structures of general insurance 
practice, including delegated underwriting, reinsurance structures, and 
third-party capital arrangements.

Fourth, to provide a practical implementation roadmap that enables a general 
insurance actuary to apply the framework progressively, beginning with existing 
cost-centre data and extending to state-based stochastic operational risk 
modelling.

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

Core principle:
An insurance contract is not only a financial obligation. It is an operational obligation.
Operational obligations require resource consumption across four categories: acquisition, maintenance, fulfilment, governance.
Expected resource consumption is not operational risk. It is the cost of running the business.
Operational risk arises when realised resource consumption deviates from the level required to sustain the intended delivery of insurance services.
Expected operational risk equals expected operational cost. This is not an assumption. It is a consequence of the first principle.

## 2.1 Insurance Contracts as Operational Obligations

## 2.2 Operational Obligations and Resource Consumption

## 2.3 Expected Resource Consumption

## 2.4 Operational Risk as Deviation from Expected Fulfilment

Operational risk arises when realised resource consumption deviates from the level required to sustain the intended delivery of insurance services.

## 2.5 Operational Risk

---

# 3. Operational Obligation Framework

## Core principle:
Every insurance contract creates obligations across all four categories simultaneously. No contract creates obligations in only one category.
Acquisition      →    Creating the relationship
Maintenance      →    Sustaining the capability
Fulfilment       →    Executing the contract
Governance       →    Preserving legitimacy
The four categories are exhaustive. Every operational activity in a general insurance entity maps to one of these four without remainder.

## Continuity Principle
Operational obligations do not extinguish
at contract expiry.

The operational relationship persists
through renewal and conditions the terms
on which the next financial obligation
is established.

Renewal is not a new operational event.
It is a continuation of an existing
operational state.

## Seasoning Principle
Operational resource consumption
declines as relationship history accumulates.

New business
→ full acquisition resource consumed
→ high information uncertainty
→ high operational risk loading

Year N renewal
→ acquisition resource approaches zero
→ information uncertainty approaches minimum
→ operational risk loading approaches minimum

The renewal discount is not a commercial concession.
It is the mathematically correct reflection
of declining operational resource consumption
across a maturing relationship.

Information Accumulation Principle
Relationship history is operational capital.

Credit checks, background verification,
submission analysis and underwriting
from prior data are not repeated
for a seasoned renewal relationship.

The insurer has already paid
for that information in prior periods.

The operational cost of pricing
a Year N renewal is therefore
structurally lower than
the operational cost of pricing
equivalent new business
independent of claims experience.

## Information Accumulation Principle
Relationship history is operational capital.

Credit checks, background verification,
submission analysis and underwriting
from prior data are not repeated
for a seasoned renewal relationship.

The insurer has already paid
for that information in prior periods.

The operational cost of pricing
a Year N renewal is therefore
structurally lower than
the operational cost of pricing
equivalent new business
independent of claims experience.

## Adverse Selection Principle

A counterparty who switches insurer
at every renewal forces full acquisition
resource consumption at every cycle.

A counterparty with long renewal history
allows operational resource to decline
to steady state minimum.

Both may carry identical claims experience.
Their operational cost profiles are not identical.
Price should reflect the difference.

## Contract Boundary Principle

Under financial obligation framing
the contract boundary resets annually.

Under operational obligation framing
the relationship state does not reset.

A ten-year renewal relationship
carries operational history
that spans multiple contract boundaries.

The IFRS 17 contract boundary
is a financial reset.
It is not an operational reset.
The CSM release profile
should reflect both.

## Shareholder and Regulatory Governance Seasoning
Governance obligations do not remain
constant across the institutional lifetime.

A new entrant carries maximum
governance resource consumption:

→ Full regulatory authorisation process
→ Full capital model validation
→ Full audit establishment
→ Full board governance build
→ Full rating agency relationship establishment
→ Maximum collateral requirements
→ Maximum supervisory intensity

A seasoned institution with
established regulatory relationship
carries minimum governance
resource consumption:

→ Incremental regulatory filing
→ Model validation at change points only
→ Established audit relationship
→ Functioning board governance
→ Established rating agency history
→ Reduced or eliminated collateral
→ Supervisory relationship in equilibrium

## The Collateral Analogy

## 3.1 Acquisition Obligations

## 3.2 Maintenance Obligations

## 3.3 Fulfilment Obligations

## 3.4 Governance Obligations

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
