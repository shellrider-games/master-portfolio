---
title: "Historia Virtualis"
kicker: "Co-located multiplayer VR"
summary: "A multiplayer, colocated VR experience where three players solve puzzles together to bake a bread in ancient Roman St. Pölten."
image: "/images/historiavirtualis.png"
# banner: "/images/projects/historia-virtualis/banner.jpg"   # detail-page image (falls back to image)
video: "https://www.youtube.com/watch?v=JfwlEoEAzEo"                       # optional; overrides banner (16:9)
weight: 5
badges: ["VR", "Multiplayer", "Location-based"]
tools: ["Unity", "C#", "Meta XR SDK", "Hand Tracking", "Shared Spatial Anchors", "Meta Avatars"]
role: "Development Operations, Multiplayer development, Implementation of player challenges"
teamMembers: "Serkan Sönmez, Georg Becker, Florian Fußthaler and Sophia Olesko"
duration: "Still ongoing"
when: "2025"
challenge: "The core challenge of Historia Virtualis was to create a multiplayer VR experience in which all players share a synchronized virtual space aligned with the physical room around them. Without access to established location-based VR (LBVR) solutions, we needed to develop our own approach, which would allow the experience to be set up in new environments with minimal effort."
approach: "We developed Historia Virtualis as a controller-free, colocated XR game using the Meta XR SDK. Players interact with tools and the virtual world through hand tracking, while their physical movement maps one-to-one to movement in the game.\n To align the virtual environment across headsets, we used Meta’s Shared Spatial Anchors feature. The host headset creates an anchor and shares it with the other players, establishing a common spatial reference that places everyone in the same virtual space within the physical room. Unity’s Netcode for GameObjects handles multiplayer networking and synchronizes the shared game state."
result: "We created and evaluated a application that is usuable to be presented at festivals and is very well received. We aim to use the technical know how we gained through this project to further develop multiuser experiences to be shown in educational contexts and museums."
achievements: [
    "1st place: 12th Interactive Digital Media Student Contest 2026, Section eXtended Reality",
    "1st place: USTP Projektvernissage 2025",
    "Shown at the European Researchers' Night",
    "Part of Lucid Dreams 2026",
    "Part of Lange Nacht der Museen at Stadtmuseum St. Pölten"
]
learned: "This was the first project in which I worked with a multiplayer framework and the Meta XR SDK. Making use of Meta's services such as Shared Spatial Anchors and Avatars added valuable tools to my skillset."
team: true
links: []
gallery: []
# gallery:
#   - "/images/projects/historia-virtualis/01.jpg"
showInHome: true
---

Historia Virtualis is a colocated experience for 3 players set in the ancient Roman version of St. Pölten called Aelium Cetium. Every player has a specific tool in game which describes their role. An axe, flint and steel, and a peel. As each tool offers different abilities to the player using it they have to cooperate to achieve the goal of baking bread for the local governor.