# Aditya Ladawa

I write Python, build AI applications and usually end up working on the frontend too. M.Sc. Data Science at TU Braunschweig. Previously at Brandl Nutrition (sports nutrition), SciBiome (biomedical data science) and NOAVIA (AI consulting).

My favourite personal project is infra.peter, an Instagram channel explaining computing and AI through short videos. I connected research agents, narration and Python video processing, then used the pipeline to grow [infra.peter](https://www.instagram.com/infra.peter/) to 17K followers and 1M views. The [code](https://github.com/aditya-ladawa/infra_peter) includes the parts between the LLM response and the published video.

## A few decisions you can inspect

[PeCal Pulse](https://github.com/aditya-ladawa/pecal-pulse) helps a calibration company's sales team decide which customers to contact about upcoming service needs. Our team built forecasts and a voice assistant that can filter accounts, show charts and prepare follow-up drafts. For predicting service volume, a simple historical baseline beat the more complex models. Predicting whether a customer would return was a separate task: logistic regression reached 0.81 ROC AUC on held-out historical data. The public demo uses synthetic data.

The [Buena context engine](https://github.com/aditya-ladawa/buena-property-context-engine) helps AI agents answer property-management questions when the relevant information is scattered across emails, invoices and other documents. We organized it into a continuously updated record for each property, with links back to the original evidence. New documents update that record without overwriting corrections a person has made.

[KI-PV-Assistent](https://github.com/aditya-ladawa/KI-Energie-Hackathon-Project) helps assess solar, storage, heat-pump and EV-charging projects using building data and relevant regulations. Technical calculations and rule retrieval run as defined code rather than being left to the language model. The model answers questions with citations to the sources.

## How I work

I sketch the architecture, build the components and test their integration early. At Brandl, that became a daily AWS pipeline for deciding when and how much inventory to order across 60+ products. At SciBiome, I built an application that helps scientists screen papers and extract evidence from PDFs, covering the frontend, backend and language-model orchestration. In a separate research project, I compared three ways of organizing agents for multi-hour research tasks, measuring report quality and citation accuracy alongside runtime and cost.

I still implement things to understand them: [a TensorFlow layer for trading signals, implemented from research papers](https://github.com/aditya-ladawa/CEFLANN), [ML exercises](https://github.com/aditya-ladawa/TensorTonic-Solutions), and [a robot that monitors exercise posture and gives feedback](https://github.com/aditya-ladawa/Workout_monitoring_robot). I go to a lot of hackathons because I get to try something unfamiliar and take it into my next project.

[LinkedIn](https://www.linkedin.com/in/aditya-ladawa/) · [Repositories](https://github.com/aditya-ladawa?tab=repositories)
