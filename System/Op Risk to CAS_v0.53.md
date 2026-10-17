# 2026 CAS Risk Call Paper Proposal — Operational Risk

**Proposed title:** When the Dashboard Turns Amber: How Operational Risk Emerges from Operational State

**Author:** Kok Pian Gew, AIA C.Act (kokpian.gew@gmail.com)

**Topic:** Operational Risk

---

## 1. Topic

A common case: before a catastrophe, the reinsurance team's dashboard is amber because experienced staff have left. After the event, claims, reinsurance and finance turn red together, and recoveries are collected in full, but only after a dispute that raises legal costs, slows subrogation and strains a broker relationship. None of this is booked as an operational loss; it is absorbed as business-as-usual noise, although it changed the result in the year it mattered most.

Operational risk capital should be sufficient, free of double counting and testable against experience, and current methods meet these tests only in part. A flat charge, or a standalone loss distribution joined to other risks by a copula, sits beside the risks it affects and gives two insurers the same charge however differently they are run. Otherwise the effect is absorbed into a wider coefficient of variation for the underlying risk, or recorded as a model limitation. Every risk enters through the operation, but not every risk is operational.

This paper proposes a modelling framework built on one principle: **no operational loading exists without a named variable in the capital model on which it acts**. As in a catastrophe model, operational loss arises where an exposure meets a condition. Operational risk rises as a team's operational state deteriorates and falls as it improves, acting as a layer of secondary uncertainty on every simulated variable, driven by the shared state as a common shock. For any variable X:

$$\tilde{X} = X \prod_i (1+k_i) + \sum_i K_i, \qquad O = \tilde{X} - X$$

Each <i>k</i><sub><i>i</i></sub> is a proportional loading from a condition <i>i</i>, and each <i>K</i><sub><i>i</i></sub> an additive cost such as a dispute or fine. O is the **operational effect** on X. Insurers already budget for it within operating expense and their claims and recovery assumptions, often with a margin, much as an IFRS 17 risk adjustment sits above best estimate; operational risk is how far the actual income statement may depart from that budget, beyond changes in volume. Operational risk is modelled as a state-dependent effect on variables already in the capital model, rather than as a separate loss distribution. When a dashboard turns amber, the model shows how unusual that state is and which variables it will reach, before any loss appears, so finance, treasury and claims can prepare in advance.

## 2. Approach

The framework needs one new field in the risk register and no new data collection. It also captures risks that registers set aside as individually immaterial, because many depend on the same team or system and move together. The framework fixes the structure, and owners choose how to apply it. The parts follow the risk control cycle of identify, quantify, mitigate and monitor.

**Part I — Identify and parameterise.** Every register entry already has an owning department, function or committee, which identifies the source of its condition. The framework adds one requirement: the owner connects each entry to the variables in the capital model that it affects, many to many. Events with no such variable, such as mergers, go to stress testing. This is no more subjective than today's scenario-based frequency-severity models, and becomes less so as state histories build up. Today's frequency-severity model is itself the entity-level sum of the additive terms <i>K</i><sub><i>i</i></sub> in this framework, so it carries over unchanged as the starting point. Past operational effects in the data used to parameterise other risks, such as claims leakage in a particular year, can be separated from insurance risk, much as a reserving actuary isolates a calendar-year effect. The method works on any capital basis, from internal economic capital and US statutory accounts to Solvency II and IFRS 17. In the example, the reinsurance team owns the dispute entry and connects it to recoveries, legal expense and claims.

**Part II — Quantify: exposure and state.** Quantification follows the structure of a catastrophe model. The capital model's simulated variables are the exposure module: each connected operational effect resolves explicitly to the underlying variables it moves, so no effect is counted twice. The operational state is the hazard module, simulated alongside the underlying risk as a dynamic Bayesian network of drivers rather than a copula. States nest from the external environment, such as the underwriting cycle, through the insurer and its departments to each team, and variables that share a team, system or function share its state. The state is read from the key risk indicators, performance measures and traffic-light ratings the insurer already reports and monitors. These act as proxies, as rating factors do in pricing, and just as pricing actuaries rebalance a portfolio when factors move, the insurer acts as its proxies move. Their monthly history calibrates how states move.

**Part III — Quantify: loading.** The loading is the vulnerability module, turning a state into an effect on a variable, such as recoveries delayed and claims increased in the years recoveries are largest. Five results follow.

1. **Separation.** Underlying risk, operational risk and parameter uncertainty become separate and visible, and operational effects now implicit in insurance risk parameters become explicit.
2. **Dependence from structure.** No copula or degrees-of-freedom assumption is needed.
3. **Compounding.** Weakness in one condition amplifies another.
4. **Mean and tail.** The budget carries the mean, and capital covers adverse deviation; a regulatory basis may floor favourable deviation at zero.
5. **Nesting.** The flat charge is a single constant loading and frequency-severity the additive case, so the same operational risk figure is reproduced exactly before any refinement.

**Part IV — Mitigate.** Improving a condition lowers the loading, the capital and the budget, putting a capital value on each control and exposing costs hidden in flat allocations; once a weakness is fixed, its relocated effect falls away. Because every tail outcome traces back to states and variables, scenarios and reverse stress tests can include operational states, and management can see how much of an extreme result is within its control and set appetite on the states it can manage. Comparing capital at the actual and the steady-state opening state shows what the current condition costs or saves, team by team.

**Part V — Monitor.** Each year the review splits the difference between the actual income statement and the budget into volume, condition and efficiency, attributes the operational part to a condition, and updates the states, the budget and the register. It tests each proxy as a pricing actuary tests a rating factor, checking whether amber and red ratings foreshadow operational effects.

**Part VI — Worked example and code.** After a short survey placing current methods within the framework, the worked example takes a synthetic multi-line property and casualty insurer's existing frequency-severity model and re-expresses it exactly within the framework. It then adapts the model step by step: refining granularity from entity to class to condition, adding state dependence, and converting additive effects to proportional loadings where evidence supports them. Each step shows the change in capital by line, gross and net. It also proposes a structure for benchmarking operating efficiency, and provides open-source Python code for the CAS GitHub repository under the MPL 2.0 licence.

## 3. Survey of Existing Literature

1. **Brehm, P. J., et al. 2007. *Enterprise Risk Analysis for Property & Liability Insurance Companies*. New York: Guy Carpenter.** Treats operational risk as a separate component of economic capital; this paper attaches it to the variables already modelled.
2. **Kelliher, P. O. J., et al. 2024. "Validating Operational Risk Models." *British Actuarial Journal* 29: e1.** Leaves boundary losses and business-as-usual costs to the validator; this paper builds both into the model and ends the causal path in an existing variable.
3. **Berquist, J. R., and R. E. Sherman. 1977. "Loss Reserve Adequacy Testing: A Comprehensive, Systematic Approach." *Proceedings of the Casualty Actuarial Society*: 123–84.** Separates operational changes in case reserving and settlement from development; this paper extends that to capital.
