<div align="center">

# ⚡ HOSSAM TOHAMY

### `BACK-END .NET DEVELOPER`

**Clean Architecture · CQRS · Authentication Systems · Real-Time Applications**

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2500&pause=700&color=512BD4&center=true&vCenter=true&width=850&lines=ASP.NET+Core+%7C+Web+API+%7C+C%23;Clean+Architecture+%7C+CQRS+%7C+MediatR;JWT+%7C+Refresh+Tokens+%7C+OTP+%7C+2FA+%7C+OAuth;SignalR+%7C+Redis+%7C+Real-Time+Systems;SQL+Server+%7C+EF+Core+%7C+PostgreSQL;Building+Secure+%26+Scalable+Backend+Systems" alt="Typing SVG" />

<br>

<a href="https://github.com/HossamTohamy1">
<img src="https://img.shields.io/badge/GitHub-HossamTohamy1-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/hossam-tohamy-a4763a350/">
<img src="https://img.shields.io/badge/LinkedIn-Hossam%20Tohamy-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://discord.gg/1257316206638010408">
<img src="https://img.shields.io/badge/Discord-Connect-5865F2?style=for-the-badge&logo=discord&logoColor=white"/>
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=HossamTohamy1&label=PROFILE%20VIEWS&color=512BD4&style=for-the-badge"/>

<br><br>

<img src="https://skillicons.dev/icons?i=cs,dotnet,mssql,postgres,mongodb,redis,docker,git,github&theme=dark" />

</div>

---

# 🧠 ABOUT ME

```csharp
public sealed class HossamTohamy
{
    public string Role =>
        "Back-End .NET Developer";

    public string MainStack =>
        "C# + ASP.NET Core + SQL Server";

    public string Architecture =>
        "Clean Architecture + CQRS + MediatR";

    public string Focus =>
        "Authentication + Authorization + Real-Time Systems";

    public string EngineeringStyle =>
        "Clean. Secure. Scalable. Maintainable.";

    public string Mindset =>
        "Build it. Break it. Understand it. Improve it.";

    public string Mission =>
        "Turning complex problems into production-ready backend systems.";
}
```

> ### ⚡ I don't just write endpoints. I build systems.

I'm a **Back-End .NET Developer** studying Computer Science at **Thebes Higher Institute of Management**, focused on designing and building **secure, scalable, maintainable backend systems**.

My strongest area is the **.NET ecosystem**, especially **ASP.NET Core, Web API, Entity Framework Core, SQL Server, Clean Architecture, CQRS, MediatR, Authentication, Authorization, Redis, and Real-Time Communication**.

I've also built applications across **React, Angular, Laravel, Node.js, Python/FastAPI, and Flutter**, giving me a broader understanding of how backend systems interact with real-world clients.

---

# ⚔️ CORE ARSENAL

<div align="center">

### 🔥 BACKEND

<img src="https://skillicons.dev/icons?i=cs,dotnet,redis,docker,postman&theme=dark" />

<br><br>

### 🗄️ DATABASES

<img src="https://skillicons.dev/icons?i=mssql,postgres,mongodb&theme=dark" />

<br><br>

### 🌐 FRONTEND

<img src="https://skillicons.dev/icons?i=angular,react,ts,js,html,css&theme=dark" />

<br><br>

### 🧰 OTHER STACKS

<img src="https://skillicons.dev/icons?i=laravel,php,nodejs,python,fastapi,flutter,dart&theme=dark" />

<br><br>

### 🛠️ TOOLS

<img src="https://skillicons.dev/icons?i=docker,git,github,postman,figma&theme=dark" />

</div>

---

# 🏗️ ENGINEERING ARCHITECTURE

I prefer designing systems around clear boundaries, separation of concerns, and maintainable business logic.

```text
                         ┌─────────────────────┐
                         │       CLIENT        │
                         │ Web / Mobile / API  │
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │     ASP.NET CORE    │
                         │       WEB API       │
                         └──────────┬──────────┘
                                    │
                                    ▼
              ┌────────────────────────────────────────┐
              │          CLEAN ARCHITECTURE             │
              │                                        │
              │  ┌────────────┐                        │
              │  │     API    │                        │
              │  └─────┬──────┘                        │
              │        ▼                               │
              │  ┌────────────┐                        │
              │  │ Application│  ← CQRS / MediatR     │
              │  └─────┬──────┘                        │
              │        ▼                               │
              │  ┌────────────┐                        │
              │  │   Domain   │  ← Business Rules     │
              │  └─────┬──────┘                        │
              │        ▼                               │
              │  ┌────────────┐                        │
              │  │Infrastructure│ ← EF / Services     │
              │  └────────────┘                        │
              └────────────────────┬───────────────────┘
                                   │
                  ┌────────────────┼────────────────┐
                  ▼                ▼                ▼
            ┌────────────┐   ┌────────────┐   ┌────────────┐
            │ SQL Server │   │   Redis    │   │  External  │
            │  EF Core   │   │   Cache    │   │  Services  │
            └────────────┘   └────────────┘   └────────────┘
```

