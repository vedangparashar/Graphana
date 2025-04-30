# 📊 Prometheus + Grafana Monitoring Setup

This repository contains a complete setup of **Prometheus** and **Grafana** using Docker and Docker Compose. It enables real-time monitoring of services and applications with customizable dashboards.

---

## 🚀 Project Overview

- 🧠 **Prometheus**: Powerful metrics and alerting toolkit.
- 📈 **Grafana**: Data visualization and dashboarding.
- 🐳 **Docker Compose**: Container orchestration for seamless setup.

---

## 📁 Project Structure

```bash
📦 Prometheus-Grafana-
├── docker-compose.yml
├── prometheus.yml
├── screenshots/
│   ├── prometheus_home.png
│   └── grafana_dashboard.png
└── README.md
⚙️ How to Run
Make sure Docker and Docker Compose are installed.

1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/Diwish15/Prometheus-Grafana-.git
cd Prometheus-Grafana-
2️⃣ Run the Setup
bash
Copy
Edit
docker-compose up -d
3️⃣ Access the Web UIs
🔹 Prometheus: http://localhost:9090

🔸 Grafana: http://localhost:3000

📌 Default Grafana login

Username: admin

Password: admin

📷 Screenshots
Prometheus P.png

Grafana G.png

📜 Configuration
docker-compose.yml
Defines services for Prometheus and Grafana with port bindings.

prometheus.yml
Basic scrape config for Prometheus.

yaml
Copy
Edit
scrape_configs:
  - job_name: 'prometheus'
    static_configs:
      - targets: ['localhost:9090']
✅ Status
 Docker Compose Setup

 Prometheus Running

 Grafana Running

 Dashboards Created

 Screenshots Added

🧑‍💻 Author
Diwish Rastogi
GitHub: @Diwish15

