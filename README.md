
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,100:1C2128&height=150&text=YASER%20ZARIFI&fontColor=FFB000&fontSize=52&fontAlignY=42&desc=FULL-STACK%20ENGINEER%20%C2%B7%20APPLIED%20AI%20%C2%B7%20AUT&descSize=15&descAlignY=68&animation=blinking" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=24&duration=2800&pause=900&color=FFB000&center=true&vCenter=true&width=720&lines=Full-stack+developer%3A+Django+%2B+DRF+%2B+React;Building+and+deploying+production+systems;Cloud+infrastructure+and+CI%2FCD;Applied+machine+learning+and+NLP;Open+to+new+projects" alt="intro"/>

<br/>

<a href="#projects"><img src="https://img.shields.io/badge/01-PROJECTS-0D1117?style=for-the-badge&labelColor=1C2128"/></a>
<a href="#volunteer-experience"><img src="https://img.shields.io/badge/02-VOLUNTEER-0D1117?style=for-the-badge&labelColor=1C2128"/></a>
<a href="#tech-stack"><img src="https://img.shields.io/badge/03-TECH%20STACK-0D1117?style=for-the-badge&labelColor=1C2128"/></a>
<a href="#how-i-work"><img src="https://img.shields.io/badge/04-HOW%20I%20WORK-0D1117?style=for-the-badge&labelColor=1C2128"/></a>
<a href="#activity"><img src="https://img.shields.io/badge/05-ACTIVITY-0D1117?style=for-the-badge&labelColor=1C2128"/></a>
<a href="#contact"><img src="https://img.shields.io/badge/06-CONTACT-0D1117?style=for-the-badge&labelColor=1C2128"/></a>

</div>

<br/>

<table>
<tr>
<td width="57%" valign="top">

### About

I'm a Computer Engineering graduate from Amirkabir University of Technology, focused on building software that solves real-world problems.

My work spans full-stack web development, mobile applications, backend architecture, and cloud deployment. I've built production systems for travel booking and payments and contributed as a volunteer full-stack developer to DATAAFG, an open-access academic research repository for Afghanistan.

I'm most comfortable with Django, DRF, PostgreSQL, and React. I also work with Linux infrastructure, Docker, CI/CD automation, and applied machine learning.

</td>
<td width="43%" valign="top">

### At a glance

**Education**  
B.Sc. Computer Engineering, AUT

**Core stack**  
Django · DRF · React · PostgreSQL

**Engineering**  
Full-stack · Cloud · CI/CD

**Learning now**  
RAG, vector search, Persian NLP

**Status**  
Open to work and collaboration

</td>
</tr>
</table>

---

## Projects

