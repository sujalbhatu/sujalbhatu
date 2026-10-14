<!-- ===================== HEADER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=0:0f0c29,50:302b63,100:24243e&height=230&section=header&text=Hey%2C%20I'm%20Sujal%20%F0%9F%91%8B&fontSize=48&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=I%20turn%20research%20papers%20into%20things%20people%20actually%20use&descSize=17&descAlignY=60" alt="header" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=3200&pause=900&color=A78BFA&center=true&vCenter=true&multiline=false&width=700&lines=%3E+backend+engineer+who+reads+ML+papers+for+fun;%3E+made+roll-call+go+from+15+min+%E2%86%92+25+seconds;%3E+taught+a+GNN+to+ignore+17+of+22+EEG+electrodes;%3E+can+tell+your+iris+apart+99.6%25+of+the+time+%F0%9F%91%81%EF%B8%8F;%3E+currently%3A+shipping%2C+interviewing%2C+repeat" alt="typing" />
  </a>
</p>

<p align="center">
  <a href="https://openforge.online"><img src="https://img.shields.io/badge/🌐_openforge.online-live-22c55e?style=for-the-badge&labelColor=1e1b4b" /></a>
  <a href="https://linkedin.com/in/sujalbhatu"><img src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=1e1b4b" /></a>
  <a href="mailto:sujalbhatu565@gmail.com"><img src="https://img.shields.io/badge/Mail-say_hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1e1b4b" /></a>
  <a href="https://codeforces.com/profile/sujalbhatu"><img src="https://img.shields.io/badge/Codeforces-1266-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white&labelColor=1e1b4b" /></a>
</p>


<!-- ===================== ABOUT ===================== -->

<p align="center">
  <img src="assets/about.svg" alt="About Sujal" width="100%" />
</p>

<!-- ===================== PROJECTS ===================== -->

## 🛸 Things I've built (that are actually live)

<table>
<tr>
<td width="50%" valign="top">

<h3 align="center">🎓 CampusTrack <sub>(RollOne)</sub></h3>
<p align="center"><i>Proxy attendance? Not on my watch.</i></p>

<p align="center">
  <a href="https://campustrack.openforge.online"><img src="https://img.shields.io/badge/▶_Live_Demo-22c55e?style=for-the-badge" /></a>
  <a href="https://github.com/sujalbhatu/Attendence_System"><img src="https://img.shields.io/badge/Source-181717?style=for-the-badge&logo=github" /></a>
</p>

A whole lecture hall checks in **in under 25 seconds** instead of 15 minutes, and nobody can mark a friend present from the canteen:

- 🔑 QR tokens signed with **HMAC-SHA256** that die every **4 s**, pushed live over **SSE**
- 📍 **35 m Haversine geofence** + line-of-sight PIN
- 🤳 Face check with in-browser cropping: **15 KB instead of 2.4 MB** per frame
- ⚙️ Handles **100+ concurrent** check-ins without double-marking races

<sub>`React` · `Node.js` · `Python` · `MongoDB` · `Docker` · `Nginx`</sub>

</td>
<td width="50%" valign="top">

<h3 align="center">⚖️ OpenForge</h3>
<p align="center"><i>Ask Indian law a question. Get the actual section back.</i></p>

<p align="center">
  <a href="https://openforge.online"><img src="https://img.shields.io/badge/▶_Live_Demo-22c55e?style=for-the-badge" /></a>
  <a href="https://github.com/sujalbhatu/Legal-chatbot"><img src="https://img.shields.io/badge/Source-181717?style=for-the-badge&logo=github" /></a>
</p>

A RAG legal assistant that refuses to hallucinate, because it has to cite the exact statute section every time:

- 🕷️ Scrapes & chunks acts straight from **IndiaCode** into **ChromaDB**
- 🧠 Recursive chat summarisation: **45% fewer tokens** on long sessions
- 🗣️ Ask in any of **14 Indian languages**, auto-detected and translated
- 📌 Strict exact-section citations, every answer traceable

<sub>`Python` · `Flask` · `React` · `Node.js` · `ChromaDB`</sub>

</td>
</tr>
</table>

## 🔬 From the lab

<table>
<tr>
<td width="50%" valign="top">

