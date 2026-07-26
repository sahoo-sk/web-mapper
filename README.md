# 🛰️ WebRecon Mapper (GUI)
  Visual attack surface mapping and automated web reconnaissance app for security teams, red teamers, and bug hunters.

## 📌 Overview
  WebRecon Mapper is an interactive desktop application that transforms raw web crawling and endpoint discovery into clear, actionable visual maps. Instead of digging through endless text logs, WebRecon Mapper gives you a dynamic, node-based overview of a target's web architecture, hidden endpoints, parameters, and technologies.

  Designed for penetration testers, security researchers, and bug bounty hunters who want speed without sacrificing visual clarity.

## ✨ Key Features
* 🗺️ **Interactive Node Map:** Drag, expand, and inspect web endpoints, subdomains, and directories in real time.

* 🔍 **Automated Directory & Endpoint Crawling:** High-speed, multi-threaded engine to discover hidden paths and legacy assets.

* 📌 **Parameter & API Route Extractor:** Click on any node to view discovered GET/POST parameters, headers, and API routes.

* ⚡ **Built-in Fingerprinting:** Instant visibility into tech stacks, CMS versions, and server headers per target node.

* 🎯 **One-Click Scope Filtering:** Easily filter out out-of-scope third-party domains, static assets (images/CSS), or specific status codes.

* 🔌 **Proxy & Traffic Control:** Route all app traffic through Burp Suite or OWASP ZAP with built-in rate-limiting controls.

* 💾 **Workspace & Project Management:** Save target maps as project files (.wrm) and export visual graphs (PNG/SVG) or raw data (JSON/CSV).

## 🖥️ UI Highlights
* **Tree & Graph Views:** Toggle between a clean visual graph and a structured folder tree.

* **Inspector Panel:** Quick-view HTTP requests/responses, parameters, and headers for selected endpoints.

* **Filter Bar:** Instant live filtering by status code (200, 403, 500), file extension, or keywords.

## 🛠️ Getting Started
Prerequisites
* Node.js (v18+) / Python (3.10+) (Adjust based on your backend)
* Git

## Installation
```

# Clone the repository
git clone https://github.com/your-username/webrecon-mapper-gui.git

# Navigate to project directory
cd webrecon-mapper-gui

# Install dependencies
npm install  # or: pip install -r requirements.txt

# Launch the app
npm start    # or: python main.py

```

## 🚀 Quick Workflow
* **New Project:** Open the app and click New Recon Session.
* **Set Target & Scope:** Enter your target URL, adjust thread count, and add out-of-scope regex rules.
* **Start Mapping:** Hit Start Crawl. Watch the visual graph build automatically as endpoints are discovered.
* **Inspect & Export:** Click on nodes to investigate inputs, filter for interesting status codes, and export your map as an HTML report or SVG graph.

⚠️ Legal Disclaimer
**IMPORTANT:** _WebRecon Mapper is intended strictly for authorized security assessments, bug bounty programs with explicit scope, and educational research. Unlawful targeting of unauthorized web applications is illegal. The developers assume no liability for misuse._
