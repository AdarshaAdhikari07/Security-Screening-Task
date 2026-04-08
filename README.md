# Human-in-the-Loop System : A Comparative Study Of Manual and AI-Assisted Security Screening

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge.svg)](https://security-screening.streamlit.app/)
https://security-screening.streamlit.app/

##  Project Overview
This software is a **Security Screening Task** developed for research into **Automation Bias** and **Verification Latency** in  security screening contexts. Unlike studies using static image datasets, this system utilizes a custom **Stochastic Procedural Content Generation (PCG) Engine** to create randomized luggage layouts for every trial, ensuring the measurement of true visual vigilance.

The project quantifies the "Speed-Accuracy Trade-off" when human operators are assisted by an imperfect AI agent (85% reliability).

##  Core Features
* **Stochastic PCG Engine:** Procedural generation of stimuli using Unicode symbols to simulate threat and non-threat items, maintaining a fixed **40% threat prevalence**.
* **Imperfect AI Agent:** A simulated assistant with a calibrated **85% reliability rate** to test human-AI trust calibration.
* **High-Resolution Telemetry:** Captures decision accuracy, verification latency (ms), and Signal Detection Theory (SDT) outcome frequencies.
* **SDT Analytics:** Integrated framework to calculate sensitivity ($d'$) and response bias ($\ln\beta$).

##  Technical Stack
* **Framework:** [Streamlit](https://streamlit.io/) (Web-based Interface)
* **Language:** Python 
* **Data Science:** Pandas, NumPy, SciPy (Statistical T-tests)
* **Visualization:** Matplotlib, Seaborn (KDE & Boxplots)
* **Verification:** Monte Carlo simulation ($N=10,000$) to confirm stochastic convergence of AI reliability.

##  Experimental Results (30 Participants)
The study identified a statistically significant **Automation Bias** effect:


##  Installation & Usage
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/AdarshaAdhikari07/Security-Screening-Task.git](https://github.com/AdarshaAdhikari07/Security-Screening-Task.git)
    cd Security-Screening-Task
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the application:**
    ```bash
    streamlit run app.py
    ```

##  Ethical Considerations
* **Project Ref:** P192826 (Coventry University)
* **Privacy by Design:** No Personally Identifiable Information (PII) is captured.
* **Informed Consent:** Participants must complete a mandatory 5-point consent checklist prior to data collection.

##  Contact
**Adarsha Adhikari** 

Artificial Intelligence & Human Factor MSc

##  Supervisor
**Dr Mark Eslaw**

