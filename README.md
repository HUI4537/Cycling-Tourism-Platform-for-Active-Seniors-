<div align="center">

# Cycling Tourism Platform<br>for Active Seniors

### 시끌시끌

**Sungmin Choi** ([@choisment922](https://github.com/choisment922)) · **Geonmin Kim** ([@GoneM129](https://github.com/GoneM129)) · **Seunggi Seo** ([@HUI4537](https://github.com/HUI4537))

**Daejeon Daeshin High School · SOFT050T**

An intelligent cycling tourism platform designed for active seniors and longer, more rewarding stays.

<table width="100%">
  <tr>
    <td align="center" width="38%">
      <a href="https://isef.net/project/soft050t-cycling-tourism-platform-for-active-seniors"><img src="https://firebasestorage.googleapis.com/v0/b/project-leo-mvp.appspot.com/o/navbars%2Fwordmark-v2.png?alt=media&amp;token=b76409d5-c39f-4235-ac7e-c7cf9fc3f52c" alt="Regeneron ISEF — official website wordmark" width="320"></a>
    </td>
    <td align="center" width="62%">
      <strong>REGENERON ISEF 2025</strong><br>
      International Science and Engineering Fair<br>
      <a href="https://isef.net/project/soft050t-cycling-tourism-platform-for-active-seniors"><strong>Systems Software · SOFT050T · View official project ↗</strong></a>
    </td>
  </tr>
</table>

<a href="https://firebasestorage.googleapis.com/v0/b/project-leo-mvp.appspot.com/o/attachments%2F97fb5480-5f10-4369-bec8-177af38155b3%2F4811ca64691?alt=media&amp;token=d2c9ec8e-da1b-4fa2-99ae-ad6d9a601272">
  <img src="https://firebasestorage.googleapis.com/v0/b/project-leo-mvp.appspot.com/o/attachments%2F97fb5480-5f10-4369-bec8-177af38155b3%2F4811ca64691?alt=media&amp;token=d2c9ec8e-da1b-4fa2-99ae-ad6d9a601272" alt="ISEF research poster: project motivation, personalized recommendations, route planning, economic analysis and conclusions" width="100%">
</a>

<sub>ISEF 2025 research poster · Click to view at full resolution.</sub>

## [Explore the full project on ISEF ↗](https://isef.net/project/soft050t-cycling-tourism-platform-for-active-seniors)

**Discover the research, methodology, project video and team on our official project page.**

<a href="https://isef.net/project/soft050t-cycling-tourism-platform-for-active-seniors">
  <img src="https://img.shields.io/badge/READ_THE_FULL_PROJECT_ON_ISEF_%E2%86%97-F0A202?style=for-the-badge&amp;labelColor=172033" alt="Read the full project on ISEF">
</a>

<br><br>

[Tech stack](#tech-stack) · [Overview](#at-a-glance) · [Project cover](#project-cover) · [Get started](#get-started) · [Team](#team)

</div>

---

## Tech stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&amp;logo=flask&amp;logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&amp;logo=sqlite&amp;logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/Jinja-B41717?style=for-the-badge&amp;logo=jinja&amp;logoColor=white" alt="Jinja">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&amp;logo=html5&amp;logoColor=white" alt="HTML5">
  <br>
  <img src="https://img.shields.io/badge/CSS-663399?style=for-the-badge&amp;logo=css&amp;logoColor=white" alt="CSS">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&amp;logo=javascript&amp;logoColor=black" alt="JavaScript">
  <br>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&amp;logo=numpy&amp;logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&amp;logo=pandas&amp;logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&amp;logo=scikitlearn&amp;logoColor=white" alt="scikit-learn">
</p>

**Backend & data:** Flask, Jinja and SQLite · **Interface:** HTML, CSS and JavaScript · **Recommendations:** NumPy, pandas and scikit-learn.

<details>
<summary><strong>Research design and repository implementation</strong></summary>

The ISEF presentation describes Sentence-BERT semantic recommendations, DEM-based slope weighting, A*/TSP route planning and geofencing with voice guidance. The badges above describe the current repository stack; its recommendation module uses NumPy matrix factorization and scikit-learn cosine similarity.

For the complete research design and economic assumptions, visit the [official ISEF project page](https://isef.net/project/soft050t-cycling-tourism-platform-for-active-seniors).

</details>

## At a glance

We explore how personalized bicycle tourism can help active seniors discover local destinations, enjoy more comfortable routes and stay longer in a region. The research brings together three parts of the travel experience:

| Discover | Plan | Explore |
| :--- | :--- | :--- |
| **Personalized recommendations** | **Comfort-aware routing** | **Hands-free guidance** |
| Match destinations to traveler profiles, interests and food preferences. | Combine route optimization with slope information to account for physical effort. | Deliver location-based audio information as riders approach points of interest. |

> **Research highlight:** The economic analysis reported a benefit–cost ratio of **58.5–87.75** under its modeled assumptions. This is an estimated impact, not measured revenue. [See the research context on ISEF →](https://isef.net/project/soft050t-cycling-tourism-platform-for-active-seniors)

## Project cover

<p align="center">
  <img src="https://github.com/user-attachments/assets/1265533e-9925-4f55-b097-2ecf29f40c8e" alt="Original 시끌시끌 project cover" width="800">
</p>

## Get started

<details>
<summary><strong>Run the Flask application locally</strong></summary>

Use **Python 3.11**, as specified in `runtime.txt`.

```bash
git clone https://github.com/HUI4537/Cycling-Tourism-Platform-for-Active-Seniors-.git
cd Cycling-Tourism-Platform-for-Active-Seniors-
python -m venv .venv
```

Activate the environment:

```powershell
# Windows PowerShell
.venv\Scripts\Activate.ps1
```

```bash
# macOS / Linux
source .venv/bin/activate
```

Install dependencies and start the server:

```bash
python -m pip install -r requirements.txt
python flask_app.py
```

Open **http://localhost:5000**. Location and routing features depend on external map services and valid API configuration; startup also loads local CSV datasets and resolves place coordinates.

</details>

## Team

**[Sungmin Choi](https://github.com/choisment922) · [Geonmin Kim](https://github.com/GoneM129) · [Seunggi Seo](https://github.com/HUI4537)**<br>
Daejeon Daeshin High School · Daejeon, South Korea<br>
ISEF 2025 · Systems Software · **SOFT050T**

[Project & team on ISEF](https://isef.net/project/soft050t-cycling-tourism-platform-for-active-seniors) · [Contact the team](mailto:choisment922@gmail.com)

---

<p align="center">
  <strong>Want the full story behind the platform?</strong><br>
  <a href="https://isef.net/project/soft050t-cycling-tourism-platform-for-active-seniors"><strong>Explore our ISEF project →</strong></a>
</p>

<p align="center">
  <sub>Badges powered by <a href="https://shields.io/">Shields.io</a> · Badge styling inspired by <a href="https://github.com/envoy1084/awesome-badges">Awesome Badges</a>.</sub>
</p>
