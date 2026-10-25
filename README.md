<a id="readme-top"></a>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:080014,25:512BD4,55:7C3AED,80:00BFFF,100:00E5FF&height=250&section=header&text=Hossam%20Tohamy&fontSize=64&fontColor=FFFFFF&fontAlignY=36&desc=Back-End%20.NET%20Developer%20%E2%80%A2%20CS%20Student%20%E2%80%A2%20Instructor&descAlignY=57&descSize=18&animation=twinkling" width="100%" alt="Hossam Tohamy — Back-End .NET Developer"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=2600&pause=800&color=00E5FF&center=true&vCenter=true&width=760&lines=Back-End+.NET+Developer;Clean+Architecture+%C2%B7+CQRS+%C2%B7+MediatR;JWT+%C2%B7+Refresh+Token+Rotation+%C2%B7+2FA+%C2%B7+OAuth;SignalR+%C2%B7+Redis+%C2%B7+Real-Time+Systems;Building+backends%2C+not+just+endpoints." alt="Typing animation"/>

<br/>

<a href="https://github.com/HossamTohamy1"><img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://www.linkedin.com/in/hossam-tohamy-a4763a350/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://discord.com/users/1257316206638010408"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"/></a>
<img src="https://komarev.com/ghpvc/?username=HossamTohamy1&label=Profile%20Views&color=7C3AED&style=for-the-badge" alt="Profile views"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:512BD4,50:7C3AED,100:00E5FF&height=3&section=header" width="100%" alt=""/>

## How I Build a Backend

