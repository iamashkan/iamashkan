<!-- ============================== HEADER ============================== -->
<a href="https://iamashkan.github.io/portfolio/">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A66C2,100:5E5CE6&height=210&section=header&text=Ashkan%20Aghamoali&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=AI%20Researcher%20%C2%B7%20XR%20Developer%20%C2%B7%20Published%20in%20the%20Royal%20Society%20Interface&descSize=17&descAlignY=58&animation=fadeIn" alt="Ashkan Aghamoali"/>
</a>

<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=5E5CE6&center=true&vCenter=true&width=820&lines=Researcher+%40+Mechanical+Intelligence+Lab%2C+LSBU;Where+biomimetics+meets+deep+learning+%26+FEA;Digital+twins+for+the+circular+economy;Giving+the+physical+world+a+queryable+mirror" alt="Typing SVG" />
</a>

<br/>

<a href="https://www.researchgate.net/profile/Ashkan-Aghamoali"><img src="https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white" alt="ResearchGate"/></a>
<a href="https://www.linkedin.com/in/ashkan-aghamoali/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://iamashkan.github.io/portfolio/"><img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
<a href="mailto:ashkaan.aghamoali@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<img src="https://komarev.com/ghpvc/?username=iamashkan&style=for-the-badge&color=5E5CE6&label=VIEWS" alt="views"/>

</div>

---

### `$ ashkan --whoami`

```python
class AshkanAghamoali:
    """AI Researcher · XR Developer · Published Author"""

    def __init__(self):
        self.affiliation = "Mechanical Intelligence (MI) Research Group — LSBU"
        self.based_in    = "Dubai, UAE"
        self.education    = "M.Sc. Digital Electronic Systems"
        self.research     = ["biomimetics", "digital twins",
                             "generative design", "computer vision"]
        self.stack        = ["Python", "Swift", "C#", "PyTorch", "Unity", "ROS 2"]
        self.philosophy   = "simulation-first, hardware-ready"

    def current_focus(self) -> list[str]:
        return [
            "Turning industrial scrap into recovered value  (Re-X digital twins)",
            "Making the physical world queryable  (ARKit + on-device ML)",
            "Bio-inspired structures optimized by  FEA → deep learning → GA",
        ]

    def collaborators(self):
        return ["MI Research Group (LSBU)", "Prof. Stanislav Gorb (Kiel Uni)"]
```

---

### 📚 Peer-Reviewed Research &nbsp;·&nbsp; *equal-contributing author on both*

**1 · The Rise of Metaverse Manufacturing** — *towards a universal, sustainable & bioinspired industrial ecosystem*

<a href="https://doi.org/10.1098/rsif.2025.0480"><img src="https://img.shields.io/badge/J.%20R.%20Soc.%20Interface-2026-C7254E?style=flat-square" alt="venue"/></a>
<a href="https://doi.org/10.1098/rsif.2025.0480"><img src="https://img.shields.io/badge/DOI-10.1098%2Frsif.2025.0480-1B72E8?style=flat-square" alt="doi"/></a>

> Eraghi, Toofani, **Aghamoali**, Zoroufi, Shafaghi, Jafari, Goel, Rajabi · *Journal of the Royal Society Interface* **23**, 20250480
> A framework uniting **complex adaptive systems**, **digital twins**, **XR**, **AI** and **biomimetics** into a sustainable Industry 5.0 manufacturing ecosystem aligned with the UN SDGs.

**2 · One to Many: An Intelligent Biomimetic Design Framework for Functional Diversification**

<img src="https://img.shields.io/badge/Generative%20Design-5E5CE6?style=flat-square" alt="t"/>
<img src="https://img.shields.io/badge/Deep%20Learning-EE4C2C?style=flat-square" alt="t"/>
<img src="https://img.shields.io/badge/FEA-009688?style=flat-square" alt="t"/>
<img src="https://img.shields.io/badge/Soft%20Robotics-FF6B00?style=flat-square" alt="t"/>

> Toofani, Eraghi, **Aghamoali**, Zoroufi, Khaheshi, Basti, **Gorb**, Rajabi · MI Research Group (LSBU) × Kiel University
> Spider-*sigillae*-inspired **"plate-pillar"** structures → high-throughput **FEA of ~900 variants** → **deep-neural-network** surrogate models → **multi-objective genetic-algorithm** generative design → a compliant hinge, mechanical joint, tunable springs & an adaptive soft gripper — delivered as an interactive **AR "Meta-Article."**

---

### 🧬 How my research becomes code

```mermaid
flowchart LR
    A["🕷️ Biological<br/>inspiration"] --> B["⚙️ Parametric<br/>CAD model"]
    B --> C["🔬 High-throughput<br/>FEA · ~900 variants"]
    C --> D["🧠 Deep-learning<br/>surrogate model"]
    D --> E["🧬 Multi-objective<br/>genetic algorithm"]
    E --> F["✨ Generative<br/>designs"]
    F --> G["📱 AR Meta-Article<br/>+ Digital Twins"]
    classDef n fill:#5E5CE6,stroke:#0A66C2,color:#fff,rx:6,ry:6;
    class A,B,C,D,E,F,G n;
```

