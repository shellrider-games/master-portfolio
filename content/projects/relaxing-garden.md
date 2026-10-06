---
title: "Relaxing Garden"
kicker: "Hackathon, mixed-reality biofeedback"
summary: "A mixed-reality garden that grows as you relax. Biofeedback from your heart drives a personal AR garden in real time. Built at the SensAI Hack 2025 in Barcelona, Runner-Up in the AI with Camera Access by Meta category."
image: "/images/relaxinggarden.png"
video: "https://www.youtube.com/watch?v=NaNxa7DFRBo&embeds_referring_euri=https%3A%2F%2Fdevpost.com%2F"
weight: 4
badges: ["Unity", "Meta Quest", "Camera Access API"]
tools: ["Unity", "Python", "Flask", "Meta Quest"]
role: "Camera Access API integration, leaf-shape detection pipeline (images sent to a local server for ML), growth shaders and procedural plant growth, and working with HR and HRV data"
teamMembers: "Tobias Furtlehner, Laura Cesar, Sofiia-Khrystyna Borysiuk, Georg Becker"
team: true
duration: "Hackathon (SensAI Hack 2025, Barcelona)"
when: "2025"
challenge: "A hackathon weekend with a brand-new, barely documented camera API, unfamiliar ML tooling and live biofeedback. We had to get leaf detection, a Flask data pipeline and a calm AR experience working under real time pressure."
approach: "Relaxing Garden turns heart rate and heart rate variability into a living AR garden. We connected a heart rate monitor and calculated a continuous relaxation score, streamed it through a lightweight Flask API into a Unity AR environment, and let custom growth shaders and procedural generation make the garden flourish as the user relaxes. Users can draw their own leaf on paper, which the system detects and grows into their plants."
contribution: "I worked with the then newly released Camera Access API and sent the captured images to our local server that ran the machine learning. I also implemented the shaders and how the plants grow. It was my first time working with HR and HRV data, which also connects to my master's thesis project on collecting biosensor data in VR."
result: "A working mixed-reality biofeedback prototype built and demoed over the hackathon weekend."
achievements:
  - "Runner-Up, AI with Camera Access by Meta, SensAI Hack 2025 (Barcelona)"
learned: "It was a great experience to compete with so many talented developers from all over the world, and I had to learn how to work under a lot of pressure with technologies I was not yet familiar with."
links:
  - icon: fa-solid fa-trophy
    url: "https://devpost.com/software/relaxing-garden"
gallery: []
showInHome: true
---

Relaxing Garden is a mixed-reality biofeedback experience built at the SensAI Hack 2025 in Barcelona. Instead of charts and numbers, it turns your heart rate and heart rate variability into a garden that grows as you relax and slows when your arousal rises.
