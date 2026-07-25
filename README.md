<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,100:1C2128&height=150&text=YASER%20ZARIFI&fontColor=FFB000&fontSize=52&fontAlignY=42&desc=FULL-STACK%20ENGINEER%20%C2%B7%20APPLIED%20AI%20%C2%B7%20AUT&descSize=15&descAlignY=68&animation=blinking" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=24&duration=2800&pause=900&color=FFB000&center=true&vCenter=true&width=620&lines=Full-stack+developer%3A+Django+%2B+DRF+%2B+React;React+Native+app+live+on+Google+Play;Applied+machine+learning+and+NLP;Open+to+new+projects" alt="intro"/>

<br/>

<a href="#projects"><img src="https://img.shields.io/badge/01-PROJECTS-0D1117?style=for-the-badge&labelColor=1C2128"/></a>
<a href="#tech-stack"><img src="https://img.shields.io/badge/02-TECH%20STACK-0D1117?style=for-the-badge&labelColor=1C2128"/></a>
<a href="#how-i-work"><img src="https://img.shields.io/badge/03-HOW%20I%20WORK-0D1117?style=for-the-badge&labelColor=1C2128"/></a>
<a href="#activity"><img src="https://img.shields.io/badge/04-ACTIVITY-0D1117?style=for-the-badge&labelColor=1C2128"/></a>
<a href="#contact"><img src="https://img.shields.io/badge/05-CONTACT-0D1117?style=for-the-badge&labelColor=1C2128"/></a>

</div>

<br/>

<table>
<tr>
<td width="57%" valign="top">

### About

I studied Computer Engineering at Amirkabir University of Technology, and most of
what I build ends up in front of real users: booking flows, payments, passenger
records, mobile apps.

The backend is where I'm most comfortable, usually Django and DRF over
PostgreSQL, with React or React Native on the front. I also work with machine
learning, and I'm most interested in NLP and recommendation systems.

</td>
<td width="43%" valign="top">

### At a glance

**Education**
B.Sc. Computer Engineering, AUT

**Core stack**
Django · DRF · React · PostgreSQL

**Learning now**
Retrieval augmented generation, vector search, Persian NLP

**Status**
Open to work and collaboration

</td>
</tr>
</table>

---

## Projects

| # | Project | What it is | Stack | Status |
|:--|:--|:--|:--|:--|
| 01 | **[Sharifineya Travel Platform](https://www.sharifineyatrip.com/)** | Travel and transport system: web, admin, booking, payments | Django, DRF, React, PostgreSQL | `Live` |
| 02 | **[Sharifineya Mobile](https://play.google.com/store/apps/details?id=com.sharifineya.mobile)** | Android app for searching and booking trips | React Native, Expo | `Google Play` |
| 03 | **Urban Helper** | Civic platform for reporting and tracking city issues | Django, React, PostgreSQL | `Completed` |
| 04 | **[Pahlawan](https://pahlawan-ai.netlify.app/)** | AI workout planner with personalized training plans | Python, Django, React | `Active` |
| 05 | **[Portfolio](https://yaserzarifi.vercel.app/en)** | Personal site for projects and experience | Next.js, React, Tailwind | `Live` |

<br/>

<details open>
<summary><b>01 &nbsp; Sharifineya Travel Platform</b> &nbsp; <code>production</code></summary>

<br/>

The travel and transportation system I built for Sharifineya Travel Services. It
covers the customer website, the admin panel, booking, passenger management,
payments, and multiple languages. One REST API serves both the web app and the
mobile app.

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

An Android app published on Google Play. Users can search for trips, book them,
and enter passenger details, and all of it talks to the same Django backend as
the website.

**[Download on Google Play](https://play.google.com/store/apps/details?id=com.sharifineya.mobile)**

<img src="https://img.shields.io/badge/React%20Native-0D1117?style=flat-square&logo=react&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/Expo-0D1117?style=flat-square&logo=expo&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/JavaScript-0D1117?style=flat-square&logo=javascript&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/REST%20API-0D1117?style=flat-square&logo=fastapi&logoColor=FFB000"/>

</details>

<details>
<summary><b>03 &nbsp; Urban Helper</b> &nbsp; <code>university project</code></summary>

<br/>

My final project at AUT. Citizens can report city problems and follow what
happens to them, so requests don't get lost between the people who file them and
the services that handle them.

<img src="https://img.shields.io/badge/Django-0D1117?style=flat-square&logo=django&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/React-0D1117?style=flat-square&logo=react&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/PostgreSQL-0D1117?style=flat-square&logo=postgresql&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/REST%20API-0D1117?style=flat-square&logo=fastapi&logoColor=FFB000"/>

</details>

<details>
<summary><b>04 &nbsp; Pahlawan, AI Workout Planner</b> &nbsp; <code>ai</code></summary>

<br/>

A fitness app that builds personalized workout plans and helps users keep their
training organized. The hard part was keeping the generated plans realistic
enough that people would actually stick to them.

<img src="https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/Django-0D1117?style=flat-square&logo=django&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/React-0D1117?style=flat-square&logo=react&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/AI%2FML-0D1117?style=flat-square&logo=openai&logoColor=FFB000"/>

</details>

<details>
<summary><b>05 &nbsp; Portfolio</b> &nbsp; <code>personal site</code></summary>

<br/>

My projects and experience in one place.

**[yaserzarifi.vercel.app](https://yaserzarifi.vercel.app)**

<img src="https://img.shields.io/badge/Next.js-0D1117?style=flat-square&logo=nextdotjs&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/React-0D1117?style=flat-square&logo=react&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/Tailwind-0D1117?style=flat-square&logo=tailwindcss&logoColor=FFB000"/>
<img src="https://img.shields.io/badge/Vercel-0D1117?style=flat-square&logo=vercel&logoColor=FFB000"/>

</details>

---

## Tech Stack

| Layer | | Tools |
|:--|:--|:--|
| **Backend** | <img src="https://skillicons.dev/icons?i=python,django,postgresql&perline=3" height="38"/> | Python, Django, Django REST Framework, PostgreSQL, REST API design |
| **Frontend** | <img src="https://skillicons.dev/icons?i=react,nextjs,js,tailwind&perline=4" height="38"/> | React, Next.js, JavaScript, Tailwind CSS, Bootstrap, HTML, CSS |
| **Mobile** | <img src="https://skillicons.dev/icons?i=react,js&perline=2" height="38"/> | React Native, Expo |
| **AI and Data** | <img src="https://skillicons.dev/icons?i=tensorflow,pytorch&perline=2" height="38"/> | TensorFlow, PyTorch, NumPy, Pandas |
| **Infra and Tools** | <img src="https://skillicons.dev/icons?i=docker,git,github,linux,vercel&perline=5" height="38"/> | Docker, Git, GitHub, Linux, Vercel |
| **Also** | <img src="https://skillicons.dev/icons?i=java,c&perline=2" height="38"/> | Java, C |

---

## How I Work

| | |
|:--|:--|
| **Schema first** | I design the data model before writing endpoints. |
| **API before UI** | The contract gets agreed on before anything is styled. |
| **Reproducible** | Docker, so it runs the same on every machine. |
| **Multilingual early** | Languages and RTL are handled from the start, not patched in. |
| **Shipped** | Deployed and kept running, not left on localhost. |

**Interested in:** AI and machine learning, NLP, search and recommendation systems, database systems, cloud deployment, UX engineering.

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
