# The-Reframe-Problem-How-Solutions-Become-Vulnerabilities-and-How-Human-Decision-Making-Contributes

# The Reframe Problem
### How Solutions Become Vulnerabilities and What Human Decision-Making Has to Do With It

---

> *"The problem is not the incident. The problem is the thinking that made the incident invisible until it happened."*

---

## Overview

This is an ongoing independent research project sitting at the intersection of data analytics, behavioural science, and cybersecurity.

The central argument is this: organisations do not fail because they lack solutions. They fail because they keep applying the same solution to a problem that has already changed shape. The solution becomes the blind spot. Security teams patch the breach, not the behaviour that caused it. Analytics teams measure the outcome, not the decision that produced it.

Most analytical frameworks start with a problem and work toward a solution. This project challenges that direction. It asks a different question — what if the solution was the problem all along? And what if the answer is not a new solution, but a reframe?

This research does not follow the traditional path. It is built on personal perspective, independent investigation, and a commitment to understanding the human layer that most technical analysis ignores.

---

## The Research Questions

### Descriptive — What happened?
- What types of security incidents appear most frequently and what do they share at the human decision layer?
- What does normal decision-making behaviour look like in a secure environment versus a compromised one?
- Where in an organisation's workflow do the most critical human decisions about security get made?
- What patterns exist in the timing, frequency, and context of successful social engineering attacks?

### Diagnostic — Why did it happen?
- What conditions were present before the decision failure occurred?
- Why do the same solutions get reapplied to recurring problems without addressing the underlying decision pattern?
- What cognitive shortcuts are most commonly exploited in successful attacks and why are they so reliable?
- How does the framing of a choice change the decision a person makes?

### Predictive — What is likely to happen?
- Which decision points are most likely to fail under future attack conditions?
- Can a model predict when a human decision failure is about to occur based on environmental signals?
- How do attack techniques evolve in response to deployed solutions — and what does that predict about the next wave?
- Under what conditions does reframing a problem produce a fundamentally different outcome?

---

## Analytical Approach

This project uses all three layers of analytics in sequence — not independently, but as a connected process where each layer informs the next.

**Descriptive Analytics**
Establish what the data actually contains before any interpretation. Frequency distributions, timing patterns, role-based patterns in who gets compromised and when.

**Diagnostic Analytics**
Investigate causality. Cross-reference incident data with contextual variables to identify which conditions correlate with decision failure. This is where behavioural science enters the analysis.

**Predictive Analytics**
Build forward-looking models trained on historical incident features to predict the likelihood of decision failure under similar future conditions. The goal is not predicting the attack — it is predicting the human vulnerability window.

---

## Tools and Technologies

| Purpose | Tool |
|---|---|
| Data manipulation | Python, Pandas, NumPy |
| Visualisation | Matplotlib, Seaborn, Plotly |
| Statistical analysis | Scipy, Statsmodels |
| Machine learning | Scikit-learn, SHAP |
| NLP for text analysis | NLTK, spaCy |
| Notebook environment | Jupyter Notebook |
| Streaming data | Apache Kafka / Python sockets |
| Network data | tshark, Wireshark PCAP |
| Version control | GitHub |
| Presentation | Power BI / Tableau |

---

## Data

**Static Data**
Historical and fixed. Used for baseline establishment, pattern identification, and model training.
Sources include public cybersecurity datasets, Verizon DBIR breach reports, MITRE ATT&CK records, CVE database exports, and Kaggle cybersecurity datasets.
Formats: CSV, JSON, XML, Excel.

**Streaming Data**
Live and continuous. Used for real-time anomaly detection and behavioural drift monitoring.
Sources include live system logs, authentication event streams, and network packet captures.
Formats: JSON streams, syslog, PCAP.

---

## Repository Structure

```
Reframe-Problem/
├── README.md
├── research/
│   └── research_questions.md
├── data/
│   ├── raw/
│   └── cleaned/
├── notebooks/
│   ├── 01_descriptive_analysis.ipynb
│   ├── 02_diagnostic_analysis.ipynb
│   └── 03_predictive_model.ipynb
├── visuals/
└── findings/
```

---

## The Human Behaviour Layer

At every stage of this analysis, the human decision sits at the centre. The data is a record of decisions. The patterns are patterns of decision failure. The prediction is a prediction of when conditions will align to make failure likely again.

Key concepts carried throughout this research:

**Cognitive Load** — decisions made under high cognitive load rely on shortcuts that can be exploited.

**Framing Effects** — the same choice presented differently produces different decisions. Attackers understand this. Defenders rarely design for it.

**Authority Bias** — people defer to apparent authority even when something feels wrong. This is not weakness. It is a deeply embedded social heuristic.

**Normalcy Bias** — a system that has never been breached feels like a system that cannot be breached. That feeling is the vulnerability.

**Level-Based Decision Making** — the decisions a junior analyst, a mid-level manager, and an executive make about the same security event are structurally different. Not just in authority but in the information available, the pressure applied, and the consequences perceived.

---

## Analysis Process

| Stage | Focus |
|---|---|
| Ask | Define the questions before touching any data |
| Investigate | Survey what data exists and what its limitations are |
| Prepare | Clean, structure, and transform — document every decision |
| Analyse | Descriptive first, then diagnostic, then predictive |
| Present | Communicate the finding and the reframe, not just the result |

---

## Project Status

**Current Stage: Ask**
Research questions defined. Data sources under investigation. No data collected yet.

This project is ongoing and will be updated as each stage of the analysis is completed.

---

## A Note on Methodology

This research is intentionally perspective-led before it is data-led. The questions came first. The data will be used to challenge, confirm, or complicate those questions — not to generate them. That order matters.

Most analysis begins with available data and works toward whatever questions that data can answer. This project begins with the questions that matter and works toward the data that can answer them. The difference is not academic. It is the difference between finding what is easy to measure and finding what is worth knowing.

---

*Ongoing independent research — updated as the analysis progresses.*
