# 5W2H METHOD IN DEFENSE ORIENTED DATA SCIENCE PROJECTS

> The 5W2H framework is a structured questioning method that helps you cover every critical dimension of your project in a clear, logical, and convincing way. Here’s how each dimension maps to a data science defense context.


## Who? (Stakeholders & Team)

Identify who is involved in the project: who **conducted** the research, who **supervised** it, and crucially, **who benefits from the results**.

In a defense project, you want to make clear who the end users of your model or analysis are (a hospital, a business unit, a policy maker, etc.), as this grounds the project in real-world relevance and justifies its scope.

In a defense data science context, this includes:

- Military units, commands, and operational staff
- Intelligence analysts and fusion centers
- Defense contractors and system integrators
- Government agencies and regulatory authorities
- Adversarial actors or threat entities (when modeling hostile behavior)
- End-users of analytical systems (commanders, operators, analysts)

From a data perspective, this also includes:

- Data owners and custodians
- Data producers (sensors, platforms, ISR systems)
- Data consumers (decision-makers, automated systems)

---

## What? (Problem Definition & Objectives)

This is the core of your introduction. Precisely define what problem you are solving, what your target variable is, what kind of task it is (classification, regression, clustering, NLP, etc.), and what success looks like.

In defense data science, this typically covers:

- The operational problem (anomaly detection in ISR data, predictive maintenance of aircraft, maritime domain awareness)
- The analytical task (classification, regression, clustering, forecasting, anomaly detection, data fusion, etc.)
- The assets or systems under study (aircraft, ships, satellites, radars, communication systems)
- The variables of interest (sensor measurements, telemetry, logs, geospatial data, signals intelligence)

It also includes:

- Key performance indicators (KPIs)
- Mission success criteria
- Model outputs and decision-support products

---

## When? (Timeline & Data Temporality)

Explain when the project was conducted, but also (and this is often overlooked) address the temporal dimension of your data. When was it collected? Is there a risk of temporal leakage or concept drift? For time-series projects, this dimension becomes central to your methodology.

Key considerations include:

- Real-time, near-real-time, or batch processing requirements
- Historical analysis vs. live operational monitoring
- Temporal resolution and sampling rates
- Mission timelines and operational tempo
- Model retraining cycles and data refresh frequencies
- Seasonality, trends, and concept drift

---

## Where? (Data Sources & Context)

Describe where your data comes from: the platform, organization, or database, and whether it is proprietary, open-source, or scraped. This is also where you justify the geographical or organizational scope of your study and address any data access or ethical constraints.

In defense applications, this includes:

- Operational Environment:
    - Theaters of operation (land, maritime, air, space, cyber)
    - Geographic regions (AOIs, EEZs, airspaces, conflict zones)
    - Physical constraints (terrain, weather, electromagnetic environment)

- Data Environment:
    - On-board systems vs. ground stations
    - Edge computing vs. centralized data centers
    - Classified vs. unclassified networks
    - Interoperable systems and coalition data-sharing environments

---

## Why? (Motivation & Scientific Justification)

This is arguably the most important dimension. You need to articulate why this problem matters, why data science is the right approach, and why your methodological choices (model selection, preprocessing strategy, evaluation metric) were made. Linking your “why” to the literature strengthens your scientific posture significantly.

In defense-oriented data science, this includes:

- Improving situational awareness
- Enhancing force protection
- Increasing operational readiness
- Reducing maintenance costs and downtime
- Detecting hostile or anomalous behavior
- Supporting intelligence-driven decision-making
- Increasing mission effectiveness and survivability

This dimension also supports:

- Cost-benefit analysis
- Return on investment (ROI) in defense capabilities
- Alignment with doctrine, capability development plans, and national security strategies

---

## How? (Methodology & Pipeline)

Walk through how you solved the problem: your end-to-end pipeline from data ingestion and preprocessing, through feature engineering, model training, hyperparameter tuning, to evaluation. Be precise about your technical choices and ready to defend them. Reproducibility and rigor are key signals juries look for here.

In a defense data science project, this includes:

- Analytical Methods:
    - Machine learning (supervised, unsupervised, semi-supervised)
    - Deep learning for sensor and signal processing
    - Bayesian methods and probabilistic modeling
    - Time-series analysis
    - Graph analytics and network analysis
    - Data fusion and multi-sensor integration

- Engineering and MLOps:
    - Data pipelines and ETL/ELT processes
    - Model deployment (edge vs. cloud/on-prem)
    - MLOps and continuous integration
    - Model monitoring and performance validation
    - Explainability and interpretability (XAI)
    - Governance and Security:
    - Data classification and access control
    - Compliance with defense cybersecurity standards
    - Auditability and traceability
    - Model validation and certification processes

---

## How Much? (Metrics, Scale & Resources)

Quantify everything: how much data you used, how long training took, what computational resources were needed, and most importantly, how well your model performs across your chosen metrics. Be honest about trade-offs (precision vs. recall, bias vs. variance).

This includes:

- Budget and funding constraints
- Human resources (data scientists, engineers, domain experts)
- Computational resources (HPC, GPUs, edge devices)
- Data acquisition and labeling costs
- Development and maintenance costs
- Opportunity costs

It also includes:

- Risk assessment (technical, operational, cybersecurity, ethical)
- Model risk and failure impact
- Sensitivity analysis and uncertainty quantification

---

## Conclusion

By systematically addressing each of these seven questions, you create a comprehensive project blueprint that anticipates challenges, clarifies expectations, and provides a framework for execution and evaluation.

The 5W2H method promotes rigorous thinking about your research design and helps communicate your project effectively to advisors, collaborators, and funding bodies. It also serves as a living document that you can revisit throughout your project to ensure you remain aligned with your original objectives while adapting to new insights or constraints that emerge during the research process.

**The author gratefully acknowledges the reader’s time and consideration.**