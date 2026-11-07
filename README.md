<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=34&duration=3000&pause=1000&color=22D3EE&center=true&vCenter=true&width=700&height=70&lines=Ashish+Kumar;Full-Stack+Developer+in+the+making;B.Tech+IT+%40+REC+Bijnor" alt="Ashish Kumar" />

**I build web apps that solve real problems, and I'm getting better at DSA every day.**

<a href="https://ashishportfolioss.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-22D3EE?style=flat-square&logo=googlechrome&logoColor=black" /></a>
<a href="https://leetcode.com/u/mrashish10x/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" /></a>
<a href="https://www.hackerrank.com/profile/ashishkumar28321"><img src="https://img.shields.io/badge/HackerRank-2EC866?style=flat-square&logo=hackerrank&logoColor=black" /></a>
<img src="https://komarev.com/ghpvc/?username=mrashish10x&style=flat-square&color=22D3EE&label=views" />

</div>

---

## 👋 Quick intro

```text
$ whoami
ashish — B.Tech IT student, Rajkiya Engineering College, Bijnor

$ cat now.txt
→ shipping a multi-role SaaS (Presently) with Next.js + Prisma
→ solving DSA problems in C++
→ learning how production apps are actually secured & deployed

$ cat goal.txt
→ land a software engineering internship, then a full-time role
```

---

## 🚀 Flagship project: Presently

> **A multi-role attendance management SaaS** for colleges, with separate Admin, Teacher and Student areas.

<table>
<tr>
<td width="55%" valign="top">

**What it does**

- 🔐 Role-based login: `/login/admin`, `/login/teacher`, `/login/student`
- 🏫 College-aware data model (multiple colleges, isolated data)
- 🧑‍🏫 Teacher assignment boundaries & attendance workflow
- ✉️ Email integration via Resend, Google OAuth sign-in
- 📊 Dashboards and charts with Recharts

**Status:** 🟡 active development

[![Live Demo](https://img.shields.io/badge/Live_Demo-22D3EE?style=for-the-badge&logo=googlechrome&logoColor=black)](https://presentylive.netlify.app/login/admin)
[![Source](https://img.shields.io/badge/Source_Code-0f172a?style=for-the-badge&logo=github)](https://github.com/mrashish10x/presently)

</td>
<td width="45%" valign="top">

**Built with**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs)
![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma)
![Turso](https://img.shields.io/badge/Turso_(libSQL)-4FF8D2?style=flat-square&logo=turso&logoColor=black)
![NextAuth](https://img.shields.io/badge/NextAuth_v5-7C3AED?style=flat-square)
![Resend](https://img.shields.io/badge/Resend-000000?style=flat-square)

</td>
</tr>
</table>

**How the pieces fit together**

```mermaid
flowchart LR
    U([User]) --> N[Next.js App Router]
    N --> A{{NextAuth + bcrypt}}
    A --> AD[Admin]
    A --> T[Teacher]
    A --> S[Student]
    AD & T & S --> P[Prisma ORM]
    P --> D[(Turso / libSQL)]
    N --> R[Resend emails]
```

---

## 🧰 Tech I work with

<div align="center">

| | |
|---|---|
| **Languages** | ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) |
| **Backend & Data** | ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma) ![SQLite](https://img.shields.io/badge/SQLite/libSQL-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white) ![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white) |

</div>

---

## 🌐 Other work

| Project | What it is | Links |
|---|---|---|
| **Personal Portfolio** | My personal site: skills, projects and journey in one place | [Live](https://ashishportfolioss.netlify.app/) · [Code](https://github.com/mrashish10x/portfolio) |

---

## 📈 Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=mrashish10x&show_icons=true&hide_border=true&theme=transparent&title_color=22D3EE&icon_color=22D3EE&text_color=8b949e" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mrashish10x&layout=compact&hide_border=true&theme=transparent&title_color=22D3EE&text_color=8b949e" />

<img width="85%" src="https://streak-stats.demolab.com?user=mrashish10x&theme=transparent&hide_border=true&ring=22D3EE&fire=22D3EE&currStreakLabel=22D3EE&sideLabels=8b949e&currStreakNum=8b949e&sideNums=8b949e&dates=8b949e" />

</div>

---

## 🤝 Let's connect

I'm open to **internships, open-source contributions and project collaborations**.
The best way to reach me is through my [portfolio](https://ashishportfolioss.netlify.app/) or by opening an issue / following on GitHub.

<div align="center">

<sub>⭐ If something here helped or interested you, a star on my repos means a lot.</sub>

</div>
