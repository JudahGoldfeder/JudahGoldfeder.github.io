---
title: "Rapidly Custimizable HVAC Simulator for Reinforcement Learning"
excerpt: "A Lightweight Calibrated Simulation Enabling Efficient Offline Learning for Optimal Control of Real Buildings, in collaboration with Google, Fall 2023.<br/><img src='/images/simulator.jpg'>"


collection: portfolio
---

<br/><img src='/images/simulator.jpg'>"

Modern commercial Heating, Ventilation, and Air Conditioning (HVAC) devices form a complex and interconnected thermodynamic system with the building and outside weather conditions, and current setpoint control policies are not fully optimized for minimizing energy use and carbon emission. Given a suitable training environment, a Reinforcement Learning (RL) model is able to improve upon these policies, but training such a model, especially in a way that scales to thousands of buildings, presents many real world challenges. We propose a novel simulation-based approach, where a customized simulator is used to train the agent for each building. Our open-source simulator1 is lightweight and calibrated via telemetry from the building to reach a higher level of fidelity. On a two-story, 68,000 square foot building, with 127 devices, we were able to calibrate our simulator to have just over half a degree of drift from the real world over a six-hour interval. This approach is an important step toward having a real-world RL control system that can be scaled to many buildings, allowing for greater efficiency and resulting in reduced energy consumption and carbon emissions.

For more information, see the [paper](https://dl.acm.org/doi/fullHtml/10.1145/3600100.3625682), or watch our talk at RLEM (starts at 2 hour mark):

<iframe width="928" height="522" src="https://www.youtube.com/embed/s_Yq5XhKWLM" title="RLEM23: The 4th ACM Workshop on Reinforcement Learning for Energy Management in Buildings and Cities" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

