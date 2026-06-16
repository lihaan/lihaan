## Hello World! 🌎 
#### I'm Li Han, a Data Scientist / Machine Learning Engineer with close to 2 years of industry experience 🧑‍💼.
My 9-5 typically consists of fine-tuning small models and classifiers for specific business needs, while also designing and building scalable pipelines centered around bulk LLM inference via API providers.

I mostly waste what limited leisure time I have by tinkering with mechanical keyboards (sofle split), PC hardware (dual 3090s), and other silly coding projects (see below). Feel free to explore my repositories and discover their niche use cases and tragic backstories 😭.
<p align="center">
  <a href="https://github.com/lihaan" target="_blank"><img alt="GitHub" src="https://img.shields.io/badge/-@lihaan-181717?style=flat-square&logo=GitHub&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/lihanong" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/-Ong%20Li%20Han-0077B5?style=flat-square&logo=Linkedin&logoColor=white"></a>
</p>

## Repo Highlights
### Fortress 🏰 <img src="https://skillicons.dev/icons?i=fastapi" width="18px" />
```
Control your PC's sleep schedule (or lack thereof) via on-demand REST API requests.
```
Lightweight HTTP service built as an exercise in **🤖 Agentic Coding 🚀 (built with Claude Code)**. It interacts with the native Windows `SetThreadExecutionState` API via concurrency-safe "stay-awake locks" to manage OS power states. Ideal for home automation tasks.

Also features: state persistence across service restarts, user-configurable stay-awake duration, decoupled client-server architecture

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=lihaan&repo=fortress-app&show_icons=true&theme=vue)](https://github.com/lihaan/Fortress)

### TeleAssist 🤖
```
Harness the power of Generative AI to automatically reply to your Telegram chats!
```
An asynchronous HTTP server and a Telegram client bot:
1) **TeleAssist-Web**: Backend Quart application that batches messages received from peers, before orchestrating prompts through LLMs to deliver a response
3) **TeleAssist-Bot**: User-facing Telegram bot to allow the owner to silence notifications, enable the LLM assistant, as well as provide a frontend for users to interact with the LLM directly

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=lihaan&repo=TeleAssist-Web&show_icons=true&theme=vue)](https://github.com/lihaan/TeleAssist-Web)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=lihaan&repo=TeleAssist-Bot&show_icons=true&theme=vue)](https://github.com/lihaan/TeleAssist-Bot)

### docktainer-backup 💾 <img src="https://skillicons.dev/icons?i=docker" width="18px" />
```
Never let a Docker container hold you (or your hard disk) hostage!
```
Daily backups of user-configurable files/directories within live Docker containers, with additional features such as automatic pruning and real-time updates delivered via Telegram notifications

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=lihaan&repo=docktainer-backup&show_icons=true&theme=vue)](https://github.com/lihaan/docktainer-backup)


## Tech Stack 💻

#### 🧠 Data Science & Core ML
* **Frameworks & Libraries:** PyTorch, scikit-learn, Hugging Face Transformers
* **MLOps & Enterprise Platform:** Google Vertex AI, MLflow, Weights & Biases
* **Data Processing:** PySpark (Big Data processing), Apache Flink (Streaming), Pandas, NumPy

#### ⚙️ Software & Data Engineering
* **Languages:** Python, Scala, JavaScript, Java, SQL
* **Backend Engines:** FastAPI, Quart (Async Flask), Flask, Node.js
* **Data Stores:** PostgreSQL, MySQL, MongoDB, Redis

#### 🛠️ Infrastructure & Modern Tools
* **DevOps / Cloud:** Docker, AWS, GCP, GitHub Actions (CI/CD), WSL
* **UI & Frontend prototyping:** Streamlit, React, Figma

<br>

<details>
  <summary align="center">📊 (Meaningless) GitHub Stats:</summary>
  <!-- ![](https://github-readme-stats.vercel.app/api?username=lihaan&theme=vue-dark&hide_border=false&include_all_commits=true&count_private=true)<br/> -->
  <p align="center">
  <img alt = "GitHub Contribution Stats" src="https://github-readme-streak-stats.herokuapp.com/?user=lihaan&theme=vue-dark&hide_border=true" />
    <br>
  <img alt = "Github Language Breakdown Stats" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lihaan&theme=vue-dark&hide_border=true&include_all_commits=false&count_private=false&layout=compact" />
  </p>
</details>




<!--
**lihaan/lihaan** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...

- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