| # | Project | What it is | Stack / Focus | Status |
|:--|:--|:--|:--|:--|
| 01 | **[Sharifineya Travel Platform](https://www.sharifineyatrip.com/)** | Travel and transport system: web, admin, booking, payments | Django, DRF, React, PostgreSQL | `Live` |
| 02 | **[Sharifineya Mobile](https://play.google.com/store/apps/details?id=com.sharifineya.mobile)** | Android app for searching and booking trips | React Native, Expo | `Google Play` |
| 03 | **[DATAAFG](https://dataafg.com/)** | Open-access repository preserving Afghanistan's academic research | Full-stack, Linux, CI/CD | `Live · Volunteer` |
| 04 | **Urban Helper** | Civic platform for reporting and tracking city issues | Django, React, PostgreSQL | `Completed` |
| 05 | **[Pahlawan](https://pahlawan-ai.netlify.app/)** | AI workout planner with personalized training plans | Python, Django, React | `Active` |
| 06 | **[Portfolio](https://yaserzarifi.vercel.app/en)** | Personal site for projects and experience | Next.js, React, Tailwind | `Live` |

<br/>

<details open>
<summary><b>01 &nbsp; Sharifineya Travel Platform</b> &nbsp; <code>production</code></summary>

<br/>

The travel and transportation system I built for Sharifineya Travel Services. It covers the customer website, the admin panel, booking, passenger management, payments, and multiple languages. One REST API serves both the web app and the mobile app.

**[sharifineyatrip.com](https://www.sharifineyatrip.com/)**

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#161B22','primaryTextColor':'#C9D1D9','primaryBorderColor':'#FFB000','lineColor':'#FFB000','secondaryColor':'#0D1117','tertiaryColor':'#0D1117','fontFamily':'monospace'}}}%%
flowchart TD
    W["React Web"]
    M["React Native App"]
    A["Admin Console"]
    API{{"Django REST Framework"}}
    W --> API
    M --> API
    A --> API
    API --> DB[("PostgreSQL")]
    API --> PAY["Payment Gateway"]
    API --> I18N["i18n / RTL"]
    API --> DOC["Docker"]
```

<img src="https://img.shields.io/badge/Django-0D1117?style=flat-square&logo=django&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/DRF-0D1117?style=flat-square&logo=django&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/React-0D1117?style=flat-square&logo=react&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/PostgreSQL-0D1117?style=flat-square&logo=postgresql&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/Docker-0D1117?style=flat-square&logo=docker&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/Tailwind-0D1117?style=flat-square&logo=tailwindcss&logoColor=FFB000"/>

</details>

<details>
<summary><b>02 &nbsp; Sharifineya Mobile</b> &nbsp; <code>android</code></summary>

<br/>

An Android app published on Google Play. Users can search for trips, book them, and enter passenger details, and all of it talks to the same Django backend as the website.

**[Download on Google Play](https://play.google.com/store/apps/details?id=com.sharifineya.mobile)**

<img src="https://img.shields.io/badge/React%20Native-0D1117?style=flat-square&logo=react&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/Expo-0D1117?style=flat-square&logo=expo&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/JavaScript-0D1117?style=flat-square&logo=javascript&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/REST%20API-0D1117?style=flat-square&logo=fastapi&logoColor=FFB000"/>

</details>

<details open>
<summary><b>03 &nbsp; DATAAFG, Afghanistan Academic and Research Repository</b> &nbsp; <code>volunteer · production</code></summary>

<br/>

**[DATAAFG](https://dataafg.com/)** is an independent, non-profit, open-access academic repository dedicated to preserving, organizing, indexing, and sharing the scholarly work of Afghan researchers.

Founded around the motto **"How does Afghanistan think?"**, the initiative addresses the fragmentation and loss of Afghanistan's academic and research output by making scholarly knowledge more accessible, discoverable, and easier to preserve.

The repository supports the long-term vision of strengthening Afghanistan's academic infrastructure and connecting researchers, students, universities, and the international scholarly community.

### My contribution

**Volunteer Full-Stack Developer**

Contributed to the platform's complete software delivery lifecycle, from application development and frontend/backend implementation to production deployment, Linux server management, and CI/CD automation.

**Engineering responsibilities:**

- **Full-stack development:** Developed and maintained frontend and backend application functionality.
- **Authentication and sessions:** Worked on login verification, user sessions, and session history management.
- **Research workflows:** Contributed to document uploads, upload progress handling, and metadata presentation.
- **User experience:** Improved responsive navigation, account controls, and multilingual interface elements.
- **Cloud infrastructure:** Deployed and maintained the production application on a Hetzner-hosted Ubuntu server.
- **CI/CD automation:** Configured and maintained GitHub Actions deployment workflows, automating updates from the repository to production.
- **Operations:** Managed Git workflows, deployment troubleshooting, and production application updates.

**[Visit the live platform](https://dataafg.com/)**

<img src="https://img.shields.io/badge/Full--Stack-0D1117?style=flat-square&logo=github&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/GitHub%20Actions-0D1117?style=flat-square&logo=githubactions&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/Linux-0D1117?style=flat-square&logo=linux&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/Hetzner%20Cloud-0D1117?style=flat-square&logo=hetzner&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/Open%20Access-0D1117?style=flat-square&logo=bookstack&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/Non--Profit-0D1117?style=flat-square&logo=githubsponsors&logoColor=FFB000"/>

</details>

<details>
<summary><b>04 &nbsp; Urban Helper</b> &nbsp; <code>university project</code></summary>

<br/>

My final project at AUT. Citizens can report city problems and follow what happens to them, so requests don't get lost between the people who file them and the services that handle them.

<img src="https://img.shields.io/badge/Django-0D1117?style=flat-square&logo=django&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/React-0D1117?style=flat-square&logo=react&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/PostgreSQL-0D1117?style=flat-square&logo=postgresql&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/REST%20API-0D1117?style=flat-square&logo=fastapi&logoColor=FFB000"/>

</details>

<details>
<summary><b>05 &nbsp; Pahlawan, AI Workout Planner</b> &nbsp; <code>ai</code></summary>

<br/>

A fitness app that builds personalized workout plans and helps users keep their training organized. The hard part was keeping the generated plans realistic enough that people would actually stick to them.

<img src="https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/Django-0D1117?style=flat-square&logo=django&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/React-0D1117?style=flat-square&logo=react&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/AI%2FML-0D1117?style=flat-square&logo=openai&logoColor=FFB000"/>

</details>

<details>
<summary><b>06 &nbsp; Portfolio</b> &nbsp; <code>personal site</code></summary>

<br/>

My projects and experience in one place.

**[yaserzarifi.vercel.app](https://yaserzarifi.vercel.app)**

<img src="https://img.shields.io/badge/Next.js-0D1117?style=flat-square&logo=nextdotjs&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/React-0D1117?style=flat-square&logo=react&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/Tailwind-0D1117?style=flat-square&logo=tailwindcss&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/Vercel-0D1117?style=flat-square&logo=vercel&logoColor=FFB000"/>

</details>

---

## Volunteer Experience

### Full-Stack Developer | DATAAFG

**Afghanistan Academic and Research Repository**  
`Volunteer` · `Full-stack Engineering` · `Cloud & DevOps`

**[dataafg.com](https://dataafg.com/)**

Supporting the development and operation of an independent, non-profit academic repository designed to preserve Afghanistan's scholarly heritage and provide free access to research.

My work involves delivering software across the entire application lifecycle:

| Area | Responsibilities |
|:--|:--|
| **Application Development** | Frontend and backend implementation, feature development, and maintenance |
| **Authentication** | Login verification, session handling, and user account functionality |
| **Research Platform** | Document uploads, metadata presentation, and contributor-facing workflows |
| **UI/UX** | Responsive interfaces, navigation improvements, and multilingual UI |
| **Infrastructure** | Linux server configuration, cloud deployment, and production maintenance |
| **CI/CD** | GitHub Actions workflows, deployment automation, and troubleshooting |

This experience combines hands-on software engineering with a broader mission to improve access to academic knowledge and strengthen Afghanistan's digital research infrastructure.

---

## Tech Stack

| Layer | | Tools |
|:--|:--|:--|
| **Backend** | <img src="https://skillicons.dev/icons?i=python,django,postgresql&perline=3" height="38"/> | Python, Django, Django REST Framework, PostgreSQL, REST API design |
| **Frontend** | <img src="https://skillicons.dev/icons?i=react,nextjs,js,tailwind&perline=4" height="38"/> | React, Next.js, JavaScript, Tailwind CSS, Bootstrap, HTML, CSS |
| **Mobile** | <img src="https://skillicons.dev/icons?i=react,js&perline=2" height="38"/> | React Native, Expo |
| **AI and Data** | <img src="https://skillicons.dev/icons?i=tensorflow,pytorch&perline=2" height="38"/> | TensorFlow, PyTorch, NumPy, Pandas |
| **Infra and DevOps** | <img src="https://skillicons.dev/icons?i=docker,git,github,linux,githubactions&perline=5" height="38"/> | Docker, Git, GitHub, GitHub Actions, CI/CD, Linux, Hetzner Cloud, Vercel |
| **Also** | <img src="https://skillicons.dev/icons?i=java,c&perline=2" height="38"/> | Java, C |

---

## How I Work

| | |
|:--|:--|
| **Schema first** | I design the data model before writing endpoints. |
| **API before UI** | The contract gets agreed on before anything is styled. |
| **Reproducible** | Docker, so it runs the same on every machine. |
| **Multilingual early** | Languages and RTL are handled from the start, not patched in. |
| **Automated delivery** | CI/CD workflows make production deployments consistent and repeatable. |
| **Shipped** | Deployed and kept running, not left on localhost. |

**Interested in:** AI and machine learning, NLP, search and recommendation systems, database systems, cloud infrastructure, DevOps, digital public infrastructure, and UX engineering.

---

## Activity

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=YaserZarifi&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=FFB000&icon_color=FFB000&text_color=C9D1D9"/>
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YaserZarifi&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=FFB000&text_color=C9D1D9"/>

<img src="https://streak-stats.demolab.com?user=YaserZarifi&hide_border=true&background=0D1117&stroke=30363D&ring=FFB000&fire=FFB000&currStreakLabel=FFB000&sideLabels=C9D1D9&dates=8B949E&sideNums=C9D1D9&currStreakNum=C9D1D9"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=YaserZarifi&bg_color=0D1117&color=C9D1D9&line=FFB000&point=FFFFFF&area=true&area_color=FFB000&hide_border=true&custom_title=Contributions" width="100%"/>

</div>

---

## Contact

| | |
|:--|:--|
| **Email** | [yaserzarifi1378@gmail.com](mailto:yaserzarifi1378@gmail.com) |
| **LinkedIn** | [mohammad-yaser-zarifi](https://www.linkedin.com/in/mohammad-yaser-zarifi/) |
| **Portfolio** | [yaserzarifi.vercel.app](https://yaserzarifi.vercel.app/en) |
| **Google Play** | [Sharifineya Mobile](https://play.google.com/store/apps/details?id=com.sharifineya.mobile) |

Open to full-stack and AI engineering roles, freelance work, and collaborations.

<div align="center">

<img src="https://komarev.com/ghpvc/?username=YaserZarifi&style=for-the-badge&color=FFB000&label=VISITORS"/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1C2128,100:0D1117&height=90&section=footer&text=ALWAYS%20LEARNING%20%C2%B7%20ALWAYS%20BUILDING&fontColor=FFB000&fontSize=18&fontAlignY=52" width="100%"/>

</div>
