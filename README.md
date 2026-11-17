<h1 align="center">Hi there, I'm Hrithik Saha <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px"/></h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=3178C6&center=true&vCenter=true&width=600&lines=Computer+Science+%26+Engineering+Graduate;BRAC+University;Full-Stack+%7C+Databases+%7C+Networking+%7C+Systems;Always+learning+something+new" alt="Typing SVG" />
</p>

<p align="center">
I build things end-to-end — from relational schema design and backend logic to the interface on top,
with the network and systems layer underneath it all. My coursework and projects span web development
across three different stacks, database systems, systems programming, and enterprise networking —
I pick whichever tool actually fits the problem rather than sticking to one.
</p>

<br/>

## 🧠 What I bring

- **Multi-stack full-stack development** — shipped complete apps in three different stacks: Django + MySQL, the MERN stack (React/Node/Express/MongoDB), and Next.js + ASP.NET Core + PostgreSQL, so I ramp up on a new team's stack fast
- **Database-first thinking** — comfortable designing relational schemas and writing the logic that keeps data consistent (append-only ledgers, signed-quantity stock tracking, row-level locking with `SELECT ... FOR UPDATE`)
- **Networking fundamentals** — hands-on with VLSM subnetting, dynamic (RIPv2) and static routing, DHCP, and DNS/mail server setup, designed and configured in Cisco Packet Tracer for a 1,300+ device network
- **Systems-level curiosity** — went beyond typical coursework to build a write-ahead-logging journaling layer in C, the same crash-consistency technique ext3/ext4 use
- **Engineering discipline** — role-based auth, server-side business-rule enforcement, and automated tests (xUnit, Django `TestCase`) aren't afterthoughts in my projects
- **Fast learner & team player** — every project below used a different language or stack, built under course or recruitment-task deadlines; some I built entirely on my own, others as part of a 2–3 person team

<br/>

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,django,flask,js,ts,react,nodejs,express,nextjs,dotnet,cs,c,mysql,postgres,mongodb,html,css&theme=dark" alt="tech stack icons"/>
</p>

<br/>

## 📌 Projects

<table width="100%">
<tr>
<td width="50%" valign="top">

### 🩸 [LifeBridge](https://github.com/hrithikcse/LifeBridge-Blood-Bank-Management-System)
**Blood Bank Management System — CSE370 Database Systems**

Django + MySQL system connecting donors, recipients, and branch blood banks across Dhaka zones. Stock is tracked through an append-only ledger (signed quantity: + collected / − issued), never a raw counter, so every bag is auditable and branch totals can be reconciled at any time. Concurrent stock updates are made safe with `SELECT ... FOR UPDATE` row locking, and the suite carries 19 Django tests over stock math and access control.

`Python` `Django` `MySQL` `Database Design`

</td>
<td width="50%" valign="top">

### 🗂️ [Journaling Filesystem](https://github.com/hrithikcse/Journaling-Filesystem-with-Transaction-Logging)
**Transaction-Logged Virtual Filesystem (VSFS)**

A C implementation of write-ahead logging for a virtual filesystem — metadata changes are journaled with record + commit entries before being applied to disk, and replayed on recovery, the same crash-consistency technique ext3/ext4 use. Implements full inode management (create/read/write/delete) over a simulated disk image with a defined block layout.

`C` `Systems Programming` `OS`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏙️ [Smart City Operations Network](https://github.com/hrithikcse/Smart-City-Operations-Network)
**Enterprise Network Infrastructure Design (Cisco Packet Tracer)**

A fully configured network simulation connecting six city units (1,300+ devices) under one fault-tolerant infrastructure. Designed VLSM subnetting on a `/16` base, mixed RIPv2 dynamic routing with next-hop, exit-interface, recursive, and floating static routes (plus redistribution into RIPv2), and configured DHCP (dedicated server + relay + router-based pools), DNS, a web server, and SMTP/POP3 mail servers.

`Cisco Packet Tracer` `RIPv2` `VLSM` `DHCP/DNS` `Networking`

</td>
<td width="50%" valign="top">

### 📝 [Assignment Submission System](https://github.com/hrithikcse/Assignment-Submission-System)
**Role-Based Full-Stack Web App — Built for OnnoRokom Assistant's SE recruitment task**

A school assignment system with Admin/Teacher/Student roles. Next.js 14 + TypeScript frontend talks to an ASP.NET Core 8 Web API (PostgreSQL via EF Core), with JWT auth and every business rule — deadlines, one-submission-per-student, marks capped at max, teachers restricted to their own assignments — enforced server-side, not just in the UI. Covered by xUnit tests and documented with Swagger/OpenAPI.

`Next.js` `TypeScript` `ASP.NET Core` `C#` `PostgreSQL` `JWT`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏨 [Saha Palace and Suites](https://github.com/hrithikcse/Saha-Palace-and-Suites)
**Hotel Booking & Management System**

A Flask + Python hotel platform covering rooms across all 8 divisions and 64 districts of Bangladesh: account registration with OTP email verification, promo codes, a loyalty-points system, verified reviews (booking-gated), a wishlist, PDF invoice generation, and an admin analytics panel. Includes an AI booking assistant chatbot powered by the Cohere API.

`Python` `Flask` `SQLAlchemy` `SQLite` `Cohere API`

</td>
<td width="50%" valign="top">

### 📚 [ProjectAlexandria](https://github.com/hrithikcse/ProjectAlexandria)
**Full-Stack MERN App — CSE470 Software Engineering**

A React (Vite + Tailwind) frontend backed by a Node.js/Express REST API with MongoDB (Mongoose), built collaboratively with classmates. Includes bcrypt-hashed authentication and file uploads via Multer.

`React` `Node.js` `Express` `MongoDB`

</td>
</tr>
</table>

<br/>

## 🎯 Currently

Looking for entry-level roles across **software development, full-stack/backend engineering, and IT/networking** — my projects span three different web stacks, relational database design, enterprise networking (Cisco), and systems programming, so I'm comfortable ramping up fast on whichever foundation a team needs.

<br/>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hrithikcse&layout=compact&theme=react&hide_border=true&langs_count=8" alt="top languages"/>
</p>

<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/hrithikcse/hrithikcse/output/github-contribution-grid-snake-dark.svg" alt="contribution snake animation"/>
</p>
