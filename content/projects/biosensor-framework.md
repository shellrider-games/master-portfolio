---
title: "Framework for collecting biometric data in VR devices"
kicker: "Master's thesis · XR"
summary: "A framework to collect multimodal biosensor data on VR devices used in my Master thesis \"Multimodal collection of biometric data related to stress in XR interventions\""
image: "/images/masterthesisproject.png"
banner: "/images/projects/biosensor-framework/1.jpg"   # detail-page image (falls back to image)
# video: "https://youtu.be/XXXXXXXXXXX"                         # optional; overrides banner (16:9)
weight: 1
badges: ["VR", "Biosensors", "Research"]
tools: ["Unity", "Android", "OpenXR"]
role: "Researcher & Developer"
teamMembers: "Georg Becker"
# team: true   # team project → "What we built"
duration: "4 months"
when: "2026"
challenge: "There was no readily accessible, well-documented framework for collecting biometric data in standalone VR applications. I set out to address this gap by developing a framework and evaluating its feasibility. The technical challenge was to connect a Polar H10 heart rate monitor to a Meta Quest 3 headset, collect ECG data, head-movement data, and voice recordings, and store them locally on the headset. I also needed to design an evaluation to assess whether users could operate the solution independently."
approach: "A custom Kotlin library streams Polar H10 data over Bluetooth to a standalone Unity VR app, which records ECG, heart rate, head movement, and voice. Timestamps and session-phase markers align the physiological and movement data, while all recordings are stored locally on the headset in a compressed session archive."
result: "The framework was used in my Master thesis and is a valuable tool for research projects in the future that need on device biometric data collection."
# achievements:
#   - "TODO: award / showcase — you can include [links](https://example.com)"
learned: "This was my first project in which I had to use Android native libraries within my Unity VR application. Further, I learned how to handle Bluetooth connection to additional devices on the Meta Quest 3 headset."
links: []
gallery: []
# gallery:
#   - "/images/projects/biosensor-framework/01.jpg"
large: true
showInHome: true
---

For my master thesis "Multimodal collection of biometric data related to stress in XR interventions" I developed a reusable framework to facilitate the collection of ECG, head movement and voice recordings in standalone VR applications. Additionally, I implemented a version of the Stroop Room, a 360° adaptation of the Stroop color–word test, and collected participant data during the experience to evaluate my framework.
