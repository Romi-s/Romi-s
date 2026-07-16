# Romina Saljooghian

**AI &amp; Automation Engineer**  
M.Sc. Automation &amp; Control Engineering — Politecnico di Milano (107/110, 2026)  
Milan, Italy · [Email](mailto:romina.saljooghian@mail.polimi.it) · [LinkedIn](https://www.linkedin.com/in/romina-saljooghian-08b3681b8/) · [**Portfolio →**](https://romi-s.github.io)

---

Control engineer by training, machine-learning practitioner by choice. I work where **control, perception, and learning** meet, from model predictive control on real robotic hardware to deep-learning pipelines and agentic AI systems.

Current flagship: [**lang2action**](https://github.com/Romi-s/lang2action), a language-to-action robotic agent. It grew out of my thesis (*Semantic Characterization of Robotic Environments*, an open-vocabulary scene graph system built with CLIP, SAM, Grounding DINO, and RAM at MERLIN Lab, Politecnico di Milano) and now spans an **MCP server**, a **LangGraph planning agent with a hallucination guard**, PyBullet execution, and a **ROS2 + C++** control node, all built eval-first.

Open to **AI / ML Engineering** and **Robotics / Automation** roles. My control background is the edge: I treat agents like control systems, with measured behavior, safety envelopes, and honest failure modes.

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat&logo=mathworks&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)

**ML / Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)

**LLM &amp; Agentic AI**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_server-6B46C1?style=flat&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FFCA28?style=flat&logoColor=black)
![RAG](https://img.shields.io/badge/RAG-0EA5E9?style=flat&logoColor=white)

**Backend &amp; MLOps**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Control &amp; Robotics**

![Simulink](https://img.shields.io/badge/Simulink-0076A8?style=flat&logo=mathworks&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat&logo=ros&logoColor=white)
![PyBullet](https://img.shields.io/badge/PyBullet-2E7D32?style=flat&logoColor=white)
![MPC](https://img.shields.io/badge/MPC-555?style=flat&logoColor=white)
![LQR](https://img.shields.io/badge/LQR-555?style=flat&logoColor=white)
![Kalman](https://img.shields.io/badge/Kalman_Filter-555?style=flat&logoColor=white)

---

## Featured Projects

| Repository | Description | Stack |
|---|---|---|
| [lang2action](https://github.com/Romi-s/lang2action) ⭐ | **Language-to-action robotic agent**: tell it *"stack the red cube on the blue box"* and it perceives the scene as a graph (via a custom **MCP server**), plans with a LangGraph agent, refuses when the object isn't there (hallucination guard), and executes pick-and-place in PyBullet — plus a **ROS2 + C++** action-server controller. Eval-first: 0.95 grounding / 0.95 task success / 1.00 refusal; closed a measured sim-to-real perception gap from 12% to 72% recall **without training**; 47 tests | Python · C++ · LangGraph · MCP · PyBullet · ROS2 · Docker |
| [jobhunt-agent](https://github.com/Romi-s/jobhunt-agent) | Agentic job-application system I use daily: an event-driven watcher orchestrating headless LLM workflows over a Markdown knowledge base — batched JD scoring, auto-tailored CVs, outreach queue with human-in-the-loop follow-ups, and a **git working tree as the review gate** | PowerShell · Claude Code · LLM agents · Obsidian |
| [Lightweight-SGG](https://github.com/Romi-s/Lightweight-SGG) | CPU-only service detecting objects and their spatial relations. Shows that bounding-box geometry plus a class prior beats CLIP image-text similarity for spatial predicates (0.79 zero-shot, 0.91 with a tiny trained head). FastAPI + Docker + CI, 21 tests, [live Gradio demo](https://romi-s-light-sgg-demo.hf.space/) | Python · PyTorch · YOLO-World · FastAPI · Docker |
| [Compliance-RAG-Agent](https://github.com/Romi-s/Compliance-RAG-Agent) | RAG backend for regulatory document Q&A. Hybrid retrieval (ChromaDB + BM25 + Reciprocal Rank Fusion), 4-node LangGraph agentic pipeline with source citations, 21 tests, deployed on [GCP Cloud Run](https://compliance-rag-agent-kwxekadtlq-ew.a.run.app/) | Python · FastAPI · LangGraph · ChromaDB · OpenAI API |
| [Visual-QA-Agent](https://github.com/Romi-s/Visual-QA-Agent) | Agentic backend answering visual questions about images & PDFs via a 4-node LangGraph pipeline with dual VLM support (Claude, GPT-4o) and conditional error routing | Python · FastAPI · LangGraph · Anthropic API · OpenAI API |
| [Plant-Leaf-Health-Classification](https://github.com/Romi-s/Plant-Leaf-Health-Classification) | 5-model ensemble CNN (86% accuracy) for plant disease detection with Grad-CAM explainability, async FastAPI inference, and MLflow tracking | Python · TensorFlow · FastAPI · MLflow · pytest |

**Also:** a *Scene Graph Generation* MSc thesis (4 chained foundation models, 6× over an end-to-end baseline; code under MERLIN Lab), *Time-Series Forecasting* (6+ architectures on 48K series, test MSE 0.01), and control/robotics work on real hardware: a *2-DOF pantograph CNC* (9 controllers on Quanser plants; MPC at 0.26 s settling) and *networked control of a vehicle platoon*. More on the [portfolio](https://romi-s.github.io).

---

## GitHub Stats

![Romina's GitHub stats](https://github-readme-stats.vercel.app/api?username=Romi-s&show_icons=true&hide_border=true&theme=tokyonight&hide=stars)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Romi-s&layout=compact&hide_border=true&theme=tokyonight)