### 🧩 Architecture & Engineering

`Clean Architecture` · `CQRS` · `MediatR` · `SOLID` · `Clean Code` · `Dependency Injection` · `Design Patterns` · `Repository Pattern` · `Service Layer` · `DTOs` · `FluentValidation`

---

# 🔐 SECURITY IS NOT OPTIONAL

Authentication is one of the areas I enjoy going deepest into.

Not just:

```text
Login → JWT → Done
```

But:

```text
                         🔐 AUTHENTICATION SYSTEM
                                  │
          ┌───────────────────────┼───────────────────────┐
          ▼                       ▼                       ▼
       REGISTER                  LOGIN                   OAUTH
          │                       │                       │
          ▼                       ▼                       ▼
   EMAIL VERIFICATION       JWT AUTHENTICATION      EXTERNAL LOGIN
                                  │
                       ┌──────────┴──────────┐
                       ▼                     ▼
                 ACCESS TOKEN         REFRESH TOKEN
                       │                     │
                       └──────────┬──────────┘
                                  ▼
                           AUTHORIZATION
                                  │
                  ┌───────────────┼───────────────┐
                  ▼               ▼               ▼
                 OTP             2FA        ROLES / CLAIMS
```

### 🛡️ Security Stack

`JWT` · `Refresh Tokens` · `Token Rotation` · `Token Revocation` · `OTP` · `2FA` · `OAuth` · `Email Verification` · `Password Reset` · `Role-Based Authorization` · `Claims`

---

# 🧬 AUTHENTICATION SERVICE

### `Secure Authentication Backend`

A dedicated authentication backend designed around **Clean Architecture + CQRS**.

```text
REGISTER
    │
    ▼
EMAIL VERIFICATION
    │
    ▼
LOGIN
    │
    ▼
ACCESS TOKEN + REFRESH TOKEN
    │
    ▼
AUTHORIZATION
    │
    ├───────────────┐
    ▼               ▼
   OTP              2FA
    │               │
    └───────┬───────┘
            ▼
     SECURE SESSION
            │
     ┌──────┴──────┐
     ▼             ▼
 LOGOUT ONE     LOGOUT ALL
 DEVICE           DEVICES
```

### Included

* ✅ Registration
* ✅ Email Verification
* ✅ Login
* ✅ JWT Access Tokens
* ✅ Refresh Tokens
* ✅ Refresh Token Rotation
* ✅ Token Revocation
* ✅ Logout From One Device
* ✅ Logout From All Devices
* ✅ Password Reset
* ✅ OTP
* ✅ Two-Factor Authentication
* ✅ OAuth
* ✅ Role-Based Authorization

### Architecture

`Clean Architecture` → `CQRS` → `MediatR` → `FluentValidation` → `EF Core`

---

# ⚡ REAL-TIME ENGINEERING

## 💬 ChatHub — Real-Time Communication

A real-time communication project built around **SignalR, WebSockets, Redis and backend event-driven communication**.

```text
                 USER A
                    │
                    │ MESSAGE
                    ▼
              ┌─────────────┐
              │   SIGNALR   │
              │     HUB     │
              └──────┬──────┘
                     │
            ┌────────┴────────┐
            ▼                 ▼
         REDIS             DATABASE
            │                 │
            ▼                 ▼
        Presence          Messages
        Caching            Storage
            │
            ▼
      REAL-TIME EVENTS
            │
            ▼
                 USER B
```

### ⚡ Features

`Real-Time Messaging` · `Online/Offline Presence` · `Notifications` · `File Sharing` · `Image Sharing` · `Voice Communication` · `SignalR` · `WebSockets` · `Redis` · `Authentication` · `Authorization`

---

# 🚀 FEATURED PROJECTS

## 🛒 [Ecommerc_Rose](https://github.com/HossamTohamy1/Ecommerc_Rose)

<img src="https://skillicons.dev/icons?i=cs,dotnet&theme=dark" height="28"/>

E-commerce backend built around **Clean Architecture and CQRS/MediatR**, with a focus on modular business logic and maintainability.

