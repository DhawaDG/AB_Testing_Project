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

## Book References

Key resources and books that guided my learning journey:
- 📄 [Handwritten Notes on A/B Testing Concepts](#)
- 📚 *Trustworthy Online Controlled Experiments* – Ron Kohavi et al.
- 📚 *Practical Statistics for Data Scientists* – Peter Bruce et al.

---
## ⬅️⬅️ [Back to Main Profile](https://github.com/DhawaDG)

Let me know if you'd like to explore the math, code snippets, or dashboards used in each of these experiments!

