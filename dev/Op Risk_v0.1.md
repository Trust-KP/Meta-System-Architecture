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

[ANCHOR: Insert practitioner evidence of attribution inconsistency — 
survey data, TRG submissions, or implementation studies showing 
divergence in current GI practice]

The consequence is that fulfilment cash flows used in the measurement of insurance contract liabilities, the identification of onerous contracts, and the determination of the contractual service margin are systematically incomplete. Contract groups whose fulfilment requires high operational intensity carry insufficient expense in their measured cost. Contract groups whose fulfilment is operationally straightforward carry excess allocation. The onerous contract test is performed on a cost base that does not reflect the true operational 
burden of each contract group.

No systematic actuarial methodology currently exists for attributing operational expenses to contract groups in a manner that reflects the operational intensity of specific relationships, business types and fulfilment activities in general insurance.

---

## 1.2 The Operational Risk Capital Disconnection

Operational risk capital in general insurance is currently estimated through 
approaches that share a common structural limitation: they measure the 
consequence of operational failure rather than the condition that produces it.

Scenario-based assessments construct hypothetical loss events and score their 
severity and frequency. Loss distribution approaches fit statistical distributions 
to historical loss data. Premium and reserve proxies apply uniform loadings 
derived from industry averages. In each case the capital charge is derived from 
observed or hypothesised loss outcomes rather than from the operational 
processes and relationships that generate those outcomes.

[ANCHOR: Insert brief literature anchors — Basel II definition, 
Solvency II SCR operational risk formula, BMA equivalents, 
LDA limitations from Frachot et al and Dutta and Perry]

Three structural limitations follow from this approach.

Current models are retrospective. The capital charge is calibrated from loss 
history that is sparse, inconsistently recorded and dominated by low-severity 
high-frequency events that bear limited relationship to the tail losses the model 
is intended to capture.

Current models are undifferentiated. The same loading is applied regardless of 
the operational quality of specific functions, the friction generated by specific 
counterparty relationships, or the direction of miscalibration. An institution 
that is operationally over-extended in one area and under-resourced in another 
carries the same capital charge as one that is uniformly well-managed.

Current models are unattributable. The capital number produced cannot be traced 
to the organisational processes, functions or relationships responsible for 
generating it. It satisfies a regulatory requirement without informing a 
management decision.

The operational risk capital charge and the operational expense base from which 
it is intended to protect are estimated independently, producing a structural 
inconsistency: the mean of the operational risk distribution is implicitly assumed 
to be zero, while the expected operational cost sits separately in the expense 
base with no formal connection to the capital model.

---

## 1.3 The Structural Invariance Problem

Current operational risk measurement approaches are not only disconnected from 
the expense base — they are structure-dependent. Different approaches are 
applied to different business types, different counterparty structures and 
different operational arrangements, without a common measurement basis across 
them.

A general insurer writing direct business, a syndicate operating through binding 
authorities, a reinsurer managing a portfolio of facultative placements, and a 
captive fronted through a carrier each face operationally distinct arrangements. 
Current frameworks treat each as requiring separate modelling assumptions, 
separate scenario libraries and separate capital loadings. The operational cost 
of a fronting arrangement, a delegated underwriting authority, an adverse 
development cover, or a sidecar structure is not systematically captured within 
any current operational risk framework.

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
operational cost — as a theorem from first principles rather than an accounting 
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

## 8.5 Adverse Development Covers

### 8.5.1 Reserve Deterioration as Prior Operational Deviation

### 8.5.2 Operational Obligations Created by ADC Structures

### 8.5.3 Monitoring and Reporting Resources

### 8.5.4 Financial Responses to Operational Deviation

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

## 10.7 Strategic Extension: Theoretical Capital and GI Balance-Sheet Emergence

The operational resource framework may be extended beyond expense attribution and operational risk capital to a broader balance-sheet emergence framework.

Under this extension, the insurer distinguishes between actual, projected and theoretical states of the portfolio. The theoretical state represents the mature steady-state position implied by the current written premium, expected loss ratio, reserve emergence pattern and capital model assumptions.

This produces theoretical premium, theoretical reserve, theoretical margin and theoretical capital.

Theoretical capital can then be compared with available capital to identify latent headroom consumption before it emerges in reported capital metrics. This provides a forward-looking traffic-light framework for capital headroom deterioration.

The same view may support a GI analogue of asset-liability management, where investment strategy is informed not only by booked reserve duration, but also by the theoretical reserve and capital support profile of the business.

The theoretical capital profile is derived from the same expected Insurance Service Layer and Operational Support Layer that gives rise to operational cost attribution, operational loss distributions and capital requirements. Consequently, the framework maintains consistency between operational expense allocation, operational risk capital, and the long-term capital commitment embedded within the written portfolio. 

Theoretical capital therefore represents the steady-state capital support implied by the current contractual and operational structure of the portfolio, while deviations emerge through the unfolding of actual experience over time.

---

# 11. Conclusions

## 11.1 Summary of Findings

## 11.2 Practical Benefits

## 11.3 Limitations

## 11.4 Future Research