**Highlights**

* 🛒 Cart Management
* 👤 User Management
* 🏷️ Offers
* 🧾 Audit Logging
* 📦 Order Management
* 🔔 Order Status Notifications
* 🧩 Mapster
* ✅ FluentValidation

`ASP.NET Core` `Clean Architecture` `CQRS` `MediatR` `Mapster` `FluentValidation`

---

## 🏨 [Hotel_System](https://github.com/HossamTohamy1/Hotel_System)

<img src="https://skillicons.dev/icons?i=cs,dotnet&theme=dark" height="28"/>

Hotel reservation backend designed around **Clean Architecture**, with advanced authorization and payment integration.

**Highlights**

* 🏨 Hotel Reservation
* 🔐 Dynamic Permission-Based Authorization
* 💳 Stripe Integration
* 📝 Structured Logging
* 🧩 Clean Architecture
* ⚡ CQRS

`ASP.NET Core` `Clean Architecture` `CQRS` `Stripe` `Serilog`

---

## 📝 [ExaminationSystem](https://github.com/HossamTohamy1/ExaminationSystem)

<img src="https://skillicons.dev/icons?i=cs,dotnet&theme=dark" height="28"/>

Examination management system built using a **layered architecture approach**.

`ASP.NET Core` `Layered Architecture` `EF Core`

---

## 🧩 [ModularERP](https://github.com/HossamTohamy1/ModularERP) · `PRIVATE`

<img src="https://skillicons.dev/icons?i=cs,dotnet&theme=dark" height="28"/>

A modular ERP backend focused on business-oriented application structure.

`C#` `.NET`

---

## 📍 [Tracking](https://github.com/HossamTohamy1/Tracking) + [Tracking_React](https://github.com/HossamTohamy1/Tracking_React)

<img src="https://skillicons.dev/icons?i=cs,dotnet,react,ts&theme=dark" height="28"/>

Tracking platform combining a **.NET backend** with a **React + TypeScript frontend**.

`ASP.NET Core` `C#` `React` `TypeScript`

---

## 🛍️ [Ecommerc_.NET_Flutter](https://github.com/HossamTohamy1/Ecommerc_.NET_Flutter)

<img src="https://skillicons.dev/icons?i=cs,dotnet,flutter,dart&theme=dark" height="28"/>

E-commerce ecosystem connecting a **.NET backend** with a **Flutter mobile client**.

`ASP.NET Core` `Flutter` `Dart`

---

# 🌎 OTHER PROJECTS

