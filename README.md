<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,10,30&height=180&section=header&text=Vihanga%20Piyumal&fontSize=42&fontColor=ffffff&animation=twinkle&desc=Full-Stack%20%26%20AI%20Developer&descSize=18&descAlignY=65" alt="Header" />

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00F0FF&center=true&vCenter=true&width=620&lines=Full-Stack+%26+AI+Developer;Fine-tuning+LLMs+with+QLoRA;Building+AI-powered+real-time+systems;Undergraduate+%40+SLIIT)](https://github.com/Renzer21)

<a href="mailto:piumal89001@gmail.com"><img src="https://img.shields.io/badge/Email-piumal89001%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://www.facebook.com/vihanga.piyumal.58/"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"/></a>
<a href="https://www.instagram.com/vihaga_piyumal/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>
<img src="https://komarev.com/ghpvc/?username=Renzer21&color=blueviolet&style=for-the-badge&label=Profile+Views" alt="Profile Views"/>

</div>

---

## 👨‍💻 About Me

I'm a BSc (Hons) Information Technology undergraduate at **SLIIT**, focused on **AI-powered real-time systems** and high-performance applications. I enjoy taking a model from a notebook to a working web product: fine-tuning it, measuring it honestly, and wiring it into a real interface.

- 🔭 Currently working on an **AI-powered student monitoring and support system** (Qwen2.5 + LoRA/QLoRA, FastAPI, React)
- 🧠 Interested in LLM fine-tuning, evaluation, and computer vision
- 🌱 Learning: production deployment of small language models, rigorous model evaluation
- 📫 Reach me: **piumal89001@gmail.com**

---

## 🛠️ Tech Stack

**Languages**

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**Backend & Databases**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Qwen](https://img.shields.io/badge/Qwen-LoRA%20%2F%20QLoRA-6F42C1?style=for-the-badge)

**Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=for-the-badge&logo=blender&logoColor=white)

---

## 🚀 Featured Project

### 🎓 AI-Powered Student Monitoring and Support System
*Research project R26-IT-113 · SLIIT*

A teacher-support platform for Grades 3 to 5 mathematics. My component combines two fine-tuned language-model pipelines with a working web integration:

| Component | What it does | Tech |
|---|---|---|
| **Student feedback analysis** | Predicts structured weakness labels and a short reason from a lesson guide and student comment | Qwen2.5-3B-Instruct, 4-bit QLoRA |
| **MCQ question generator** | Generates grade, topic and difficulty-controlled maths questions, checked by an independent solver | Qwen2.5-Math-1.5B-Instruct, LoRA |
| **Website integration** | Personalised starting paper, lesson video while generating, lesson-grounded learning assistant | Ollama (qwen2.5:3b), web app |

**Evaluation, reported honestly:** 99.44% exact label-set accuracy on a rule-generated feedback test set (vs 15.83% / 27.50% for TF-IDF Logistic Regression / Linear SVM baselines); 70.37% of freshly generated questions mathematically correct under an independent solver.

`Python` `PyTorch` `Transformers` `PEFT` `bitsandbytes` `scikit-learn` `Ollama`

> 🔗 Repository link: _add your repo URL here_

---

## 📊 GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Renzer21&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Stats" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Renzer21&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Renzer21&theme=tokyonight&hide_border=true" alt="Streak" />

</div>

---

## 🎯 Currently Focused On

- Measuring models properly: baselines, held-out tests, independent answer checking
- Making small LLMs fast and safe enough for real classroom use
- Building real-time, high-performance applications

---

## 🤝 Let's Connect

I'm open to internships, collaborations and AI / full-stack projects. Drop me an email or a message.

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,10,30&height=100&section=footer)

</div>
