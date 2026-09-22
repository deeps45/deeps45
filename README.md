<table>
<tr>
<td width="150" align="center">
<img src="./assets/profile.jpg" width="120" height="120" style="border-radius:50%;object-fit:cover" alt="Siva Sai Deepank Manoj" />
</td>
<td>

# Siva Sai Deepank Manoj

**I build AI agents that can actually do things, not just talk about them.**

MCS, Computer Science · Texas A&M University
[Email](mailto:deepanksiva@gmail.com) · [LinkedIn](https://www.linkedin.com/in/siva-sai-deepank-manoj-2802ab213/)

</td>
</tr>
</table>

Most of what's below started as "I wonder if I can get this to actually work" and turned into a real project. I like the part after the demo, when something breaks and you find out whether you actually built it right.

A few things I'm proud of:
- Got a drone anomaly detector to beat its baseline by 35.9%, using an architecture normally used for video prediction, not telemetry
- Killed processes mid-run on a live Kafka pipeline to check it actually recovers, instead of assuming it would
- Built an LLM agent that learns a UI once by watching the screen, then never needs the model again to repeat the task

---

### Skills

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

### Featured Projects

**[Computer-Use Automation System](https://github.com/deeps45/computer-use-automation)**
I taught an LLM to operate a banking-style web app it had never seen before: log in, look something up, fill out a form, just by watching screenshots and clicking around like a person would. Once it succeeds, the run gets saved as a replayable script that no longer needs the model, and the whole thing can pause and hand control to a human mid-task if it gets stuck.
`TypeScript` `Playwright` `Claude Sonnet 4.5`

**[Groundline — Agentic RAG Knowledge Assistant](https://github.com/deeps45/agentic-rag-assistant)**
A RAG assistant I built to stop making things up. It only answers with what it can point to in the source document and says "I don't know" instead of guessing. Hybrid search (keyword + embeddings) plus a re-ranking pass so the sources it cites are actually relevant, not just similar-sounding.
`Python` `LangGraph` `LangChain` `FAISS` `React`

**[Distributed Event Processing Platform](https://github.com/deeps45/distributed-event-processing-platform)**
Kafka, Redis, Postgres, all the pieces you'd expect from an event pipeline. The part I actually cared about was proving it survives failure, so I wrote chaos tests that kill a consumer mid-run and check it recovers, instead of just hoping it would.
`Python` `Kafka` `FastAPI` `Redis` `Postgres`

**[Drone Telemetry Anomaly Detection (JEPA)](https://github.com/deeps45/Drone-Anomaly-Detection-JEPA)** — team project, CSCE 625
Trained a model to flag abnormal drone telemetry after only ever seeing normal flights, no labeled attacks. Beat the baseline by 35.9%. Built with Yaswanth Reddy Yaradoddi and Ubaid Khan Mohammed.
`Python` `JEPA` `PyTorch`

**[PokeRL — Playing Pokémon Red with Deep RL](https://github.com/deeps45/PokemonRL)**
Wanted to see if I could train an agent to beat Pokémon Red. Broke the game into small learnable pieces (leave the house, find the first battle, win it) instead of throwing PPO at the whole game at once.
`Python` `PyTorch` `Stable-Baselines3` `PyBoy`

### GitHub Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=deeps45&hide_border=true&theme=default" alt="GitHub streak stats" />
</p>
