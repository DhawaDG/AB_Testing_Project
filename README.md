# 🎯 A/B Testing – Controlled Experiments for Data-Driven Decisions

This section of my portfolio is a hands-on application of the concepts from *Trustworthy Online Controlled Experiments* by Kohavi, Tang, and Xu. It showcases how I apply rigorous experimentation practices to solve business problems, optimize product decisions, and drive user engagement using statistically sound methods.

---

## 🧪 Key Concepts Covered

- Designing control vs treatment experiments with business goals in mind
- Implementing z-tests, t-tests, and proportion tests
- Calculating p-values, confidence intervals, and effect sizes
- Understanding sequential testing, multiple comparisons, and randomization
- Applying CUPED, stratification, and power analysis
- Validating system trustworthiness with A/A tests
- Exploring Bayesian methods and multi-armed bandits
- Handling leakage, interference, and long-term effects

---

## 📁 Projects Overview 

| SN | Project Title                                                                 |
|----|--------------------------------------------------------------------------------|
| 1  | [ Email Newsletter Signup Optimization](https://github.com/DhawaDG/Email-Newsletter-Signup-Optimization)                          |
| 2  | [ Mobile App Install Button Optimization](https://github.com/DhawaDG/Mobile-App-Install-Button-Test)                          |
| 3  | [ E-commerce Average Order Value (AOV) Comparison](https://github.com/DhawaDG/-E-commerce-Average-Order-Value-AOV-Comparison)                          |


---

## 📚 Book Chapter-to-Project Mapping **[PDF](https://github.com/DhawaDG/AB_Testing_Project/blob/main/fullupdatedABproject.pdf)**

| Book Chapter / Concept                          | Description                                      | Project Numbers           |
|--------------------------------------------------|--------------------------------------------------|---------------------------|
| **Part I: Introductory Topics for Everyone**     |                                                  |                           |
| Introduction & Motivation                        | Business impact measurement                      | 1, 3, 9, 15, 16, 22       |
| Running & Analyzing Experiments                  | Basic A/B test execution                         | 1, 2, 3, 4, 5             |
| Twyman’s Law & Trustworthiness                   | Bias detection, result skepticism                | 9, 17, 18                 |
| Experimentation Platform                         | Infrastructure, culture, and process             | 16, 17, 18, 22            |
| **Part II: Selected Topics for Everyone**        |                                                  |                           |
| Speed Matters                                     | Sequential testing & early stopping              | 10, 13, 17                |
| Organizational Metrics                           | KPI selection, guardrails                        | 8, 18, 20, 22             |
| Institutional Memory                             | Documentation and knowledge retention            | 17, 18                    |
| **Part III: Complementary Techniques**           |                                                  |                           |
| Observational/Quasi-Experiments                  | Natural & retrospective experiments              | 15, 16                    |
| **Part IV: Experimentation Platform Topics**     |                                                  |                           |
| Randomization                                     | Proper control/treatment setup                   | All projects              |
| A/A Testing                                       | Platform/system validation                       | 17, 18                    |
| Leakage & Interference                           | Handling network effects                         | 14, 19, 20                |
| **Part V: Analyzing Experiments**                |                                                  |                           |
| Statistical Test Selection                        | Appropriate test choice                          | All projects              |
| Multiple Testing & Corrections                   | Family-wise error rate, FDR                      | 6, 7, 19, 21              |
| Statistical Power                                | Power analysis, sample size estimation           | 2, 7, 10, 11              |
| Variance Reduction                               | CUPED, stratification                            | 11, 12, 15                |
| Heterogeneous Treatment Effects                  | Subgroup differences                             | 12, 20, 21                |
| Long-Term Treatment Effects                      | Measuring sustained impact                       | 16, 22                    |
| **Other Advanced Topics**                        |                                                  |                           |
| Bayesian Methods                                 | Posterior inference & credible intervals         | 13, 14                    |
| Multi-Armed Bandits                              | Adaptive experimentation                         | 14                        |
| Quasi-Experiments                                | Natural experiments                              | 15, 16                    |

---

## 📓  Handwritten Notes PDF

A collection of my detailed handwritten notes and summaries on these topics is available in PDF format.

- 📄 [Handwritten Notes on A/B Testing Concepts](#)

> **Note on Viewing PDFs on GitHub:**  
> If you encounter an "***Unable to render code block***" or preview error when opening a **📄 View PDF on GitHub** link, please reload the page or use the **⬇️ Download PDF** link right below it.

### Introduction and Motivation:

| Topics Covered | Page |
| :--- | :--- |
| Online Controlled Experiments Terminology & Core Vocabulary: Scientific experiment definition, Control (A) vs. Treatment (B) groups, analogies, and random assignment math concepts | `page 1` |
| Treatment Effects, Randomization & Unit of Randomization/Analysis: Treatment effect formulas, coin toss analogy, unit of analysis (user, session, cookie), and confounding risk | `page 2` |
| Metrics, Significance & Power: Invariant vs. evaluation metrics, null hypothesis ($H_0$), $Z$-score formula, statistical power, sample size requirements, and lift formula | `page 3` |
| Variance, Standard Error & P-Value Misinterpretations: Variance vs. standard error, confidence intervals, and common missteps in interpreting p-values | `page 4` |
| Why Experiment? Correlation, Causality & Observational Limitations: Why observational data can mislead, correlation vs. causation, and confounding variables | `page 5` |
| Controlled Experiments vs. Medicine Trials: Medical headache trial setup, placebo vs. active treatment, and mapping medical trials directly to web A/B testing | `page 6–7` |
| Observational Study Biases & Limitations: Selection bias, self-selection bias, survivorship bias, seasonality, and why regression/propensity matching falls short of experiments | `page 7–9` |
| Head-to-Head Comparison Table: Controlled Experiments vs. Observational Studies across assignment, bias, causality, confounding, and reliability | `page 9–10` |
| Why Randomization Equals Trust: Definition of randomization, button color test example, and why non-randomized tests fail | `page 10–12` |
| Randomization as the Gold Standard: Applications in medicine, public policy, and tech for trustworthy causal inference | `page 13` |
| Causality, Real-World Analogies & Trustworthiness: Online note-taking analogy, trustworthiness criteria, and essential ingredients for controlled experiments | `page 14–16` |
| Tenets of Experimentation & Iterative Improvement: Guiding rules (trust data, speed matters, pre-defined metrics), compound effect of small wins, and feedback loops | `page 17–18` |
| Strategy vs. Tactics & Overall Evaluation Criterion (OEC): Strategic goals vs. tactical experiments, Mount Everest analogy, OEC definition, and cumulative lift math ($\sum \Delta_i$) | `page 18–19` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/AB_Testing_Project/blob/main/ab_1_.Introduction_and_Motivation_merged_wm.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/AB_Testing_Project/raw/refs/heads/main/ab_1_.Introduction_and_Motivation_merged_wm.pdf)

### Twyman’s Law and Experimentation Trustworthiness 
| Topics Covered | Page |
| :--- | :--- |
| Twyman's Law & Experimentation Trustworthiness: Introduction to misinterpretation of statistical results in A/B testing | `page 1` |
| Confidence Intervals (CI) in A/B Testing: Simple explanation, factory ruler analogy, math concept for proportions, and Python code visualization | `page 2–4` |
| Useful Tricks & Comparison to P-Values: Interpreting CIs, width vs. precision, and how CIs compare to p-values | `page 5` |
| Threats to Internal Validity: Definition, bad lighting in an eye test analogy, and common threats table (Instrumentation, Selection Bias, History, Maturity, Leakage, Implementation Bugs) | `page 6–7` |
| Python Analogy & Simulation of Internal Threats: Simulating biased assignment and checking results | `page 8–9` |
| Segment Differences & Simpson's Paradox Introduction: Fast food experiment analogy (McDonald's spicy burger), why segment analysis matters, and Python simulation of segment masking | `page 10–12` |
| Threats to External Validity: Internal vs. external validity comparison, common threats table (Time bias, User bias, Geographic bias, Device bias, Scale-up failure), and Python generalization analogy | `page 13–16` |
| Simpson's Paradox Deep Dive: College admissions bias example, how trends reverse when groups combine, and Python simulation of Simpson's paradox in A/B testing | `page 17–20` |
| Healthy Skepticism & Twyman's Law: Definition ("Any figure that looking interesting or different is usually wrong"), miracle drug analogy, examples where skepticism saves you, and Python surprise lift simulation | `page 21–24` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/AB_Testing_Project/blob/main/ab_3_Twyman_Law_and_Experimentation_Trustworthiness_wm.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/AB_Testing_Project/raw/refs/heads/main/ab_3_Twyman_Law_and_Experimentation_Trustworthiness_wm.pdf)

### Experimentation Platform and Culture

| Topics Covered | Page |
| :--- | :--- |
| Experimentation Maturity Models & Goals: Definition, framework goals (designing, implementing, analyzing, and trusting tests), and maturity journey analogy | `page 1` |
| Maturity Levels Breakdown: Level 1 (Manual Testing), Level 2 (Basic Infrastructure), Level 3 (Centralized Platform), Level 4 (Self-Service Scalable Platform), Level 5 (Experimentation-Driven Culture), and the math/trust shift behind maturity levels | `page 1–4` |
| Real-World Analogy in Code & Summary Table: Python simulation concept (manual vs. mature tests), maturity level comparison table (Level 1, 3, 5), and final thoughts on trust ladders | `page 4–5` |
| Infrastructure & Tools Overview: Technical systems definition, why infrastructure matters (plumbing analogy), avoiding leaky pipes/dirty data, and core components intro | `page 5–6` |
| Core Component 1 — Experimentation Service (Randomization Engine): Randomization function, determinism via user ID seeds, code implementation, and consequences of randomization failure | `page 6–7` |
| Core Component 2 — Exposure Logging (Telemetry): Definition of exposure logging, cinema test screening analogy (analyzing exposed vs. assigned users), and Python code snippet | `page 7–8` |
| Core Component 3 — Metric Definition Layer: Standardized metrics definition, code snippet, and reducing ambiguity/cherry-picking | `page 7–8` |
| Core Component 4 — Guardrails, Diagnostics & Dashboards: Automatic SRM checks (`check_srm` code snippet), visual dashboards (Airbnb XP, Netflix XP, Uber's Experimentation Platform, Microsoft Exp), and reporting features | `page 9–10` |
| Why Infrastructure Matters & Interlinked Topics Summary Table: "Garbage In, Garbage Out" concept, interlinked topics (SRM, Internal Validity, CIs, Maturity), and final layer risk breakdown table | `page 10–11` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/AB_Testing_Project/blob/main/ab_4_Experimentation_Platform_and_Culture_wm.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/AB_Testing_Project/raw/refs/heads/main/ab_4_Experimentation_Platform_and_Culture_wm.pdf)


### Speed Matters: An End-to-End Case Study 

| Topics Covered | Page |
| :--- | :--- |
| Local Linear Approximation (LLA) in A/B Testing: Definition, mathematical foundations (first-order Taylor approximation $f(x+\Delta x) \approx f(x) + f'(x)\cdot \Delta x$), derivative slope calculation example, step-by-step math, and true value comparison | `page 1–3` |
| Local Linear Approximation Real-World Analogy & Insights: Sound volume app analogy, extrapolating small load time drops ($100\text{ms} \to 120\text{ms}$), smooth curve assumptions, and interlink with sensitivity analysis and extreme results | `page 4–6` |
| Measuring Website Performance: Server-side vs. page load vs. above-the-fold vs. First Contentful Paint (FCP) vs. Time to Interactive (TTI), per-user load times, and real user data tracking | `page 6–9` |
| Percentiles vs. Averages in Skewed Distributions: Why mean load times are misleading due to outliers, median ($50^{\text{th}}$ percentile), $95^{\text{th}}$ percentile worst-case views, and restaurant service time analogy | `page 7–10` |
| Slowdown Experiment Design: Deliberately injecting latency ($+100\text{ms}, +250\text{ms}, +500\text{ms}$), industry benchmarks (Amazon, Bing, Google slowdown tests), 7-step design procedure (OEC, latency tiers, user-level randomization, guardrail monitoring, fitting slopes), and ankle weights analogy | `page 11–13` |
| Local Linear Approximation vs. Extreme Results: Detailed comparison table across definitions, formulas, assumptions, models, tipping points, and dangers of misuse | `page 13–14` |
| Underlying Mathematical Frameworks: Mathematical tools, formulas, and visual analogies comparing symbolic derivatives, LLA (least squares linear regression), and non-linear extreme results (quadratic splines) | `page 14–17` |
| Step-by-Step Mathematical Worked Examples: LLA math using 3 small-delay tiers ($0\text{ms}, 100\text{ms}, 250\text{ms}$), Python code snippets (`np.cov`), quadratic matrix setup ($X^T X \beta = X^T y$) for large delays ($500\text{ms}, 1000\text{ms}$), and demonstrating LLA failure at $1000\text{ms}$ | `page 17–20` |
| Impact of Different Page Elements (Component-Level Slowdowns): Component sensitivity breakdown (HTML shell, Hero images, Ads, Below-the-fold images), multiple linear regression formulation ($M = a + \sum b_j \Delta t_j$), worked dataset solving for component slopes ($b_1, b_2, b_3$), news site dinner plate analogy, and summary takeaways | `page 21–27` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/AB_Testing_Project/blob/main/ab_5_Speed_Matters_wm.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/AB_Testing_Project/raw/refs/heads/main/ab_5_Speed_Matters_wm.pdf)

### Organizational Metrics

| Topics Covered | Page |
| :--- | :--- |
| Metric Taxonomy: Categorizing metrics into Goal (North Star/OEC), Driver (Leading Indicators), Guardrail, and Diagnostic Metrics; mathematical links (multiplicative models, regression); and the Metric Tree analogy | `page 1–4` |
| Formulating Metrics: 8 core principles (Alignment, Sensitivity, Directionality, Unit Consistency, Variance Control, Resistance to Gaming, Explainability, Timeliness); 6 techniques (Ratio metrics, per-user averaging, CUPED, Winsorization, Log transform, Event funnels); Coffee-shop analogy; and Food Delivery App case study with end-to-end math workflow | `page 4–12` |
| Evaluating Metrics: Criteria for evaluating candidate metrics (Alignment, Sensitivity/Power, Robustness, Interpretability); Car Dashboard & Thermometer analogies; core mathematical equation ($\Delta M = \alpha \cdot \Delta G + \epsilon$); formulas for Pearson correlation, Variance, MDE, Bias, Noise Ratio, and Relative Efficiency; step-by-step case study evaluating CTR vs. ATC metrics; and a 5-step real-world evaluation workflow | `page 12–23` |
| Evolving Metrics: Why metrics drift over time due to UI/product shifts, user behavior, or better data access; mathematical model of metric drift; the 3-step loop (Monitor, Diagnose, Reformulate); comparing old vs. new metric performance; and thermometer recalibration analogy | `page 24–29` |
| Sidebar — Guardrail Metrics: Definition, role in protecting user experience/trust, highway car analogy, and application examples across domains; 4 rules of good guardrails (Bounded, Fast to Measure, Hard to Game, Critical); two-hypothesis testing decision framework; step-by-step homepage A/B test worked example; and Two-Sample $Z$-test statistical violation checks ($Z$-score calculation) | `page 30–41` |
| Sidebar — Gameability: Definition of metric manipulation vs. real user value; school grading analogy; spammy button/CTR vs. downstream purchase conversion example; and principles of hard-to-game metrics | `page 41–44` |


### Metrics for Experimentation and the Overall Evaluation Criterion

| Topics Covered | Page |
| :--- | :--- |
| From Business Metrics to Metrics Appropriate for Experimentation: Why raw business metrics (total revenue, quarterly profit, NPS) fail in short-term A/B tests due to slow timelines and high variance/noise | `page 1` |
| What Makes a Metric Good for Experimentation & Coffee Shop Analogy: Key properties (sensitive, timely, directional, low variance, hard to game) and testing soup while cooking analogy | `page 2` |
| The Math Behind the Transformation: Variance reduction vs. adding users/days, and comparing statistical power between revenue and conversion rate metrics | `page 3` |
| Estimating Treatment Effect & Confidence Intervals: Formulas for treatment effect ($\Delta$), standard error ($SE$), and $95\%$ confidence intervals | `page 4` |
| A/B Test Variance Determines Success: Mathematical deep dive comparing binary conversion rate against high-variance revenue per user | `page 5` |
| The Variance-Power Relationship & Why High-Variance Metrics Fail: The impact of power users/whales, skewed distributions, and unbounded variance | `page 6` |
| Practical Metric Selection Strategy & Variance Reduction Techniques: Low-variance vs. high-variance metrics, ratio metrics, log transformations, Winsorization, trimming, stratification, and CUPED | `page 7–8` |
| Power Analysis Formula & Examples: Preventing underpowered/overpowered tests, parameter breakdown ($Z_{\alpha/2}, Z_\beta, \sigma^2, \Delta$), and sample size calculations for conversion vs. revenue | `page 9–10` |
| Summary Lessons & Business-to-Experiment Conversion Table: Low-variance recommendations, takeaway formulas, and mapping raw business metrics to experiment-ready proxies | `page 11–12` |
| Combining Key Metrics into an Overall Evaluation Criterion (OEC): Why OECs are needed to resolve conflicting metrics, weighted formula, and School GPA analogy | `page 13` |
| Making Decisions with an OEC: Resolving manager debates and making single, pre-defined, trusted decisions | `page 14` |
| Case Study — OEC for Email at Amazon: Solving the spam/unsubscribe problem by integrating lifetime value loss penalties ($L$) into the OEC formula | `page 15–17` |
| Case Study — OEC for Bing's Search Engine: Balancing user satisfaction (success rate) with ad revenue to protect long-term user trust | `page 18–19` |
| Goodhart's Law: Definition ("When a measure becomes a target, it ceases to be a good measure"), time spent on page proxy example, and math-based correlation drop analysis | `page 20–21` |
| Campbell's Law: Definition, high-stakes metric corruption, broken retention filtering example, school test scores analogy, and defense strategies | `page 22–24` |
| The Lucas Critique: Definition ("You can't reliably use historical models to predict the effect of a policy change"), streaming platform ad increase example, math formulas, and A/B testing overlap | `page 25–26` |


###  Institutional Memory and Meta-Analysis

| Topics Covered | Page |
| :--- | :--- |
| Institutional Memory Definition & Real-World Analogy: Definition of collective knowledge from past A/B tests and the hospital/doctor decision-making analogy | `page 1` |
| Math Behind Institutional Memory (Bayesian Statistics): Treating past experiment knowledge as Bayesian priors, likelihood, and posteriors to reduce noise and overreaction | `page 2` |
| Institutional Memory Tools & Connections: Overview of internal platform tools (Airbnb XP, Netflix Meta Flow), meta-analysis, Goodhart's law, and experimentation culture | `page 2–3` |
| Why Institutional Memory is Useful & Overlapping Topics: Avoiding repeated failures, speeding up decisions, jigsaw puzzle analogy, Bayesian A/B testing, and boosting statistical power | `page 3` |


###  Ethics in Controlled Experiment

| Topics Covered | Page |
| :--- | :--- |
| Data Collation Overview & Importance: Definition of data collation (instrumentation, transport, and governance), why accurate logging is vital for scientific validity, and its ethical criticality regarding user fairness, privacy, and organizational integrity | `page 1` |
| Coffee Shop Loyalty Card Experiment Analogy: Real-world example demonstrating how a data logging bug (failing to log $40\%$ of successful purchases in the treatment group) flips a true positive uplift ($+2\%$) into a false negative conclusion ($-2.8\%$) | `page 2` |
| Mathematical View of Logging Bias & Checklist: Formalization of observed lift versus true lift showing how bad logging introduces systematic downward bias, followed by a simple reliability checklist | `page 2–3` |
| Culture and Processes in Experimentation: Defining shared beliefs and repeatable processes, comparing robust engineering workflows (design docs, peer review boards, live guardrails, post-mortems) against ad-hoc operations, and simulation results | `page 3` |
| User Identifiers (Sidebar): Why stable user IDs matter to ensure independence and prevent cross-bucket contamination, and a breakdown of common identifier types (cookies, login IDs, device IDs, hashed composite emails) | `page 3–4` |
| User-Level vs. Session-Level Bucketing & Mathematical Contamination: Comparing clean user-level bucketing with flawed session-level bucketing, the mathematical impact of cross-bucket contamination ($\Delta_{\text{obs}} = (1-c)\cdot \Delta$), and summary ID guidelines | `page 4` |


###   Complementary Techniques 

| Topics Covered | Page |
| :--- | :--- |
| The Space of Complementary Techniques: Definition of complementary methods (logs analysis, human evaluation, UER, focus groups, surveys, external data), balanced meal analogy, vector spaces, dot products, orthogonality, cosine similarity, and Gram matrices | `page 1–7` |
| Logs-Based Analysis: Mining client logs, sessionization workflow with timeout parameters ($T$), defining session-level metrics (CTR, time-to-first-byte), cohort stratification ($Z_u$), two-sample $Z$-test for cohorts, and anomaly detection using Exponentially Weighted Moving Average (EWMA) | `page 7–18` |
| Human Evaluations: Qualitative scoring by judges/experts (relevance, fluency, aesthetics), latent variable models, and inter-rater agreement metrics (Cohen's kappa $\kappa$) | `page 18–20` |
| User Experience Research (UER) & Focus Groups: Qualitative insights, depth over breadth, small sample sizes, focus group discussions, exploratory data analysis (EDA), and latent variable discovery | `page 20–25` |
| Surveys & External Data: Structured questionnaires, ordinal scales, Likert responses, tracking outlier/tail performance, and quantitative tail analysis via quantiles | `page 25–29` |
| Putting It All Together (Multi-Method Data Fusion): Combining complementary techniques, ensemble learning, Principal Component Analysis (PCA), Bayesian inference, multi-model data fusion, covariance/redundancy analysis, and decision theory with utility functions | `page 29–35` |

###  Observational Causal Studies

| Topics Covered | Page |
| :--- | :--- |
| When Controlled Experiments Are Not Possible: Why randomized experiments are the gold standard but sometimes unfeasible due to ethical, technical, low sample size, one-time events, or cost constraints; real-world medical/smoking analogy | `page 1–2` |
| Counterfactuals & Average Treatment Effect (ATE): Definition of counterfactuals ($Y_i(1) - Y_i(0)$), the fundamental problem of causal inference, Average Treatment Effect (ATE), unconfoundedness, and the back-door criterion | `page 3–5` |
| Design for Observational Causal Studies: Methods to mimic randomized experiments using observational data, including matching, stratification/subclassification, and regression adjustment | `page 6–10` |
| Propensity Score Matching (PSM): Definition of propensity score ($e(X)$), calculating scores via logistic regression, matching techniques (nearest neighbor, caliper), and comparison with regression adjustment | `page 11–15` |
| Confounding & Difference-in-Differences (DiD): Definition of confounding variables and causal graphs; Difference-in-Differences (DiD) design to isolate true treatment effects from natural time trends using the parallel trends assumption | `page 16–18` |
| Human Evaluation & Inter-Rater Reliability: Using judges/experts for qualitative scoring, Cohen's Kappa ($\kappa$) for 2 raters, Fleiss' Kappa for multiple raters, interpreting kappa values, and sample size/variance reduction ($\text{Var}(\bar{x}) = \sigma^2 / R$) | `page 19–27` |
| Advanced Human Evaluation Design: Paired design vs. unpaired $t$-tests, Gold Questions (spam detection via binomial tests), and median aggregation for robustness against outliers | `page 28–34` |
| User Experience Research (UER) & Pitfalls in Observational Studies: Defining UER and latent variables; pitfalls of observational studies (confounding, selection bias, model misspecification, over-controlling, Simpson's Paradox, no ground truth); and sidebar on famous refuted observational studies (HRT, beta-carotene antioxidants) | `page 35–39` |

###  Client-Side Experiments

| Topics Covered | Page |
| :--- | :--- |
| Differences Between Server-Side and Client-Side Experiments: Core concepts, implementation location, key differences comparison table (speed, security, measurement, randomization timing, data consistency, flexibility), and the "Chef vs. Waiter" analogy | `page 1–3` |
| Randomization Timing & Mathematical Bias: Mathematical formulation of unbiased server-side randomization versus client-side selection bias, conditioning on JavaScript execution/staying long enough not to bounce, and violations of the Rubin Causal Model | `page 3–6` |
| Core Implications for Client-Side Experiments: Detailed breakdown of testing risks including exposure bias, delayed randomization and logging gaps, instrumentation gaps (ad blockers, network delays, JS errors), inconsistent cross-device/session assignments, and treatment leakage/flickering | `page 6–10` |
| Conclusions, Best Practices & Mitigations: When to prefer server-side vs. client-side testing, high-stakes rule of thumb, mitigation techniques for client-side issues (triggered analysis, redundant logging, assignment proportion validation), and underlying missing data concepts | `page 10–13` |

###  Instrumentation

| Topics Covered | Page |
| :--- | :--- |
| Client-Side vs. Server-Side Instrumentation: Definitions, advantages and disadvantages of server-side (backend) vs. client-side (frontend JS) tracking, comparison table, restaurant analogy, and missing data mechanisms (MCAR, MAR, MNAR) | `page 1–2` |
| Processing Logs from Multiple Sources: Challenges in large-scale A/B testing systems combining client, server, and third-party logs; key challenges including time skew, ID stitching across different identifiers, event duplication/loss, and relational/probabilistic join foundations | `page 2–3` |
| Culture of Instrumentation: Organizational mindset where tracking and measurement are built by default, smart factory analogy, why instrumentation is critical for experimentation, mathematical function mappings, and key takeaways | `page 3–4` |

###  Choosing a Randomization Unit 

| Topics Covered | Page |
| :--- | :--- |
| Randomization Unit vs. Analysis Unit: Definitions, restaurant experiment analogy (branches vs. customers), and the student lunch program example illustrating group-level vs. individual-level mismatches | `page 1` |
| Violation of Independence & Clustered Standard Errors: Why grouping at the cluster level (schools) while analyzing at the student level violates independent observations, leads to intra-cluster correlation (ICC), underestimates standard errors, and requires clustered standard errors | `page 2–3` |
| Randomization & Analysis Summary Table: Summary of mismatch risks, clustering adjustments, and interlocking experiment design topics | `page 3–4` |
| User-Level Randomization: Definition, grocery store loyalty cards analogy, advantages (consistency, cleaner metrics, session stitching), challenges (unauthenticated users, multi-device tracking, shared IPs), and implementation summary | `page 5–8` |

###   Ramping Experiment Exposure: Trading Off Speed,Quality, and Risk

| Topics Covered | Page |
| :--- | :--- |
| Ramping Experiment Exposure & Quality/Risk Trade-off: Balancing speed, data quality, and business/user risk when ramping A/B test exposure ($1\% \to 10\% \to 50\% \to 100\%$), medical trial analogy, and decomposing risk ($\text{Probability} \times \text{Magnitude}$) | `page 1–2` |
| What is Ramping?: Definition of gradual exposure, restaurant dish rollout analogy, expected cumulative harm function, and how statistical power improves as sample size increases during a ramp | `page 3–4` |
| SQR Ramping Framework (Speed, Quality, Risk): Framework definition, mobile phone launch analogy, component interactions (triangle model), and mathematical risk modeling | `page 4–5` |
| Four Ramp Phases: Structured deployment phases including Pre-launch check / smoke test, Safe ramp-up ($1\%–10\%$), Data ramp ($25\%–50\%$), Final (90/No-Go) rollout, risk vs. exposure curves, and summary table | `page 6–7` |
| Post-Final Ramp: Monitoring after $100\%$ rollout, regression to the mean, delayed impact detection (churn, LTV, long-lagged metrics), operational readiness, and summary | `page 7–8` |

###  Scaling Experiment Analyses

| Topics Covered | Page |
| :--- | :--- |
| Data Processing: Definition of raw log cleaning, parsing, filtering, and aggregation by unit of analysis; pizza shop analogy; ETL (Extract, Transform, Load) pipeline steps; and underlying math for aggregation over randomized units | `page 1–2` |
| Data Computation: Definition of computing experiment metrics, deltas, standard errors, confidence intervals, p-values, and guardrail metrics from processed logs; mathematical foundation with a worked numerical example | `page 3–5` |
| Results Summary and Visualization: Communicating experiment outcomes through tabular summaries and visual representations (bar plots with error bars, time-series plots, lift charts); mapping error bars to standard errors and confidence intervals ($\pm 1.96 \times SE$); and summary table | `page 5–8` |

###  The Statistics behind Online Controlled Experiments 

| Topics Covered | Page |
| :--- | :--- |
| Type I/II Errors & Statistical Power: Definitions ($\alpha, \beta, 1-\beta$), airport security metal detector analogy, step-by-step hypothesis test setup, $Z$-table critical value computation, and key drivers of power | `page 1–5` |
| Bias in Experiments: Definition of estimator bias ($\text{Bias}(\hat{\Delta}) = E[\hat{\Delta}] - \Delta$), miscalibrated kitchen scale analogy, selection bias example, and mitigation techniques | `page 6–7` |
| Multiple Testing & Corrections: Family-Wise Error Rate (FWER) formula ($1 - (1-\alpha)^m$), Bonferroni correction proof and worked math example, Benjamini-Hochberg False Discovery Rate (FDR) procedure with step-by-step worked table | `page 8–17` |
| Fisher's Meta-Analysis: Definition, formula $\chi^2 = -2 \sum \ln(p_i)$, jury deliberation analogy, and step-by-step worked math example combining independent $p$-values across platforms | `page 18–21` |
| Chi-Square Tests ($\chi^2$): Pearson residuals and expected counts, Example 1: Goodness-of-fit test (die fairness), Example 2: Test of independence (gender vs. handedness), Resampling/Permutation-based $\chi^2$ test, and Theoretical $2 \times 3$ contingency table test | `page 22–31` |
| Fisher's Exact Test: Hypergeometric distribution formula, fixed margins concept, step-by-step enumeration of possible $2 \times 2$ tables, two-tailed $p$-value derivation, and scientific fraud detection application | `page 32–41` |

###  Variance Estimation and Improved Sensitivity: Pitfalls and Solutions 

| Topics Covered | Page |
| :--- | :--- |
| Common Pitfalls in Variance Estimation: Overview of common mistakes in A/B testing variance estimation | `page 1` |
| Pitfall 1 — Raw CTR Variance vs. Per-User Metrics: Why raw Click-Through Rate ($\text{total clicks}/\text{total impressions}$) hides user-level variability, uniform (Site A) vs. skewed (Site B) behavior comparison, and mathematical breakdown | `page 1–4` |
| Pitfall 2 — Correlation Within Units (Sessions vs. Users): Failing to account for intra-user correlation across sessions, e-commerce "Buy Now" button experiment example, "What is a session?" definition, and step-by-step worked math comparing session-level (naive) vs. user-level (correct) aggregation | `page 4–10` |
| Pitfall 3 — Using Wrong Unit of Analysis & Impressions: Unit mismatch bias, "What is an impression?" definition, impression-level vs. user-level analysis in ad testing, and summary guidelines | `page 10–13` |
| Pitfall 4 — Overfitting to Variance Reduction Techniques: Risks of overly aggressive covariate adjustment or tuning after observing outcomes, worked numerical example showing pre-planned vs. overfitted adjustments, and data leakage risks | `page 13–17` |
| Improving Sensitivity: Methods to boost statistical power by reducing variance (CUPED / Covariate Adjustment, Triggering, Bucketing/Stratification), mathematical formula for adjusted variance $\text{Var}(Y_i^{\text{adj}}) = \sigma_y^2 (1 - R^2)$, and key takeaways | `page 18–20` |
| Variance of Other Statistics — The Delta Method: Estimating variance for non-average metrics (ratios, rates, percentiles), step-by-step Delta Method derivation for CTR ($R = Y/X$), and a hand-calculated worked example with 4 users | `page 21–25` |
| Ratio of Averages vs. Average of Ratios: Comparing Normalized CTR ($\sum Y_i / \sum X_i$) against Naive Per-User CTR ($\frac{1}{n} \sum \frac{Y_i}{X_i}$), Influencer vs. Regular User real-world example, and avoiding Simpson's Paradox | `page 25–28` |
| Weighted Averages with Correlation Adjustment (UMVUE): Optimal variance weighting formula ($w_i \propto \frac{n_i}{1 + (n_i - 1)\rho}$), defining intra-user correlation ($\rho$), step-by-step worked math across 3 users, and comparing Naive vs. UMVUE weighted averages | `page 28–32` |

### The A/A Test 

| Topics Covered | Page |
| :--- | :--- |
| Why A/A Tests?: Definition of an A/A test (splitting traffic without a treatment), system validation vs. feature validation, laboratory scale calibration analogy, Type I error ($\alpha$) estimation, and doctor thermometer analogy | `page 1–3` |
| How to Run A/A Tests (Core Principles): 5 key principles (random user splitting, production scale execution, running multiple tests to check Type I error rate, testing across key metrics, checking statistical properties/ ($p$)-value uniform distributions), digital scale lab analogy, and summary table | `page 3–5` |
| What Does it Mean When an A/A Test Fails?: Definition of A/A failure, 5 main failure scenarios (inflated Type I error rate, inconsistent/biased randomization, instrumentation/logging bugs, time-based/temporal bias, cross-bucket contamination), faulty thermometer analogy, summary table of common A/A failures, and debugging steps | `page 6–9` |

###  Triggering for Improved Sensitivity 

| Topics Covered | Page |
| :--- | :--- |
| Examples of Triggering & Why Use Triggering: Definition of triggering (measuring only relevant users), real-world examples (search engine, ad click, shopping cart, video watch), connection to statistical power, and simple mathematical derivation of standard error ($SE = \frac{\sigma}{\sqrt{pN}}$) | `page 1–5` |
| Numerical Example (Kohavi, Longbotham et al. 2009): Demonstrating how un-triggered users dilute treatment effects ($+0.2\text{s}$ search effect becoming $+0.08\text{s}$ overall), Bing search engine simulation, global vs. triggered analysis comparison, and mathematical breakdown | `page 6–10` |
| Optimal vs. Conservative Triggering: Trade-off between maximizing statistical power (optimal style) and avoiding bias/keeping tests trustworthy (conservative style using pre-treatment criteria), and statistical $Z$-score formulation | `page 11–13` |
| Overall Treatment Effect: Mathematical formula for global business impact ($\text{Overall Effect} = p \cdot \Delta_T + (1-p) \cdot \Delta_N$), discount coupon example, key underlying assumptions, and summary | `page 14–16` |
| Trustworthy Triggering: The non-negotiable core principle that triggering must be strictly independent of treatment, search layout analogy (Case A vs. Case B), user relationship rules, and consequences of violation | `page 17–21` |
| Common Pitfalls, Root Causes & Fixes: Detailed breakdown of 4 major mistakes (treatment-dependent triggering, post-treatment behavior, misinterpreting overall effect, differential triggering rates), pre- vs. post-treatment comparison table, and best practices table | `page 22–26` |

### Sample Ratio Mismatch and Other Trust-Related Guardrail Metrics

| Topics Covered | Page |
| :--- | :--- |
| Sample Ratio Mismatch (SRM) & Trust-Related Guardrail Metrics: Definition of SRM, fair coin flip analogy, Chi-Square goodness-of-fit test for SRMs ($\chi^2 = \frac{(O_A - E_A)^2}{E_A} + \frac{(O_B - E_B)^2}{E_B}$), why SRM breaks statistical trust, and main root causes | `page 1–3` |
| Debugging SRMs & Relationship with Guardrail Metrics: Root cause analysis (assignment code bugs, bot filtering, asymmetric logging, client-side scripts, temporal ramp bugs), step-by-step debugging strategy, guardrail metrics vs. SRM comparison table, and McDonald's diet assignment analogy | `page 4–7` |
| Leakage and Interference Between Variants: Definition of leakage and interference; Example 1: Shared computers/cookie-level tracking with McDonald's menu display board analogy; mathematical formulation of SUTVA violations and treatment effect dilution ($\hat{Y}_A = \alpha Y_A + (1-\alpha)Y_B$) | `page 7–10` |
| Interference Examples (Social Networks, Cross-Device, Search, Inventory): Example 2: Social networks/Facebook News Feed (dance floor music analogy); Example 3: Cross-device usage; Example 4: Search engine ranking feedback loops; Example 5: Inventory/warehouse capacity constraints; leakage vs. interference summary table | `page 10–13` |
| Practical Solutions for Leakage & Interference: 6 mitigation techniques: stable randomization units (User ID), cluster randomization (classrooms/SUTVA preservation), geo-experiments/market-level randomization, client-side caching/sticky assignments, holdouts/shadow testing, and post-experiment data filtering | `page 14–17` |
| Detecting and Monitoring Interference: 5 detection strategies: non-linear metric curves across treatment percentages (perfume room analogy), tracking control group performance over time (express checkout lanes analogy), network graph analysis ($N(u)$), monitoring SRM, and cross-device/multi-touch attribution mismatch | `page 18–22` |
| Measuring Long-Term Treatment Effects: Short-term vs. long-term treatment effects, gym membership analogy, mathematical definition of short-term vs. steady-state long-term effects ($\lim_{n \to \infty} T(n)$), and a step-by-step worked math example | `page 22–26` |
| Reasons Treatment Effects Differ Between Short-Term & Long-Term: 6 core mechanisms: User learning curve ($T(n) = a(1 - e^{-bn})$), Novelty effect decay ($T(n) = a e^{-bn}$), Network effects/peer influence, Habit formation (sigmoid adoption curves), Delayed downstream metrics, and Churn/retention selectivity | `page 26–30` |
| Long-Running Experiments & Survivor Bias Math: Why long-running A/B tests are used, core operational challenges (variant leakage, churn, external noise), medical drug trial analogy, and a day-by-day step-by-step mathematical proof demonstrating upward survivor bias ($\hat{T}_{\text{obs}}(t) > \hat{T}_\infty$) | `page 30–35` |
| Alternative Methods for Long-Running Experiments: 4 forecasting alternatives: Early predictors/proxy metrics ($\text{Corr}(X, Y)$), Causal modeling & ML estimators (uplift modeling, causal forests, Double ML), Survival analysis/retention modeling ($S(t)$ extrapolation), and Synthetic controls/re-weighting (CUPED, PS weighting); college graduation proxy analogy; and summary table | `page 36–39` |

  
## Book References

Key resources and books that guided my learning journey:
- 📄 [Handwritten Notes on A/B Testing Concepts](#)
- 📚 *Trustworthy Online Controlled Experiments* – Ron Kohavi et al.
- 📚 *Practical Statistics for Data Scientists* – Peter Bruce et al.

---
## ⬅️⬅️ [Back to Main Profile](https://github.com/DhawaDG)

Let me know if you'd like to explore the math, code snippets, or dashboards used in each of these experiments!

