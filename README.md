<!-- ═══════════════════════════ HERO ═══════════════════════════ -->

<div align="center">

<img src="assets/hero.svg" width="100%" alt="Alrhaden Javier | Full-Stack & Systems Developer" />

<br />
<img src="https://img.shields.io/github/followers/RADENzzz?label=Followers&color=6C63FF&style=flat-square" alt="Followers" />
<a href="https://www.linkedin.com/in/alrhaden-javier-86b89428b/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>

</div>

<br />

## About Me

Hey, I'm **Raden**, a full-stack and systems developer. I like the whole stack: designing the schema, wiring the API, and then making the interface feel effortless.

I care about software that is *correct* before it is clever, well-tested, documented, and genuinely usable by the people who run it every day.

- **Building:**
  - [**CoE-NNECT**](https://github.com/RADENzzz/coe-nnect), a scheduling platform for the College of Engineering at WMSU.
  - [**End of The DayZ**](https://github.com/RADENzzz/End-of-the-Day), a 2D platform game, made with MONOGAME
  - [**CAPSLOCK**] A 3D Mini-Open world story ISEKAI game, made with GODOT 
- **Exploring:** systems programming, distributed web architecture, and game development.
- **2027 goal:** ship **CAPSLOCK**, my biggest game project yet.
- **Outside the terminal:** game engines, 3D art, and hardware tinkering on Raspberry Pi and Arduino.

<br />

## Featured Project

<h3 align="center">CoE-NNECT</h3>
<p align="center"><i>Academic scheduling for the College of Engineering · Western Mindanao State University</i></p>

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Open%20App-6C63FF?style=for-the-badge&logo=railway&logoColor=white)](https://coe-nnectfrontend-production.up.railway.app/)
[![Repository](https://img.shields.io/badge/Source-Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RADENzzz/coe-nnect)
[![License](https://img.shields.io/badge/License-MIT-00D2FF?style=for-the-badge)](https://github.com/RADENzzz/coe-nnect/blob/main/LICENSE)

</div>

Most universities still build faculty timetables by hand, moving blocks around a spreadsheet until nothing overlaps. **CoE-NNECT** replaces that with a real system: a monorepo web platform that validates schedules against **27 scheduling rules**, runs role-based review and approval workflows, and generates conflict-free timetables with a **constraint-programming solver**.

**What it does**

- Manages departments, terms, faculty, rooms, subjects, sections, and prospectuses.
- Creates, validates, reviews, approves, and publishes class schedules end to end.
- Enforces constraints for conflicts, faculty qualifications, teaching loads, and room suitability.
- Gives deans, department heads, and administrators dedicated role-based workspaces.
- Imports prospectus data straight from PDFs using editor-defined regions.
- Ships timetables, reports, audit history, notifications, and in-app chat.

**How it's built**

```text
React + Vite  ──►  NestJS API  ──►  Supabase (PostgreSQL + Auth)
                       │
                       ├──►  TypeScript rules engine (27 constraints)
                       ├──►  Python OR-Tools solver (CP-SAT)
                       └──►  FastAPI prospectus parser (PDF → data)
```

| Snapshot | Details |
| :-- | :-- |
| **Scope** | 78 / 79 functional requirements delivered (~99%) |
| **Correctness** | 27 constraint rules · 190 passing tests |
| **Architecture** | pnpm monorepo · 7 workspaces · shared rules package |
| **CI/CD** | 4 GitHub Actions pipelines · Playwright end-to-end suite |
| **Deployment** | Railway (API + Python services) · Vercel (frontend) |

**Stack:** `TypeScript` · `NestJS` · `React` · `Tailwind CSS` · `React Query` · `Zustand` · `Python` · `OR-Tools` · `PostgreSQL` · `Supabase` · `Docker` · `GitHub Actions`

<details>
<summary><b>Watch the auto-scheduler generate a timetable</b></summary>

<br />

<p align="center">
  <img src="https://raw.githubusercontent.com/RADENzzz/coe-nnect/main/docs/demo.gif" width="90%" alt="CoE-NNECT automatic schedule generation demo" />
</p>

</details>

<br />

## Tech Stack

<table align="center">
  <tr>
    <td align="right"><b>Languages</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=ts,py,go,rust,cpp,swift" height="40" alt="TypeScript, Python, Go, Rust, C++, Swift" />
    </td>
  </tr>
  <tr>
    <td align="right"><b>Frontend</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,flutter" height="40" alt="React, Next.js, Tailwind CSS, Flutter" />
    </td>
  </tr>
  <tr>
    <td align="right"><b>Backend &amp; Data</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=nodejs,nestjs,express,postgres,supabase" height="40" alt="Node.js, NestJS, Express, PostgreSQL, Supabase" />
    </td>
  </tr>
  <tr>
    <td align="right"><b>Systems &amp; Creative</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=godot,blender,raspberrypi,arduino" height="40" alt="Godot, Blender, Raspberry Pi, Arduino" />
    </td>
  </tr>
  <tr>
    <td align="right"><b>Tooling</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=git,github,githubactions,docker,vite,vercel" height="40" alt="Git, GitHub, GitHub Actions, Docker, Vite, Vercel" />
    </td>
  </tr>
</table>

<br />

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=RADENzzz&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=6C63FF&icon_color=00D2FF&text_color=C9D1D9&rank_icon=github" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RADENzzz&layout=compact&langs_count=8&hide=html,css&hide_border=true&bg_color=0D1117&title_color=6C63FF&text_color=C9D1D9" alt="Top languages" />

<br />

<img width="70%" src="https://streak-stats.demolab.com?user=RADENzzz&hide_border=true&background=0D1117&stroke=6C63FF&ring=6C63FF&fire=00D2FF&currStreakLabel=6C63FF&sideLabels=C9D1D9&dates=8B949E&currStreakNum=FFFFFF&sideNums=FFFFFF" alt="GitHub streak" />

</div>

<br />

## Contribution Graph

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RADENzzz/RADENzzz/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/RADENzzz/RADENzzz/output/github-contribution-grid-snake.svg" />
    <img alt="Contribution grid snake animation" src="https://raw.githubusercontent.com/RADENzzz/RADENzzz/output/github-contribution-grid-snake.svg" width="100%" />
  </picture>
</div>

<br />

## Let's Connect

<div align="center">

<a href="https://www.linkedin.com/in/alrhaden-javier-86b89428b/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" height="32" alt="LinkedIn" />
</a>
<a href="https://www.facebook.com/Alrhaden.Javier">
  <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" height="32" alt="Facebook" />
</a>
<a href="https://www.youtube.com/@AlrhadenJavier">
  <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" height="32" alt="YouTube" />
</a>
<a href="https://github.com/RADENzzz?tab=repositories">
  <img src="https://img.shields.io/badge/More%20Projects-181717?style=for-the-badge&logo=github&logoColor=white" height="32" alt="More projects" />
</a>

<br /><br />

<i>Always up for a good build | let's make something worth shipping.</i>

</div>

<br />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D2FF,100:6C63FF&height=120&section=footer&fontSize=14" width="100%" alt="Footer" />