**🧠 [GGCS: Gated Graph Convolution Selection](https://github.com/sujalbhatu/EEG-channel-classification)**
<br><sub>MVI Lab, NIT Jamshedpur</sub>

What if a brain-computer interface needed **5 electrodes instead of 22**? A graph network that learns *which* channels matter for motor-imagery classification, cutting **77%** of the hardware while staying competitive on BCI Competition IV-2a.

📄 *GCN-Based End-to-End Channel Selection and Classification for Motor Imagery BCIs*, submitted to **Neural Computing & Applications**

</td>
<td width="50%" valign="top">

**👁️ [Hybrid Iris Recognition](https://github.com/sujalbhatu/IRISH)**
<br><sub>Capstone project</sub>

Old-school meets deep learning: classic **Daugman IrisCode** (rubber-sheet normalisation, Log-Gabor filters, Hamming matching) fused with a **multi-scale ResNet-50**.

🎯 **99.60%** accuracy on CASIA-Iris-V1
<br>🛡️ False accepts down from **6.3% → 0.19%**

</td>
</tr>
</table>

<details>
<summary><b>🗂️ More experiments (click to expand)</b></summary>
<br>

| Project | What it does |
|---|---|
| 🛒 [Amazon ML Challenge](https://github.com/sujalbhatu/Amazon-ML-Hackathon) | Entity resolution at scale; finished **Top 1,000 globally** (2026) |
| 🦴 [Bone Health Classifier](https://github.com/sujalbhatu/Automated-Classification-of-Bone-Health) | Automated classification of bone health from medical images |
| 🤟 [Indian Sign Language Detection](https://github.com/shivapreetham/indian-sign-language-detection) | Real-time ISL gesture recognition with computer vision |

</details>

<!-- ===================== STACK ===================== -->

## 🧰 My toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,java,python,js,ts,bash&perline=6" />
  <br><br>
  <img src="https://skillicons.dev/icons?i=react,nodejs,express,django,flask,postman&perline=6" />
  <br><br>
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,docker,nginx,linux,git&perline=6" />
  <br><br>
  <img src="https://skillicons.dev/icons?i=pytorch,opencv,sklearn,gcp,githubactions,vscode&perline=6" />
</p>

<!-- ===================== SCOREBOARD ===================== -->

## 🏁 Scoreboard

<p align="center">
  <img src="https://img.shields.io/badge/Amazon_ML_Challenge_2026-Top_1000_🌍-FF9900?style=flat-square&labelColor=232F3E" />
  <img src="https://img.shields.io/badge/DSA_problems-600+_🧩-8B5CF6?style=flat-square&labelColor=1e1b4b" />
  <img src="https://img.shields.io/badge/CodeKarma--March-4th_place_🏅-F59E0B?style=flat-square&labelColor=1e1b4b" />
  <a href="https://codeforces.com/profile/sujalbhatu"><img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fcodeforces.com%2Fapi%2Fuser.info%3Fhandles%3Dsujalbhatu&query=%24.result%5B0%5D.maxRating&label=Codeforces%20max&logo=codeforces&color=1F8ACB&style=flat-square&labelColor=1e1b4b" /></a>
  <img src="https://img.shields.io/badge/Research-1_paper_under_review_📄-EC4899?style=flat-square&labelColor=1e1b4b" />
</p>


<!-- ===================== STATS ===================== -->

## 🧬 What I write most

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sujalbhatu&layout=compact&theme=midnight-purple&hide_border=true&langs_count=8&card_width=420" />
</p>

<!-- ===================== OFF THE KEYBOARD ===================== -->

## ☕ Off the keyboard

- 🤝 I mentor school kids from rural backgrounds for the **Navodaya entrance exams** with Sankalp Club. Teaching logical reasoning to a 10-year-old is harder than any LeetCode hard.
- 🐛 Favourite bug ever: a race condition that marked one student present *twice*. Fixed with compound unique indexes and a lot of coffee.
- 💬 Ask me about: SSE vs WebSockets, why your RAG hallucinates, or how many EEG channels you *really* need.

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer&text=let's%20build%20something%20that%20scales&fontSize=20&fontColor=c4b5fd&fontAlignY=70" />
</p>
