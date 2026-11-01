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

> **Note on Viewing PDFs on GitHub:**  
> If you encounter an "***Unable to render code block***" or preview error when opening a **📄 View PDF on GitHub** link, please reload the page or use the **⬇️ Download PDF** link right below it.

### Introduction and Motivation:
| Topics Covered | Page |
| :--- | :--- |
| Introduction & Core Terminology: Online controlled experiments, A/B test definition, Control Group (A), Treatment Group (B), analogies, and random assignment math concepts | `page 1` |
| Treatment Effects, Randomization, and Unit of Randomization/Analysis: Defining treatment impact, eliminating bias via random assignment, and common units of analysis | `page 2` |
| Metrics & Statistical Significance: Invariant vs. evaluation metrics, Null hypothesis ($H_0$), statistical significance, $Z$-score formula, statistical power, and sample size requirements | `page 3` |
| Experiment Metrics & P-Values: Lift calculations, variance, standard error, and common pitfalls in p-value interpretation | `page 4` |
| Correlation vs. Causality: Why correlation does not equal causation, examples from app data, and defining causal relationships | `page 5` |
| Measuring Causality & Trustworthiness: Real-world study analogies, why randomized experiments are required to establish causality, and principles of trustworthy testing | `page 6` |
| Controlled Experiment Ingredients & Tenets: Essential prerequisites for running valid experiments (clear hypothesis, randomization, power, instrumentation, metrics, duration, analysis plan) and guiding tenets | `page 7` |
| Tenets & Improvement Over Time: Core experiment rules (speed matters, decentralize, evaluate long-term impact, pre-defined metrics), compound effects of iteration, and rapid feedback loops | `page 8` |
| Strategy vs. Tactics & Overall Evaluation Criterion (OEC): High-level strategy vs. tactical experiments, real-world mountain climbing analogy, Overall Evaluation Criterion (OEC), and cumulative lift formulas | `page 9` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/AB_Testing_Project/blob/main/ab_1_Introduction_and_Motivation_wm.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/AB_Testing_Project/raw/refs/heads/main/ab_1_Introduction_and_Motivation_wm.pdf)

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