| Repository                                                                            | Stack                  |
| :------------------------------------------------------------------------------------ | :--------------------- |
| [Tourism_System](https://github.com/HossamTohamy1/Tourism_System)                     | `JavaScript`           |
| [Hotel_System_Laravel](https://github.com/HossamTohamy1/Hotel_System_Laravel)         | `Laravel` `PHP`        |
| [Ecommerc_laravel](https://github.com/HossamTohamy1/Ecommerc_laravel)                 | `Laravel` `PHP`        |
| [Ecommerc_node.js](https://github.com/HossamTohamy1/Ecommerc_node.js)                 | `Node.js` `JavaScript` |
| [Ecommerce_Python-FastApi](https://github.com/HossamTohamy1/Ecommerce_Python-FastApi) | `Python` `FastAPI`     |
| [Chat_Websocket](https://github.com/HossamTohamy1/Chat_Websocket)                     | `PHP` `WebSocket`      |
| [Saraha](https://github.com/HossamTohamy1/Saraha)                                     | `Laravel` `Blade`      |
| [School](https://github.com/HossamTohamy1/School)                                     | `C#` `.NET`            |
| [Classes_Managment-.NET-](https://github.com/HossamTohamy1/Classes_Managment-.NET-)   | `C#` `.NET`            |
| [Hosptial](https://github.com/HossamTohamy1/Hosptial)                                 | `C#` `.NET`            |
| [Flutter](https://github.com/HossamTohamy1/Flutter)                                   | `Flutter` `Dart`       |

---

# 🧰 TECH STACK

<table>
<tr>
<td align="center" width="25%"><b>Core Backend</b></td>
<td>
<img src="https://skillicons.dev/icons?i=cs,dotnet&theme=dark"/>
<br>
<code>ASP.NET Core</code> <code>Web API</code> <code>EF Core</code> <code>LINQ</code>
</td>
</tr>

<tr>
<td align="center"><b>Architecture</b></td>
<td>
<code>Clean Architecture</code>
<code>CQRS</code>
<code>MediatR</code>
<code>SOLID</code>
<code>Design Patterns</code>
<code>Dependency Injection</code>
</td>
</tr>

<tr>
<td align="center"><b>Security</b></td>
<td>
<code>JWT</code>
<code>Refresh Tokens</code>
<code>OTP</code>
<code>2FA</code>
<code>OAuth</code>
<code>Claims</code>
</td>
</tr>

<tr>
<td align="center"><b>Data & Cache</b></td>
<td>
<img src="https://skillicons.dev/icons?i=mssql,postgres,mongodb,redis&theme=dark"/>
</td>
</tr>

<tr>
<td align="center"><b>Frontend</b></td>
<td>
<img src="https://skillicons.dev/icons?i=angular,react,ts,js,html,css&theme=dark"/>
</td>
</tr>

<tr>
<td align="center"><b>Other Ecosystems</b></td>
<td>
<img src="https://skillicons.dev/icons?i=laravel,php,nodejs,python,fastapi,flutter,dart&theme=dark"/>
</td>
</tr>

<tr>
<td align="center"><b>Tools & DevOps</b></td>
<td>
<img src="https://skillicons.dev/icons?i=docker,git,github,postman,figma&theme=dark"/>
</td>
</tr>
</table>

---

# 👨‍🏫 TEACHING & KNOWLEDGE SHARING

Alongside software development, I teach technical content through **eYouth Academy and DECI** programs.

My teaching areas include:

* 🔐 Cybersecurity Fundamentals
* 🌐 Web Development
* 📊 Data Science & EDA
* 🤖 AI Concepts
* 🗄️ Databases
* 💻 Computer Science Fundamentals

### Teaching Philosophy

```text
REAL-WORLD ANALOGY
        ↓
FORMAL DEFINITION
        ↓
TECHNICAL EXPLANATION
        ↓
HANDS-ON EXAMPLE
        ↓
STUDENT PRACTICE
```

> **Understand the concept → see it in action → build it yourself.**

---

# 📊 GITHUB PERFORMANCE

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=HossamTohamy1&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=HossamTohamy1&layout=compact&theme=tokyonight&hide_border=true" width="49%"/>

<br><br>

<img src="https://streak-stats.demolab.com?user=HossamTohamy1&theme=tokyonight&hide_border=true" width="70%"/>

</div>

---

# 🏆 GITHUB TROPHIES

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=HossamTohamy1&theme=tokyonight&no-frame=true&no-bg=true&margin-w=10&row=1" />

</div>

---

# 📈 CONTRIBUTION GRAPH

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=HossamTohamy1&theme=tokyo-night&hide_border=true&area=true" width="100%"/>

</div>

---

# 🐍 CONTRIBUTION SNAKE

<div align="center">

<img src="https://raw.githubusercontent.com/HossamTohamy1/HossamTohamy1/output/github-contribution-grid-snake-dark.svg" alt="GitHub Contribution Snake" />

</div>

---

# 🧠 ENGINEERING MINDSET

```text
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│                  DON'T JUST MAKE IT WORK.                    │
│                                                              │
│                       MAKE IT CLEAN.                         │
│                       MAKE IT SECURE.                        │
│                       MAKE IT SCALABLE.                      │
│                       MAKE IT MAINTAINABLE.                  │
│                                                              │
│                     THEN MAKE IT FAST.                       │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

### My Development Loop

```text
        PROBLEM
           │
           ▼
        ANALYZE
           │
           ▼
         DESIGN
           │
           ▼
         BUILD
           │
           ▼
         TEST
           │
           ▼
         BREAK
           │
           ▼
       UNDERSTAND
           │
           ▼
        IMPROVE
           │
           └───────────────► REPEAT
```

---

# ⚽ BEYOND THE CODE

<div align="center">

`💻 Backend Development`   `⚽ Football`   `🏋️ Gym`   `🧠 Problem Solving`   `🔥 Learning`   `🚀 Building`

</div>

---

<div align="center">

# ⚡ BUILDING SYSTEMS, NOT JUST ENDPOINTS.

### `C#` · `.NET` · `ASP.NET Core` · `CQRS` · `Clean Architecture` · `SQL Server` · `Redis`

<br>

**Code it. Break it. Understand it. Improve it.** 🚀

<br><br>

<a href="https://github.com/HossamTohamy1">
<img src="https://img.shields.io/badge/EXPLORE_MY_GITHUB-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/hossam-tohamy-a4763a350/">
<img src="https://img.shields.io/badge/CONNECT_ON_LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

</div>
