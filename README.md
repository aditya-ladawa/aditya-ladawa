# Aditya Ladawa

I build AI applications that connect models to the work around them: data pipelines, APIs, interfaces, evaluation and deployment.

I'm an M.Sc. Data Science student at TU Braunschweig, based in Braunschweig, Germany. My work spans AI agents and RAG, forecasting, computer vision, and Python automation. I enjoy taking an unfamiliar problem apart, sketching a rough architecture, and getting the components working together.

[LinkedIn](https://www.linkedin.com/in/aditya-ladawa/) · [Projects](https://github.com/aditya-ladawa?tab=repositories) · [infra.peter](https://www.instagram.com/infra.peter/)

## Start here

### [PeCal Pulse](https://github.com/aditya-ladawa/pecal-pulse)
First place at Perschmann Calibration's Hack The Lab, built with a team of four.

A voice-enabled sales workspace that combines customer segmentation, activity prediction and calibration-volume forecasts with an assistant that can filter accounts, open customer details, create charts and save follow-up drafts. Next.js and TypeScript frontend, FastAPI backend, scikit-learn analytics, LangGraph orchestration and LiveKit voice.

The historical activity model reached a held-out ROC AUC of 0.81. For volume prediction, a simple historical baseline outperformed more complex candidates on validation MAE. The public repository runs on synthetic demo data; its demo is separate from the private historical evaluation.

### [infra.peter](https://github.com/aditya-ladawa/infra_peter)
One of my favourite personal projects. I automated research, scripting, voice generation and video assembly with Python, LangChain/LangGraph and ffmpeg, then used the pipeline to grow an Instagram channel to 17,000 followers and 1M views in three months.

Production time fell from six hours to about 20 minutes at €0.20 per video. The pipeline produced 100 videos, of which I posted 86. [Watch the channel](https://www.instagram.com/infra.peter/).

### [Buena property context engine](https://github.com/aditya-ladawa/buena-property-context-engine)
A source-backed context engine for property management, built at Big Berlin Hack. It links thousands of mixed-source documents and 6,000+ emails into a living `Context.md` map with evidence pointers, incremental updates and protected human corrections. The project led to an interview opportunity at Buena.

### [KI-PV-Assistent](https://github.com/aditya-ladawa/KI-Energie-Hackathon-Project)
A renewable-energy planning prototype combining source-grounded regulations, building/site data and deterministic technical assessment with LLM Q&A. Built with Next.js, TypeScript and FastAPI, with geospatial integration, roof-potential analysis and bilingual DE/EN responses. Covers solar, storage, heat pumps and wallboxes. [Video walkthrough](https://youtu.be/l-oEOvdLlZI).

### [Brand presence detection](https://github.com/aditya-ladawa/brand_presence_prediction)
Fine-tuned YOLOv11-Large on a manually annotated 71-logo dataset for sponsorship analysis in football broadcasts. Achieved 96% precision at 17-21 FPS on an RTX 4060, then tracked exposure duration, frequency and screen position.

### [Workout monitoring robot](https://github.com/aditya-ladawa/Workout_monitoring_robot)
My team-based bachelor's thesis combined pose estimation, navigation and interactive exercise guidance on Raspberry Pi and Arduino. I mainly worked on real-time pose estimation, autonomous navigation, action recognition and posture correction. The system ran at 10 FPS with 100 ms feedback latency. [Published research paper](https://github.com/aditya-ladawa/Workout_monitoring_robot/blob/main/A-RESEARCH-PAPER_Workout_monitoring_robot.pdf).

## Research and production work

At [Brandl Nutrition](https://brandl-nutrition.de/pages/ueber-uns), I built forecasting and inventory-planning systems for 60+ products. Daily AWS runs processed 111,000 records and fed Looker Studio dashboards, replacing weekly manual updates. I also built an n8n email agent using Shopify/DHL APIs and custom Claude Skills, plus internal Slack bots with Composio and a custom MCP adapter.

At [SciBiome, TU Braunschweig](https://scibiome.tu-bs.de/), I built the frontend, backend and LLM orchestration for literature screening and PDF-data extraction. We evaluated a systematic-review agent on 900 annotated papers across four LLMs; the best model reached 100% sensitivity on that benchmark. My separate research project compared a context-engineered deep agent with ReAct and multi-agent designs, measuring report quality, citation grounding, runtime and cost. The work was accepted for an oral presentation at GCB 2026.

At [NOAVIA](https://noavia.de/), I built Python document-intelligence and market-intelligence systems using OCR, LLMs, RAG and source traceability. Earlier, at [TECHR](https://techr.co.in/), I worked on CycleGAN MRI translation and image enhancement with PyTorch, TensorFlow and OpenCV.

## Experiments and learning

- [CEFLANN](https://github.com/aditya-ladawa/CEFLANN): implemented a trading neural network from two research papers, including a custom TensorFlow layer and regularized Moore-Penrose weight estimation.
- [SynthMotion](https://github.com/aditya-ladawa/Hera_hack_deep_explainer): a research-to-video pipeline with narration, motion graphics and Python media assembly. [Project page](https://aditya-ladawa.github.io/Hera_hack_deep_explainer/).
- [TensorTonic Solutions](https://github.com/aditya-ladawa/TensorTonic-Solutions): my implementations of mathematical, data science, ML and deep-learning exercises.
- Pattern Recognition Lab at TU Braunschweig: SVMs, CNNs, GANs, time-series anomaly detection and speech denoising.
- [Ideological polarization seminar](https://www.linkedin.com/posts/aditya-ladawa_how-do-people-use-the-same-words-to-mean-ugcPost-7373759125823852544-OnsG): R/Python analysis of semantic graphs, stance and engagement in election discourse.

I regularly attend hackathons to try unfamiliar tools and bring what I learn into everyday work. Alongside PeCal Pulse's first place, my teams placed second with CoNurse at HealthHack and Fit Happens at 42 Wolfsburg.

## Tools I work with

Python, SQL, TypeScript, Next.js and FastAPI. LangChain/LangGraph, RAG and MCP for agent applications. PyTorch, TensorFlow, scikit-learn and OpenCV for ML. AWS, Docker, Git and n8n for deployment and automation; Looker Studio, Excel and Power BI for analysis and reporting.

In my free time, I learn system design, build small experiments, go to the gym and make music in FL Studio.