---

### 🚀 Flagship Engineering

<details open>
<summary><b>♻️ &nbsp;Circular-Economy Digital Twins</b></summary>
<br/>

| Project | What it does | Stack |
|---|---|---|
| [**UR5e Circular Motor Recovery**](https://github.com/iamashkan/UR5e-Circular-Motor-Recovery) | A UR5e cobot disassembles failed motors and sorts every part into Reuse / Repair / Replace / Recycle | `ROS 2 Jazzy` `MoveIt 2` `Gazebo` `Unity` |
| [**Battery Sorting Digital Twin**](https://github.com/iamashkan/Battery-Sorting-in-Digital-Twin) | Operational control twin for a battery-recovery micro-factory, with digital product passports | `Unity` `FastAPI` `CV` `Streamlit` |
| [**Defect Inspection Twin**](https://github.com/iamashkan/defect-inspection-digital-twin) | PyTorch surface-defect CV + Grad-CAM heatmaps → structured recovery decision | `PyTorch` `OpenCV` `ROS 2` |
| [**Re-X Inspection Twin**](https://github.com/iamashkan/re-x-inspection-digital-twin) | Inspection pipeline aligned to the RESCu-M2 research theme | `PyTorch` `Grad-CAM` `ROS 2` |

</details>

<details open>
<summary><b>📡 &nbsp;Spatial Computing & Industrial AR</b></summary>
<br/>

| Project | What it does | Stack |
|---|---|---|
| [**Real-Time Digital Twin on iOS**](https://github.com/iamashkan/Real-Time-Digital-Twin-Generation-on-IOS) | Scans industrial rooms into live, queryable 3D twins bound to real devices | `Swift` `ARKit` `RoomPlan` `Core ML` `MQTT` |
| [**Semantic Segmentation AR**](https://github.com/iamashkan/Semantic-Segmentation-using-Unity-and-Niantic-Lightship) | Environment-aware AR powered by real-time semantic segmentation | `Unity` `Niantic Lightship` |
| [**WebAR Face Filter**](https://github.com/iamashkan/WebAR-FaceFilter) | Browser-native AR face tracking — no app install | `Unity` `Needle Engine` |

</details>

<details open>
<summary><b>⚡ &nbsp;Smart Systems & Edge AI</b></summary>
<br/>

| Project | What it does | Stack |
|---|---|---|
| [**Smart Highway Lighting**](https://github.com/iamashkan/Smart-Highway-Lighting) ⭐ | Emergency-aware adaptive motorway lighting — **up to 70% energy saved** | `Python` `STM32` `MQTT` `Unity 6` |
| [**Solar Sentinel**](https://github.com/iamashkan/solar-sentinel) | Solar-farm twin: CV panel inspection + water-budgeted cleaning-robot dispatch | `Python` `ROS 2` `Streamlit` |
| [**Market Price Bot**](https://github.com/iamashkan/CurrencyRateTelegramBot) | Serverless Telegram bot posting live FX / gold / crypto prices | `Cloudflare Workers` `JavaScript` |

</details>

---

### 🛠️ Tech Arsenal

**Languages** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)

**Research & ML** &nbsp;
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Core ML](https://img.shields.io/badge/Core%20ML-0A84FF?style=flat-square&logo=apple&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![FEA](https://img.shields.io/badge/FEA%20%2F%20CAE-009688?style=flat-square)
![Genetic Algorithms](https://img.shields.io/badge/Genetic%20Algorithms-5E5CE6?style=flat-square)

**XR · 3D · Robotics** &nbsp;
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![ARKit](https://img.shields.io/badge/ARKit-000000?style=flat-square&logo=apple&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)
![MoveIt](https://img.shields.io/badge/MoveIt_2-0A7BBB?style=flat-square)
![Gazebo](https://img.shields.io/badge/Gazebo-FF6B00?style=flat-square&logo=gazebo&logoColor=white)

**Backend · Edge · Infra** &nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)

---

<!-- ============================== SNAKE ============================== -->
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iamashkan/iamashkan/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/iamashkan/iamashkan/output/github-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/iamashkan/iamashkan/output/github-snake.svg" width="100%" />
</picture>

### 📊 GitHub Activity

<img src="https://streak-stats.demolab.com/?user=iamashkan&hide_border=true&ring=5E5CE6&fire=EA4335&currStreakLabel=5E5CE6&sideLabels=5E5CE6" alt="streak" width="460"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=iamashkan&bg_color=00000000&color=5E5CE6&line=0A66C2&point=0A66C2&area=true&area_color=5E5CE6&hide_border=true&custom_title=Contribution%20Graph" alt="activity graph" width="95%"/>

</div>

---

<div align="center">

*“The best way to recover value from the physical world is to first give it a digital mind.”*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:5E5CE6,100:0A66C2&height=120&section=footer" alt="footer"/>

</div>
