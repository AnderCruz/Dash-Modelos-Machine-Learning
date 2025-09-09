# 🚀 MLOps: Model Deployment

This project demonstrates how to **deploy machine learning models** in production environments using **Flask, Docker, Google Cloud Platform (GCP), and GitHub Actions**.

Developed by **Nowa Analytics**, a consultancy specialized in **Data Science, Machine Learning, and MLOps solutions**.

--

## 📌 Project Overview

The main objective of this project is to learn how to:

* Make machine learning models accessible via APIs
* Deploy models using **Flask** and **Google Cloud Platform**
* Package and distribute applications with **Docker**
* Automate continuous deployment with **GitHub Actions**

By the end of this project, you will have a **production-ready deployment pipeline** for serving ML models.

---

## ⚙️ Project Workflow

### 🔹 1. Project Setup

* Install **Cookiecutter** to follow community-driven data science repository standards
* Structure a **Data Science + Flask** project
* Create a **GitHub repository** and upload project files

### 🔹 2. Model Serving with Flask on GCP

* Create a **Google Cloud Platform (GCP)** account
* Launch a server on **Google Compute Engine**
* Configure and run a Flask server
* Open **Firewall rules** to allow HTTP requests
* Serve your ML model on a remote server

### 🔹 3. Containerization with Docker

* Write a `Dockerfile`
* Configure **environment variables** in Docker
* Build Docker containers
* Push images to **Google Container Registry**
* Deploy containers to **Google Cloud Run**

### 🔹 4. CI/CD with GitHub Actions

* Create a **GitHub Actions YAML pipeline**
* Integrate with **Google Cloud Run**
* Create and configure a **Service Account**
* Store secrets in **GitHub Actions**
* Enable **continuous delivery pipeline** for automatic deployments

---

## 📁 Project Structure

```
📦 mlops-deploy
│
├── app/                  # Flask application
│   ├── main.py           # API and model serving
│   ├── model.pkl         # Serialized ML model
│   └── requirements.txt  # Dependencies
│
├── Dockerfile            # Docker container definition
├── .github/workflows/    # GitHub Actions CI/CD pipelines
│   └── deploy.yaml
├── README.md             # This file
└── cookiecutter.json     # Project template definition
```

---

## 📊 Technologies & Tools

* **Python 3.9+**
* **Flask** → API framework
* **Google Cloud Platform (GCP)** → Compute Engine, Container Registry, Cloud Run
* **Docker** → Containerization
* **GitHub Actions** → CI/CD pipeline
* **Cookiecutter** → Project structuring

---

## 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yourusername/mlops-deploy.git
cd mlops-deploy
```

2. Install dependencies:

```bash
pip install -r app/requirements.txt
```

3. Run the Flask app locally:

```bash
python app/main.py
```

4. Build and run with Docker:

```bash
docker build -t mlops-deploy .
docker run -p 5000:5000 mlops-deploy
```

5. Deploy to **Google Cloud Run** with GitHub Actions (automatic after push).

---

## ✅ Results

* Built a **production-ready ML API** with Flask
* Deployed models on **Google Compute Engine** and **Cloud Run**
* Containerized applications with **Docker**
* Automated deployments using **GitHub Actions CI/CD pipeline**

---

## 🏢 About Nowa Analytics

**Nowa Analytics** is a consultancy specialized in **data analytics, AI, and MLOps**. We help companies transform models into production systems through **cloud solutions, automation, and scalable deployment pipelines**.

📍 São Paulo | Madrid | London
🌐 [nowaanalytics.com](http://nowaanalytics.com) *(replace with actual site if available)*

---

## 📬 Contact

For consulting services or project inquiries:

* 📧 [contact@nowaanalytics.com](mailto:contact@nowaanalytics.com)
* 💼 LinkedIn: [Nowa Analytics](https://linkedin.com/company/nowaanalytics)

