# Lindiwe Songelwa — Data Science & DevOps Portfolio

A fully responsive, single-page portfolio website built with pure HTML, CSS, and JavaScript — showcasing 12 projects across two disciplines: **Data Science** and **DevOps Engineering (AZ-400)**.

🔗 **Live Site**: [lindiwe-22.github.io/Portfolio-Website](https://lindiwe-22.github.io/Portfolio-Website/)

---

## 📁 Project Structure

```
portfolio-website/
│
├── index.html          # Main HTML structure — all sections and project cards
├── styles.css          # All CSS styles, animations, and responsive layout
├── script.js           # JavaScript for interactivity and scroll behaviour
└── README.md           # Project documentation
```

---

## 🗂️ Featured Projects

### 🔬 Data Science

| Project | Description | Stack |
|---|---|---|
| **SA Crime Intelligence Report** | Rigorous interrogation of Q3 2025/26 SAPS crime statistics cross-referenced with SAMRC femicide data. Applies OLS regression, ARIMA forecasting, correlation analysis and anomaly detection. | Python, Statsmodels, Scikit-learn, ARIMA |
| **Mining Quality Intelligence** | Full-stack ML system predicting silica concentrate failures in an iron ore flotation plant, trained on 737,453 sensor readings with a live GREEN/AMBER/RED Streamlit dashboard. | XGBoost, TensorFlow, SMOTE, Streamlit, Plotly |
| **Tyla Grammy Sentiment Analysis** | NLP study revealing 82% positive sentiment across 214 fan reactions in 20+ countries following Tyla's historic Grammy win. Dual-model validation with VADER and TextBlob. | Python, VADER, TextBlob, YouTube API, WordCloud |
| **Diamonds Are Forever** | Full-stack ML investigation into the diamond industry — quantifying the 73.8% lab-grown price collapse, K-Means buyer archetypes, and price forecasting at R²=0.9997. | Random Forest, XGBoost, K-Means, Streamlit, Plotly |
| **SA Bank Trust Score** | Consumer intelligence dashboard scoring South Africa's six major banks across complaint resolution, regulatory sanctions, consumer favour rate and public sentiment. | Python, Streamlit, Pandas, Matplotlib, OBS/SARB Data |
| **Who Really Gets the Money?** | Public interest investigation into R69.5 billion of SA development finance — combining Gini/Lorenz inequality analysis, ML cost-per-job prediction, and Isolation Forest anomaly detection. | Scikit-learn, XGBoost, Isolation Forest, Streamlit, Plotly |

### ⚙️ DevOps (AZ-400 Portfolio)

| Project | Description | Stack |
|---|---|---|
| **SA Bank Trust Score — DevOps Pipeline** | Production-grade CI/CD pipeline with four GitHub Actions workflows: app health checks, CSV data quality validation, scheduled data freshness monitor with auto Issue creation, and Docker build verification. | GitHub Actions, Docker, CI/CD, YAML |
| **Tyla Sentiment Tracker** | Automated fortnightly sentiment tracking pipeline — YouTube comments analysed on a scheduled GitHub Actions workflow with no manual intervention. | GitHub Actions, VADER, TextBlob, Scheduled CI |
| **Prometheus — Grafana Monitoring** | Production observability stack for the Iris Model API — metrics collection, dashboard visualisation and alerting in a fully containerised environment. | Prometheus, Grafana, Docker |
| **K8s Iris Deployment** | Production-grade Kubernetes deployment demonstrating container orchestration, autoscaling, and rolling updates using Kubernetes manifests and kubectl. | Kubernetes, Docker, kubectl |
| **Terraform — Docker IaC** | Infrastructure as Code project provisioning a full Docker stack using Terraform — multi-environment deployment, resource management and infrastructure versioning. | Terraform, Docker, HCL |
| **ML CI/CD Pipeline** | End-to-end ML model deployment pipeline built on GitHub Actions — automated training, testing, and deployment stages for a machine learning model. | GitHub Actions, Python, CI/CD |

---

## 🛠️ Technologies Used

### Frontend
- **HTML5** — Semantic markup and accessible structure
- **CSS3** — Custom properties, CSS Grid, Flexbox, keyframe animations, glassmorphism
- **JavaScript (ES6+)** — Intersection Observer API, scroll behaviour, dynamic panel toggling

### Data Science Stack
- Python, Pandas, NumPy, Scikit-learn, XGBoost, TensorFlow
- Statsmodels (OLS, ARIMA), VADER, TextBlob
- Streamlit, Plotly, Matplotlib, Seaborn

### DevOps Stack
- GitHub Actions (CI/CD workflows, scheduled jobs, artifact management)
- Docker (containerisation, Docker Compose, multi-stage builds)
- Kubernetes (manifests, kubectl, autoscaling, rolling updates)
- Terraform (IaC, HCL, multi-environment provisioning)
- Prometheus & Grafana (metrics, observability, alerting)
- YAML (workflow and manifest authoring)

---

## 🎨 CSS Techniques

- **Keyframe animations** — floating hero circles, skill bar shimmer, morphing profile border
- **CSS custom properties** — centralised design tokens for colour, shadow, and gradient
- **Glassmorphism** — `backdrop-filter: blur()` on the fixed navigation bar
- **Intersection Observer API** — scroll-triggered animations on section entry
- **SVG illustrations** — inline, self-hosted project card visuals (no external image dependencies)
- **Mobile-first responsive design** — breakpoints at 768px and 480px

---

## 🚀 Deployment

The portfolio is deployed via **GitHub Pages** and updates automatically on every push to `main`.

**Live URL**: [https://lindiwe-22.github.io/Portfolio-Website/](https://lindiwe-22.github.io/Portfolio-Website/)

To run locally:
```bash
git clone https://github.com/Lindiwe-22/Portfolio-Website.git
cd Portfolio-Website
# Open index.html directly in any modern browser
start index.html       # Windows
open index.html        # Mac
xdg-open index.html    # Linux
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Target |
|---|---|
| 1200px+ | Desktop |
| 768px – 1199px | Tablet |
| 320px – 767px | Mobile |

---

## 📧 Contact

**Lindiwe Songelwa**
- Email: sl.songelwa@hotmail.co.za
- GitHub: [github.com/Lindiwe-22](https://github.com/Lindiwe-22)
- LinkedIn: [linkedin.com/in/lindiwe-songelwa](https://www.linkedin.com/in/lindiwe-songelwa)
- Credly: [credly.com/users/samnkelisiwe-lindiwe-songelwa](https://www.credly.com/users/samnkelisiwe-lindiwe-songelwa)

---

*Built with HTML, CSS, JavaScript — and a lot of intention.*