```mermaid
flowchart TB
    client(["Client · Web / Mobile"])

    subgraph api ["API Layer"]
        ep["ASP.NET Core Endpoints"]
    end

    subgraph rt ["Real-Time"]
        hub["SignalR Hub"]
    end

    subgraph app ["Application Layer"]
        med{{"MediatR Pipeline<br/>Validation · Logging"}}
        cmd["Commands"]
        qry["Queries"]
    end

    subgraph core ["Domain"]
        ent["Entities · Business Rules"]
    end

    subgraph infra ["Infrastructure"]
        db[("SQL Server<br/>EF Core")]
        cache[("Redis<br/>Cache")]
        ext["Stripe · Email"]
    end

    client -- "HTTPS + JWT" --> ep
    ep --> med
    med --> cmd & qry
    cmd --> ent
    cmd --> db
    cmd --> ext
    qry --> cache
    cache -. "miss" .-> db
    cmd -. "events" .-> hub
    hub -. "live updates" .-> client

    classDef svc fill:#512BD4,stroke:#7C3AED,color:#FFFFFF
    classDef store fill:#0E7490,stroke:#00E5FF,color:#FFFFFF
    classDef outer fill:#111827,stroke:#00BFFF,color:#FFFFFF
    class ep,hub,med,cmd,qry,ent svc
    class db,cache store
    class client,ext outer
    style api fill:#7C3AED14,stroke:#7C3AED
    style rt fill:#00BFFF14,stroke:#00BFFF
    style app fill:#7C3AED14,stroke:#7C3AED
    style core fill:#00BFFF14,stroke:#00BFFF
    style infra fill:#00E5FF14,stroke:#00E5FF
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:512BD4,50:7C3AED,100:00E5FF&height=3&section=header" width="100%" alt=""/>

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [TimeTable](https://github.com/HossamTohamy1/Time-Mangments)

**Configuration-driven school & university timetabling — bilingual AR / EN.**

Generates timetables with the OR-Tools CP-SAT solver, pushes live changes over SignalR, and exports to PDF & Excel. Every institution type is data, not code.

<img src="https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET 10"/>
<img src="https://img.shields.io/badge/Clean_Architecture-7C3AED?style=flat-square" alt="Clean Architecture"/>
<img src="https://img.shields.io/badge/SignalR-00BFFF?style=flat-square" alt="SignalR"/>
<img src="https://img.shields.io/badge/OR--Tools-0891B2?style=flat-square" alt="OR-Tools"/>
<img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white" alt="Angular"/>

</td>
<td width="50%" valign="top">

### [Tracking](https://github.com/HossamTohamy1/Tracking)

**Import & shipment tracking platform.**

Customers request an import, get the full cost calculated (shipping, customs, fees), pay by card, and follow their container stage by stage. Ships with a [React 19 PWA client](https://github.com/HossamTohamy1/Front_Tracking).

<img src="https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET 10"/>
<img src="https://img.shields.io/badge/CQRS_+_MediatR-7C3AED?style=flat-square" alt="CQRS + MediatR"/>
<img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white" alt="Stripe"/>
<img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT"/>
<img src="https://img.shields.io/badge/Serilog-1E293B?style=flat-square" alt="Serilog"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Loma — AuraCommerce](https://github.com/HossamTohamy1/Loma)

**Online store API with a built-in theme customizer.**

Products, categories, cart and orders, plus a no-code store designer. Tuned with in-memory caching and Brotli / Gzip compression; serves its Angular build from `wwwroot`.

<img src="https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET 8"/>
<img src="https://img.shields.io/badge/EF_Core-7C3AED?style=flat-square" alt="EF Core"/>
<img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT"/>
<img src="https://img.shields.io/badge/Caching-0891B2?style=flat-square" alt="Caching"/>

</td>
<td width="50%" valign="top">

### [Hotel System](https://github.com/HossamTohamy1/Hotel_System)

**Hotel operations back-end.**

Rooms & facilities, multi-room reservations, offers, payments and reviews — with role- and feature-based permissions so every employee can do exactly what they should.

<img src="https://img.shields.io/badge/.NET_9-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET 9"/>
<img src="https://img.shields.io/badge/Layered_Architecture-7C3AED?style=flat-square" alt="Layered Architecture"/>
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="SQL Server"/>
<img src="https://img.shields.io/badge/Authorization-DC2626?style=flat-square" alt="Authorization"/>

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br/>

| Project | What it is | Stack |
| :-- | :-- | :-- |
| [School](https://github.com/HossamTohamy1/School) | School management API with paged results | .NET 9 · CQRS · MediatR · FluentValidation |
| [Examination System](https://github.com/HossamTohamy1/ExaminationSystem) | Online exams with automatic grading | .NET 9 · ASP.NET Core Identity · Repository pattern |
| [Hospital](https://github.com/HossamTohamy1/Hosptial) | Patients, diagnoses & prescriptions web app | ASP.NET Core MVC · Identity · SMTP |
| [Tourism System](https://github.com/HossamTohamy1/Tourism_System) | Tourism booking API with online payments | Node.js · Express · MongoDB · Stripe |
| [Front Tracking](https://github.com/HossamTohamy1/Front_Tracking) | Client app for the Tracking platform | React 19 · TypeScript · Vite · PWA |
| [Classes Management](https://github.com/HossamTohamy1/Classes_Managment) | Class management dashboard | Angular 20 · Angular Material |

</details>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:512BD4,50:7C3AED,100:00E5FF&height=3&section=header" width="100%" alt=""/>

## Tech Stack

<table>
<tr>
<td align="center" width="130"><b>Back-End</b></td>
<td><img src="https://skillicons.dev/icons?i=cs,dotnet&theme=dark" alt="C#, .NET"/><br/><code>C#</code> <code>ASP.NET Core</code> <code>Web API</code> <code>MVC</code> <code>EF Core</code> <code>LINQ</code> <code>SignalR</code></td>
</tr>
<tr>
<td align="center"><b>Libraries</b></td>
<td><code>MediatR</code> <code>FluentValidation</code> <code>AutoMapper</code> <code>Serilog</code> <code>Identity</code> <code>Swagger</code> <code>QuestPDF</code> <code>OR-Tools</code></td>
</tr>
<tr>
<td align="center"><b>Data</b></td>
<td><img src="https://skillicons.dev/icons?i=mssql,postgres,mongodb,redis&theme=dark" alt="SQL Server, PostgreSQL, MongoDB, Redis"/><br/><code>SQL Server</code> <code>PostgreSQL</code> <code>MongoDB</code> <code>Redis</code></td>
</tr>
<tr>
<td align="center"><b>Tools</b></td>
<td><img src="https://skillicons.dev/icons?i=docker,git,github,postman,visualstudio,figma&theme=dark" alt="Docker, Git, GitHub, Postman, Visual Studio, Figma"/><br/><code>Docker</code> <code>Git</code> <code>GitHub</code> <code>Postman</code> <code>Visual Studio</code> <code>Figma</code></td>
</tr>
</table>

<details>
<summary><b>Beyond .NET — comfortable crossing the stack when the project needs it</b></summary>
<br/>

<img src="https://skillicons.dev/icons?i=angular,react,ts,js,nodejs,express,python,fastapi,laravel,php,flutter,dart&theme=dark" alt="Other stacks"/>

`Angular` · `React` · `TypeScript` · `JavaScript` · `Node.js` · `Express` · `Python` · `FastAPI` · `Laravel` · `PHP` · `Flutter`

</details>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:512BD4,50:7C3AED,100:00E5FF&height=3&section=header" width="100%" alt=""/>

## Leveling Up

- [x] ASP.NET Core Web API, EF Core & SQL Server
- [x] Clean Architecture + CQRS with MediatR
- [x] JWT, refresh-token rotation, OTP & 2FA
- [x] Real-time apps with SignalR
- [ ] Distributed caching with Redis
- [ ] Messaging & event-driven architecture
- [ ] Containerized, scalable APIs with Docker

<div align="center">

`BUILDING` ➜ `LEARNING` ➜ `REFACTORING` ➜ `SCALING`

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:512BD4,50:7C3AED,100:00E5FF&height=3&section=header" width="100%" alt=""/>

## Teaching

<img src="https://img.shields.io/badge/eYouth_Academy-512BD4?style=for-the-badge" alt="eYouth Academy"/>
<img src="https://img.shields.io/badge/DECI-00BFFF?style=for-the-badge" alt="DECI"/>

I teach **Cybersecurity**, **Web Development**, **Data Science & EDA**, **AI** and **Databases**.
`LEARN` ➜ `BUILD` ➜ `SHARE`

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:512BD4,50:7C3AED,100:00E5FF&height=3&section=header" width="100%" alt=""/>

## GitHub Analytics

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=HossamTohamy1&layout=compact&langs_count=6&hide=html,css,scss,cmake,c%2B%2B,swift&hide_border=true&border_radius=10&card_width=320&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=HossamTohamy1&layout=compact&langs_count=6&hide=html,css,scss,cmake,c%2B%2B,swift&hide_border=true&border_radius=10&card_width=320&bg_color=F6F8FA&title_color=512BD4&text_color=24292F" height="170" alt="Top languages"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=HossamTohamy1&hide_border=true&border_radius=10&background=0D1117&stroke=30363D&ring=7C3AED&fire=00E5FF&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=00E5FF&sideLabels=C9D1D9&dates=8B949E"/>
  <img src="https://streak-stats.demolab.com?user=HossamTohamy1&hide_border=true&border_radius=10&background=F6F8FA&stroke=D0D7DE&ring=7C3AED&fire=0891B2&currStreakNum=24292F&sideNums=24292F&currStreakLabel=512BD4&sideLabels=57606A&dates=57606A" height="170" alt="GitHub streak"/>
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=HossamTohamy1&theme=github_dark"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=HossamTohamy1&theme=github" width="90%" alt="Contribution graph"/>
</picture>

### Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/HossamTohamy1/HossamTohamy1/output/github-contribution-grid-snake-dark.svg"/>
  <img src="https://raw.githubusercontent.com/HossamTohamy1/HossamTohamy1/output/github-contribution-grid-snake.svg" alt="Contribution snake"/>
</picture>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:512BD4,50:7C3AED,100:00E5FF&height=3&section=header" width="100%" alt=""/>

<div align="center">

**Outside the code:** Football · Gym · Always learning

<img src="https://capsule-render.vercel.app/api?type=transparent&height=90&text=BUILD.%20BREAK.%20FIX.%20SHIP.%20REPEAT.&fontSize=26&fontColor=00E5FF&fontAlignY=50&animation=twinkling" alt="Build. Break. Fix. Ship. Repeat."/>

<a href="https://github.com/HossamTohamy1"><img src="https://img.shields.io/badge/Explore_my_repos-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="Explore my repos"/></a>
<a href="https://www.linkedin.com/in/hossam-tohamy-a4763a350/"><img src="https://img.shields.io/badge/Let's_connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Let's connect"/></a>

<sub><a href="#readme-top">Back to top</a></sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00E5FF,35:00BFFF,65:7C3AED,100:512BD4&height=140&section=footer&animation=twinkling" width="100%" alt=""/>
