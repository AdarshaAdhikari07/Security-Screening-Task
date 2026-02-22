
HUMAN-IN-THE-LOOP  SYSTEM:  A Comparative Study Of Manual and AI-Assisted Security Screening


1. PROJECT OVERVIEW
-------------------
This software is a 'Security Inspection System' developed in Python
(Streamlit) for research into "Automation Bias" and "Verification
Latency" in  security screening. 

Instead of static images, the system uses a Stochastic Procedural Content 
Generation (PCG) engine to create randomized luggage bags for every trial, 
ensuring the assessment of true visual vigilance.

2. CORE FEATURES
----------------
* Stochastic PCG: Randomizes  luggage layouts using Unicode symbols 
  for threat and non-threat items.
* Imperfect AI Agent: Simulated assistant with 85% reliability (P=0.85) 
  to test trust calibration.
* Telemetry Logging: Captures reaction time (ms), decision accuracy, 
  and interaction mode into a structured CSV format.

3. TARGET THREATS
-----------------
Participants act as Security Officers to identify:
Threat iteams  



4. INSTALLATION & USAGE
-----------------------
Requirements: Python 3.9+, Streamlit, Pandas, NumPy, SciPy.

1. Install dependencies:
   pip install -r requirements.txt

2. Run the application:
   streamlit run app.py

6. ETHICAL CONSIDERATIONS
-------------------------
Project Ref: P192826
The study uses 'Privacy by Design'—no personal identifiable information 
(PII) is captured. All participants must pass a 5-point 
informed consent checklist before beginning

7. CONTACT
----------
Student Name: Adarsha Adhikari 
