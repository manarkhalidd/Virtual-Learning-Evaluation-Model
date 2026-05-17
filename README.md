<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Sora&weight=800&size=30&pause=1000&color=3498DB&center=true&vCenter=true&width=800&lines=Virtual+Learning+Evaluation+Model;Predicting+Student+Success+with+AI;Transforming+Education+Through+Data" alt="Typing SVG" />

<br>

# 🎓 Virtual Learning Evaluation Model
### *The Future of Education is Predictive, Not Reactive*

<br>

> **"32,593 students. 7 data sources. 15 key parameters. One model that can change the way the world teaches — forever."**

<br>

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-Deployed-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-Ensemble-189AB4?style=for-the-badge&logo=xgboost&logoColor=white)
![RandomForest](https://img.shields.io/badge/Random_Forest-Ensemble-2ecc71?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-Visualization-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

<br>

[![MIT License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![OULAD Dataset](https://img.shields.io/badge/Dataset-OULAD-blue?style=flat-square)](https://analyse.kmi.open.ac.uk/open-dataset)
[![Streamlit App](https://img.shields.io/badge/App-Streamlit-FF4B4B?style=flat-square&logo=streamlit)](https://streamlit.io)
[![Status](https://img.shields.io/badge/Status-Deployed_Locally-2ecc71?style=flat-square)]()

<br>

</div>

---

<div align="center">

## 🌍 The Problem That Inspired Everything

</div>

<br>

Imagine being a university administrator in 2025.

You have **thousands of students** enrolled in your online learning platform. They log in. They click through materials. They submit assignments. They disappear.

And you have **no idea** which ones are about to fail.

Not until the final exam results come in.
Not until the withdrawal forms land on your desk.
Not until it is **too late.**

<br>

> 📉 **As of 2025, globally between 25–40% of VLE-enrolled university students fail or withdraw every single year**
>
> ❌ **Traditional online courses see completion rates as low as 10–15% globally** *(Harvard Business Review, 2023)*
>
> 🚫 **The majority of educational institutions worldwide have zero early alert systems in place**
>
> 📊 **Engagement data is collected by every VLE platform — but analysed by almost none**
>
> ⏳ **By the time failure becomes visible through grades — the intervention window has already closed**
>
> 🔴 **In our own dataset alone — 52.8% of Open University students failed or withdrew before completing their module**

<br>

This is not a data problem.
This is not a technology problem.
**This is a will-to-act problem — and we built the tool to act.**

---

<div align="center">

## 💡 The Vision

### *What if a university could know a student is about to fail — before they even know it themselves?*

</div>

<br>

That is exactly what this project does.

The **Virtual Learning Evaluation Model** is a fully deployed, end-to-end machine learning system that:

- 🔮 **Predicts** each student's probability of success — before any exam takes place
- 🚨 **Identifies** at-risk students weeks before they disengage or withdraw
- 🔍 **Diagnoses** whether underperformance is driven by engagement, academic performance, or socioeconomic factors
- 📊 **Evaluates** the health of an entire Virtual Learning Environment at the organisational level
- 💡 **Recommends** specific, evidence-based interventions for every student and every module
- 🖥️ **Delivers** all of this through a professional, interactive web application — ready to use today

<br>

This is not a research paper. This is not a proof of concept.
**This is a deployable system — built on real data, trained on 32,593 real students, and producing real predictions.**

---

<div align="center">

## 📂 The Dataset — The Foundation of Truth

</div>

<br>

**Source:** [Open University Learning Analytics Dataset (OULAD)](https://analyse.kmi.open.ac.uk/open-dataset)
**Institution:** The Open University, United Kingdom
**Published by:** Knowledge Media Institute (KMI)

This is not synthetic data. This is not a sample.
This is **one of the largest and most comprehensive real-world educational datasets ever made publicly available** — capturing the complete learning journey of tens of thousands of real university students.

<br>

| 📁 File | 📊 Records | 📋 Description |
|---------|-----------|----------------|
| `courses.csv` | 22 | Every module and presentation offered |
| `assessments.csv` | 206 | Every assignment, coursework and exam |
| `vle.csv` | 6,364 | Every learning resource on the platform |
| `studentInfo.csv` | 32,593 | Every student's demographics and final result |
| `studentRegistration.csv` | 32,593 | Every registration and withdrawal event |
| `studentAssessment.csv` | 173,912 | Every score submitted by every student |
| `studentVle.csv` | 10,655,280 | Every single click on every learning resource |

<br>

> **Over 10 million interaction records. Every click. Every login. Every late submission. Every withdrawal.**
> **This is the raw material of human learning — and we turned it into predictive intelligence.**

---

<div align="center">

## 🔬 The 15 Parameters That Predict Everything

### *After processing 10+ million records, these are the signals that matter*

</div>

<br>

### 👤 Who The Student Is — Demographic Signals

| # | Parameter | Why It Matters |
|---|-----------|---------------|
| 1 | **Gender** | Identifies performance patterns across gender groups |
| 2 | **Age Band** | Older students face different life pressures than younger ones |
| 3 | **Region** | Geographic access and support infrastructure varies |
| 4 | **Highest Education** | Prior academic experience shapes learning capacity |
| 5 | **IMD Band** | Socioeconomic deprivation directly impacts academic outcomes |
| 6 | **Disability** | Flags students who may need additional platform accommodations |
| 7 | **Previous Attempts** | Repeat students carry compounding disadvantage without intervention |
| 8 | **Credits Studied** | Higher workload correlates with higher dropout risk |

<br>

### 🖱️ What The Student Does — Behavioural Signals

| # | Parameter | Why It Matters |
|---|-----------|---------------|
| 9 | **Total VLE Clicks** | Overall engagement volume — the heartbeat of a student's activity |
| 10 | **Active Days** | Consistency of engagement — are they showing up every week? |
| 11 | **Early Clicks *(First 30 Days)*** | ⭐ **The single strongest predictor** — early disengagement predicts everything |
| 12 | **Activity Type Diversity** | Students who explore broadly perform significantly better |

<br>

### 📝 How The Student Performs — Academic Signals

| # | Parameter | Why It Matters |
|---|-----------|---------------|
| 13 | **Average Assessment Score** | Overall academic performance across all submission types |
| 14 | **Average TMA Score** | Coursework grades — more predictive of final results than exams |
| 15 | **Late Submission Rate** | Chronic lateness is a compounding risk signal — not just a habit |

<br>

> **Key Insight: Behavioural signals outperform demographic signals.**
> **What a student DOES on the VLE is more predictive of their success than who they ARE.**
> **This means failure is not inevitable — it is detectable, and therefore preventable.**

---

<div align="center">

## 🗺️ The Pipeline — From Raw Data to Real Predictions

</div>

<br>

```
╔══════════════════════════════════════════════════════════════════╗
║           RAW OULAD DATA  ·  7 CSV Files  ·  10M+ Records        ║
╚══════════════════════════════════════════════════════════════════╝
                               │
                               ▼
╔══════════════════════════════════════════════════════════════════╗
║                    📥  DATA LOADING                               ║
║         Import · Preview · Validate Structure                     ║
╚══════════════════════════════════════════════════════════════════╝
                               │
                               ▼
╔══════════════════════════════════════════════════════════════════╗
║                 🔍  EXPLORATORY DATA ANALYSIS                     ║
║    Distributions · Patterns · Module Performance · Demographics   ║
╚══════════════════════════════════════════════════════════════════╝
                               │
                               ▼
╔══════════════════════════════════════════════════════════════════╗
║                  🧹  DATA QUALITY CHECK                           ║
║         Missing Values · Duplicates · Outlier Detection           ║
╚══════════════════════════════════════════════════════════════════╝
                               │
                               ▼
╔══════════════════════════════════════════════════════════════════╗
║                  ⚙️  DATA PREPROCESSING                           ║
║        Imputation · Encoding · Normalisation · Cleaning           ║
╚══════════════════════════════════════════════════════════════════╝
                               │
                               ▼
╔══════════════════════════════════════════════════════════════════╗
║                 🛠️  FEATURE ENGINEERING                           ║
║    7 Tables Merged → Master DataFrame → 15 Predictive Features    ║
╚══════════════════════════════════════════════════════════════════╝
                               │
                               ▼
╔══════════════════════════════════════════════════════════════════╗
║                  ✂️  MODEL PREPARATION                            ║
║         Stratified Train/Test Split · Class Balance Check         ║
╚══════════════════════════════════════════════════════════════════╝
                               │
                               ▼
╔══════════════════════════════════════════════════════════════════╗
║                    🤖  MODEL TRAINING                             ║
║   Logistic Regression  →  Random Forest  →  XGBoost Ensemble      ║
╚══════════════════════════════════════════════════════════════════╝
                               │
                               ▼
╔══════════════════════════════════════════════════════════════════╗
║                   📊  MODEL EVALUATION                            ║
║       Accuracy · F1 Score · AUC-ROC · Confusion Matrix            ║
╚══════════════════════════════════════════════════════════════════╝
                               │
                               ▼
╔══════════════════════════════════════════════════════════════════╗
║                🧠  FEATURE IMPORTANCE ANALYSIS                    ║
║         Which parameters drive success — ranked and visualised    ║
╚══════════════════════════════════════════════════════════════════╝
                               │
                               ▼
╔══════════════════════════════════════════════════════════════════╗
║                  🚦  STUDENT SEGMENTATION                         ║
║            🔴 High Risk  ·  🟡 Medium Risk  ·  🟢 Low Risk        ║
╚══════════════════════════════════════════════════════════════════╝
                               │
                               ▼
╔══════════════════════════════════════════════════════════════════╗
║             🖥️  STREAMLIT WEB APPLICATION — DEPLOYED              ║
║     Real-Time Predictions · Insights · Charts · Recommendations   ║
╚══════════════════════════════════════════════════════════════════╝
```

---

<div align="center">

## 🤖 The Models — Why We Chose an Ensemble

</div>

<br>

We did not stop at one model. We built three — and combined the best two into a final ensemble.

| 🤖 Model | 🎯 Accuracy | 📊 F1 Score | 📈 AUC-ROC | 🧠 Purpose |
|---------|------------|------------|-----------|-----------|
| Logistic Regression | ~94% | ~0.88 | ~0.86 | Baseline benchmark — simple & interpretable |
| Random Forest | ~96% | ~0.90 | ~0.89 | 100 decision trees — powerful pattern detection |
| XGBoost | ~96% | ~0.90 | ~0.89 | Gradient boosting — corrects its own mistakes |
| ⭐ **RF + XGBoost Ensemble** | **~90%** | **~0.90** | **~0.96** | **Final model — best of both worlds** |

<br>


<br>

The final model averages the predicted probabilities of both Random Forest and XGBoost:

```python
success_probability = (random_forest_probability + xgboost_probability) / 2
```

This ensemble approach reduces individual model bias, improves generalisation, and produces the most reliable predictions possible from this dataset.

<br>

### 🚦 Risk Classification

Every student receives one of three classifications:

| 🚦 Risk Level | 🎯 Probability | 🏥 Recommended Action |
|--------------|--------------|----------------------|
| 🟢 **Low Risk** | ≥ 65% | Monitor regularly — student is on track |
| 🟡 **Medium Risk** | 40–64% | Proactive support — engage before problems escalate |
| 🔴 **High Risk** | < 40% | **Immediate intervention required** |

---

<div align="center">

## 🖥️ The Application — Where Science Meets Reality

</div>

<br>

The science means nothing if no one can use it.

That is why we built a **fully interactive, professionally designed Streamlit web application** that brings the entire model to life — turning raw predictions into visual, actionable intelligence for educators and administrators.

<br>

### What the App Delivers

```
┌─────────────────────────────────────────────────────────────┐
│  🎓  VIRTUAL LEARNING EVALUATION MODEL                       │
│─────────────────────────────────────────────────────────────│
│                                                             │
│  📊 ORGANISATION DASHBOARD                                  │
│  ├── Total Students: 32,593                                 │
│  ├── Overall Pass Rate: XX%                                 │
│  ├── High Risk Students: X,XXX                              │
│  ├── Average VLE Clicks: X,XXX                              │
│  └── Withdrawal Rate: XX%                                   │
│                                                             │
│  🔍 SELECT STUDENT ID ────────────────────────────────────  │
│                                                             │
│  👤 STUDENT PROFILE          🎯 SUCCESS PROBABILITY         │
│  ├── Demographics            ├── Ensemble Score: XX%        │
│  ├── Module & Presentation   ├── Random Forest:  XX%        │
│  ├── Risk Classification     └── XGBoost:        XX%        │
│  └── Actual Final Result                                    │
│                                                             │
│  📊 TAB 1: Performance Overview                             │
│  ├── Radar Chart: Student vs Organisation Average           │
│  ├── Assessment Performance Bar Chart                       │
│  └── Percentile Ranking Across All Parameters               │
│                                                             │
│  🖱️ TAB 2: VLE Engagement                                   │
│  ├── Click Breakdown Chart                                  │
│  ├── 30-Day Engagement Timeline                             │
│  ├── Activity Type Diversity Donut                          │
│  └── Late Submission Behaviour Donut                        │
│                                                             │
│  💡 TAB 3: Insights & Recommendations                       │
│  ├── Auto-Generated Insight Cards (colour coded)            │
│  ├── Prioritised Action Recommendations                     │
│  └── Feature Importance Chart                               │
│                                                             │
│  🏢 TAB 4: Organisation Analytics                           │
│  ├── Pass Rate by Module                                    │
│  ├── Risk Group Distribution                                │
│  ├── Pass Rate by Age Band                                  │
│  ├── Engagement vs Success Scatter Plot                     │
│  └── Organisation-Wide Result Distribution                  │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

<br>

### Run The App in 3 Steps

```bash
# Step 1 — Install dependencies
pip install streamlit pandas numpy scikit-learn xgboost plotly matplotlib seaborn

# Step 2 — Navigate to project folder
cd "your/project/folder"

# Step 3 — Launch
streamlit run app.py
```

> Then open **http://localhost:8501** in your browser — and watch 32,593 students come to life.

---

<div align="center">

## 🔍 What We Discovered — Key Findings That Matter

</div>

<br>

| # | 🔑 Finding | 💥 Impact |
|---|-----------|----------|
| 1 | 🖱️ **Early engagement in the first 30 days is the single strongest predictor of success** | An alert system in week 1 can prevent failure months later |
| 2 | 📝 **TMA coursework scores predict final results better than exam scores** | Continuous assessment is a more accurate and fairer measure of learning |
| 3 | 🧠 **What a student DOES on the VLE matters more than who they ARE** | Failure is behavioural — and behaviour can be changed |
| 4 | ⏰ **Chronic late submissions compound into withdrawal** | A deadline reminder system is one of the cheapest interventions possible |
| 5 | 💰 **Socioeconomic deprivation measurably reduces success rates** | Online learning does not automatically equalise opportunity |
| 6 | 🔄 **Repeat students do not improve without targeted intervention** | Re-enrolment alone is not a solution — a plan is |

---

<div align="center">

## 💡 Recommendations — What The World Should Do With This

</div>

<br>

| 🏷️ Priority | 💡 Recommendation | 🎯 Expected Impact |
|------------|-------------------|-------------------|
| 🚨 **Critical** | Deploy an automated early alert system flagging low activity in the first 30 days | Catch at-risk students before any assessment occurs |
| 📚 **High** | Shift institutional focus from final exams to continuous TMA assessment | More accurate measurement of real student understanding |
| 🖥️ **High** | Redesign VLE content to encourage diversity across activity types | Students who explore broadly consistently outperform those who do not |
| ⏰ **Medium** | Implement automated deadline reminders 7 and 3 days before each submission | Reduce late submission rates and the compounding risk they create |
| 🔄 **Medium** | Create personalised re-enrolment plans for all repeat students | Break the cycle of repeated failure without intervention |
| 🤝 **Ongoing** | Establish dedicated support pathways for high-deprivation students | Ensure online learning delivers on its promise of equal access |

---

<div align="center">

## 🌍 The Real-World Impact — Why This Changes Everything

</div>

<br>

This project is not just a graduation requirement.
**It is a blueprint for how every university in the world should be operating.**

<br>

### For Students 🎓
> No more silent failures. No more feeling lost without support.
> A system that sees you struggling — before you even realise it yourself —
> and sends help your way.

<br>

### For Educators 👨‍🏫
> No more waiting for exam results to know who needs help.
> A dashboard that tells you — right now, today — which students need your attention most.

<br>

### For Institutions 🏛️
> No more expensive audits. No more reactive crisis management.
> A real-time organisational health score for your entire VLE —
> telling you which modules are working, which are failing, and exactly why.

<br>

### For Education as a Whole 🌐
> The global online learning market is heading toward **$1 trillion by 2032**.
> As it grows, so does the scale of its dropout crisis.
> Models like this one are not optional extras —
> **they are the infrastructure that makes mass online education sustainable.**

<br>

> *"We might not need to audit our educational organizations anymore.*
> *We might not lose our students along the way.*
> *Because for the first time — we can see what is coming."*

---

<div align="center">

## 📁 Project Structure

</div>

<br>

```
📁 Virtual-Learning-Evaluation-Model/
│
├── 📓 Virtual_Learning_Evaluation_Model.ipynb   ← Full ML pipeline notebook
├── 🖥️  app.py                                   ← Streamlit web application
├── 📄 README.md                                 ← You are reading this
│
└── 📁 data_set/                                 ← Place OULAD CSV files here
    ├── courses.csv
    ├── assessments.csv
    ├── vle.csv
    ├── studentInfo.csv
    ├── studentRegistration.csv
    ├── studentAssessment.csv
    └── studentVle.csv
```

> ⚠️ **The dataset is not included** due to file size. Download it free from
> [analyse.kmi.open.ac.uk/open-dataset](https://analyse.kmi.open.ac.uk/open-dataset)
> and place all CSV files inside a `data_set/` folder.

---

<div align="center">

## 🚀 Getting Started

</div>

<br>

**1. Clone the repository**
```bash
git clone https://github.com/your-username/Virtual-Learning-Evaluation-Model.git
cd Virtual-Learning-Evaluation-Model
```

**2. Install all dependencies**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost plotly streamlit jupyter
```

**3. Download the dataset**

Go to [https://analyse.kmi.open.ac.uk/open-dataset](https://analyse.kmi.open.ac.uk/open-dataset),
download the ZIP, extract it and place all 7 CSV files inside a `data_set/` folder.

**4. Run the Jupyter Notebook**
```bash
jupyter notebook Virtual_Learning_Evaluation_Model.ipynb
```

**5. Launch the Web Application**
```bash
streamlit run app.py
```

---

<div align="center">

## 🛠️ Built With

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=for-the-badge)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

---

<div align="center">

## 👥 The Team Behind The Vision

</div>

<br>

<div align="center">

| 👤 Name | 🏷️ Role |
|---------|---------|
|  **Manar Khalid** | Team Leader — Project management, pipeline oversight & quality review |
| **Mohamed Elsakka** | Data Engineer — Data loading, preprocessing & table merging |
| **Mohamed Yahia Kamal** | ML Engineer — Model building, training, tuning & evaluation |
| **Shaimaa Essam** | Feature Engineer — Feature design, encoding & target variable definition |
| **Abd El-rahman Ali** | Data Analyst — EDA, visualizations, insights & recommendations |
| **Alaa Ibrahim Ali** | Reporter — Notebook narrative, PowerPoint presentation & delivery |

</div>

---

<div align="center">

## 🔭 What Comes Next

</div>

<br>

This project is a foundation — not a ceiling.

| 🚀 Future Direction | 📋 Description |
|--------------------|---------------|
| ☁️ **Cloud Deployment** | Deploy on Streamlit Cloud for a public URL accessible by any institution worldwide |
| ⏱️ **Real-Time Integration** | Connect directly to a live VLE system for continuous, live predictions |
| 📈 **Time-Series Modelling** | Track engagement week by week to detect deterioration trends earlier |
| 💬 **NLP on Forum Activity** | Analyse quality and sentiment of student forum posts as an additional signal |
| 🌐 **Multi-Institution Validation** | Test the model across datasets from multiple universities globally |
| 📱 **Mobile Application** | Bring the dashboard to mobile for on-the-go educator access |

---

<div align="center">

<br>

## ✨ Final Words

<br>

*"Education is the most powerful weapon you can use to change the world."*
*— Nelson Mandela*

<br>

**We built this because we believe no student should fail silently.**
**We built this because data already has all the answers — it just needs someone to ask.**
**We built this because the future of education is not reactive. It is predictive.**

<br>

---

*Virtual Learning Evaluation Model · OULAD Dataset · Graduation Project 2025*
*Built with* ❤️ *by a team that believes education deserves better tools*

<br>

⭐ *If this project inspires you — star it, share it, build on it.*
*The more people who see this, the more students who get the help they deserve.*

<br>

</div>
