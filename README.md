# Bioinformatics Toolkit (v1)

A lightweight, open-source bioinformatics web app built using Flask, AIML, and custom Python logic.  
This project demonstrates core backend development skills, practical application of AI/ML logic (via AIML), and integration of bioinformatics tooling in a cloud-ready architecture.

---

## 🧬 Project Overview

This app simulates a conversational interface designed to assist with basic bioinformatics tasks such as:

- Uploading and parsing **FASTA** sequences
- Performing **sequence alignment**
- Interacting via a simple **AI chatbot interface** (AIML-based)
- Displaying aligned output in a human-readable form

Originally structured using **Flask + static HTML**, this version demonstrates full-stack logic before transitioning into a more modular, cloud-native architecture.

---

## 🧰 Tech Stack

| Layer        | Tech                     |
|--------------|--------------------------|
| Backend      | Flask (Python)           |
| Chat Logic   | AIML (Artificial Intelligence Markup Language) |
| Bio Sequence | BioPython                |
| UI           | HTML, minimal JavaScript |
| Deployment   | Docker-ready, EC2-compatible |

---

## ⚙️ Key Features

- 📁 Upload and parse FASTA files for DNA/RNA sequences
- 🧠 AI chatbot interface for triggering app functionality
- 🧮 Sequence alignment logic with alignment output
- 🐳 Docker support for containerized deployment
- 🔐 Prepared for secure API refactoring in v2

---

## 🔭 What's Next (Planned in v2)

The next iteration of this app (`bioinformatics-v2`) will be:
- Rebuilt with a **Vue.js frontend** (hosted via S3 + CloudFront)
- Refactored into a **modular Flask API backend** (hosted on EC2 or containerized via ECS)
- Deployed using **Terraform** for full Infrastructure-as-Code
- Integrated with modern CI/CD pipelines

---

## 🚀 Live Demo

_(coming soon — hosted version will be deployed via AWS CloudFront + EC2)_

---

## 👨‍💻 About the Developer

This project is developed by a Tier 2 support engineer transitioning into cloud engineering and DevOps.  
I have 5+ years of real-world IT operations experience, formal AWS certifications, and hands-on development skills in Python, cloud infrastructure, and full-stack web systems.

---

## 📄 License

Apache License 2.0
