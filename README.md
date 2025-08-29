
```markdown
# 🚀 Cloud-Native Labs: Docker, Knative & OpenShift Serverless

This repository contains hands-on labs, guides, and presentations for learning **Docker**, **Knative**, and **OpenShift Serverless**.  
It is organized into two main sections:

1. **Docker Basics to Advanced** – labs, presentations, networking, volumes, and registry exercises.  
2. **Knative & OpenShift Serverless** – serving, eventing, pipelines, and traffic management.  

---

## 📂 Repository Contents

### 🐳 Docker Labs & Guides

#### 📘 Presentations
- `Introduction to docker.pptx` – Beginner introduction to Docker.  
- `Docker Basics.pptx` – Core concepts and usage.  
- `Dockerfile.pptx` – Writing and using Dockerfiles.  
- `dockers.pptx` – Additional Docker slides.  

#### 🧪 Labs & PDFs
- `Lab1.pdf`, `Lab2.pdf`, `Lab3.pdf`, `Lab4.pdf` – Docker hands-on labs.  
- `Dockerfile.pdf` – External content on writing Dockerfiles.  
- `To build a pipeline for Dockerfile and Kubernetes in Jenkins.pdf` – CI/CD pipeline lab.  
- `To create a private Docker registry and push an image.pdf` – Working with a private registry.  
- `Push image to docker hub.pdf` – Publishing images.  
- `Map nfs share to container.pdf` – Storage integration.  
- `Volume map docker.pdf` – Volume mapping example.  
- `startupservice docker.pdf` – Startup service with Docker.  
- `container snapshot.pdf` – Container snapshotting.  

#### 📑 Networking & Volumes
- `docker host networking.txt` – Host networking mode.  
- `docker none network.txt` – None network mode.  
- `docker netwokr lab 2.txt`, `docker network lab 1.txt` – Networking labs.  
- `docker tmpfs.txt` – Using tmpfs with Docker.  
- `docker volumbe bind lab.txt` – Bind mount example.  
- `docker volume labs.txt` – Volume labs.  
- `docker volume assignment.docx` – Assignment on volumes.  

#### 📦 Compose, Swarm & Argo
- `compose lab.txt` – Docker Compose basics.  
- `dockercompose proj2.txt` – Docker Compose project.  
- `dockerswarmlabs.txt` – Docker Swarm labs.  
- `argo.txt` – Intro/notes on Argo.  

#### 🛠 Assignments
- `assingement on debug container.docx` – Debugging container exercise.  

---

### ☁️ Knative & OpenShift Serverless Labs

#### 📘 Guides
- `Create Api resource from cli.docx` – Create Knative resources via CLI.  
- `Event source api.docx` – Working with Knative Event Sources.  
- `Openshift developer sandbox.docx` – Using OpenShift Developer Sandbox.  
- `Ping source.docx` – Example of PingSource eventing.  
- `Serverless api.docx` – APIs for serverless workloads.  
- `Serverless service deployed by OpenShift Pipeline.docx` – Deployment with OpenShift Pipelines.  
- `Serving lab1.docx` – Knative Serving basics.  
- `kn cli serving.txt` – CLI reference for Serving.  
- `knserving traffic split.txt` – Traffic splitting between revisions.  
- `api-resource-event-lab.txt` – Event-driven API lab.  

#### 📑 Reference & Slides
- `Serverless.pptx` – Slide deck on Serverless.  
- `knative api server.pdf` – Reference on Knative API Server.  

---

## 🛠 Prerequisites
To follow the labs, ensure you have:
- **Docker** installed ([Get Docker](https://docs.docker.com/get-docker/)).  
- **OpenShift Developer Sandbox** account ([Sign up](https://developers.redhat.com/developer-sandbox)).  
- **Knative CLI (`kn`)** installed ([Install guide](https://knative.dev/docs/client/install-kn/)).  
- **kubectl / oc CLI** configured for your cluster.  

---

## 📘 Suggested Learning Path

### 🔹 Docker
1. Start with presentations (`Introduction to docker.pptx`, `Docker Basics.pptx`).  
2. Do core labs (`Lab1.pdf` → `Lab4.pdf`).  
3. Explore volumes & networking (`docker volume labs.txt`, `docker network lab 1.txt`).  
4. Work with registries & pipelines (`Push image to docker hub.pdf`, `To build a pipeline for Dockerfile and Kubernetes in Jenkins.pdf`).  
5. Advanced topics (`dockerswarmlabs.txt`, `argo.txt`).  

### 🔹 Knative & OpenShift
1. Setup OpenShift Developer Sandbox.  
2. Learn Serving basics (`Serving lab1.docx`, `kn cli serving.txt`).  
3. Work with Event Sources (`Event source api.docx`, `Ping source.docx`).  
4. Deploy via Pipelines.  
5. Experiment with traffic splitting.  

---


---
```
