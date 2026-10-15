<p align="center">
  <img src="https://raw.githubusercontent.com/dfcgaming/dfcgaming/05e7988d7c5165d6e07356790cd87ea2ef66a317/assets/header.svg" alt="Dylan — developer and owner of SiteNomads.nl" width="100%" />
</p>

<p align="center"><b>Owner of SiteNomads.nl · Full stack developer · Ethical hacker</b></p>
<p align="center">
  <a href="https://sitenomads.nl">SiteNomads.nl</a> &nbsp; / &nbsp;
  <a href="#citylife">Citylife</a> &nbsp; / &nbsp;
  <a href="#project-directory">Project directory</a> &nbsp; / &nbsp;
  <a href="https://github.com/dfcgaming?tab=repositories">Public repositories</a>
</p>

## Dylan / dfcgaming

I'm **Dylan**, known here as **dfcgaming**. I'm the **owner of [SiteNomads.nl](https://sitenomads.nl)**, a self-hosting service provider offering website development and SEO optimisation. I'm also a **full stack developer and ethical hacker**.

The technologies I know best are **Laravel, HTML, CSS, JavaScript, Node.js, and Java**. I use **Livewire** for Laravel interfaces and **SCSS** for styling. Most of my Java work is in Minecraft, where I've built roleplay systems, custom gamemodes, and tools for plugin development.

A lot of my work lives in private repositories. This page tells the stories behind those projects as well as the ones you can explore publicly. They range from **Citylife**, a Minecraft life simulator that has been a big part of my life, to hosting infrastructure, collaborative Bible study, a live riding app, and investigation software.

My interest in ethical hacking sits alongside my development work: understanding how a system behaves, where its boundaries are, and how it can be made safer. I also want to become a **private investigator to help people**. That ambition is the reason I started Timelino.

## SiteNomads.nl

**My business: self-hosting services, website development, and SEO optimisation.**

[Visit SiteNomads.nl](https://sitenomads.nl)

SiteNomads brings together the areas I work in professionally. I provide hosting services, develop websites, and work on their search-engine optimisation. Owning the business makes the environment around a website just as relevant to me as its code and design.

<table>
<tr>
<td width="33%" valign="top">
<h3>Hosting</h3>
<p>Self-hosting services for websites and applications, alongside my work on hosting infrastructure and management tools.</p>
</td>
<td width="33%" valign="top">
<h3>Web development</h3>
<p>Laravel and Livewire applications, with HTML, CSS, SCSS, and JavaScript for the frontend.</p>
</td>
<td width="33%" valign="top">
<h3>Website SEO</h3>
<p>Website optimisation for search engines, with attention to the structure and presentation of the site.</p>
</td>
</tr>
</table>

## Project directory

| Area | Project | What it is | Source |
| :--- | :--- | :--- | :--- |
| **Minecraft life simulation** | [Citylife](#citylife) | A dedicated roleplay world with banking, jobs, businesses, property, and city systems | Private |
| **Hosting & infrastructure** | [Cloud Haven](#cloud-haven) | A hosting control panel for isolated applications and connected server nodes | Private |
| **Research & investigation** | [Timelino](#timelino) | An early investigation-software project for organising and retrieving collected information | Private |
| **Reading & collaboration** | [Schrift / BibleApp](#schrift--bibleapp) | A Bible reader with translation comparison, notes, study boards, and shared sessions | Private |
| **Mobile & real-time systems** | [MotoMeeting](#motomeeting) | A riding app with live positions, communication, meetings, and traffic information | Private |
| **Minecraft horror** | [Enderman](#enderman) | An asymmetric gamemode built around a hunt, collectible pages, and changing player roles | Private |
| **Minecraft survival** | [Apocolypse](#apocolypse) | A movie-inspired zombie apocalypse project with custom combat and enemy behaviour | Private |
| **Developer tools** | [Spigot Auto Reloader](#spigot-auto-reloader) | A hot-reload helper for the Minecraft plugin development cycle | Private |
| **Browser tools** | [StructlyDiagrams](#structlydiagrams) | A static infrastructure diagram editor with JSON, SVG, and PNG export | [Public](https://github.com/dfcgaming/StructlyDiagrams) |

## Minecraft worlds and gamemodes

### Citylife

**A fully dedicated life simulator in Minecraft, and one of the projects that means the most to me.**

Citylife has been a big part of my life and my work as a developer. The idea was to build a city people could live a role in: have a job, run a business, use a bank account, own or access property, and take part in a world shaped by other players.

That meant building the systems behind daily life. A transaction needed to connect with a player's account. A job needed to belong to a business and carry its own permissions. A building needed to know who could enter or change it. Those details are what make the roleplay possible.

The project includes:

- **Banking and transactions:** bank accounts, an ATM interface, deposits, withdrawals, and in-game cash.
- **Jobs and businesses:** company registration, ownership, job roles, wage data, and player employment.
- **Property and access:** plots with owners, members, and access linked to employment.
- **Player identity and permissions:** player records, names, levels, groups, and individual permissions.
- **City interactions:** garage doors, barriers, lifts, linked controls, and factory-style block processing.
- **Administration:** tools for managing the world, players, jobs, property, and permissions.
- **Companion projects:** a phone interface with contact screens, a separate weapons module, and a custom resource pack.

The Java plugin connects to backend services through socket-based requests. Banking, employment, businesses, and player data therefore extend beyond individual in-game commands.

Citylife represents the kind of development I enjoy most: several systems working together over time, with people giving them a purpose. It is a substantial part of my Minecraft development history, rather than a small standalone plugin.

**Technologies:** Java, Spigot/Bukkit APIs, Socket.IO integration, custom inventory interfaces, backend services, and resource-pack assets.

[Public Citylife resource pack](https://github.com/dfcgaming/cityliferesourcepack)

### Enderman

**A multiplayer horror gamemode where the balance changes during the match.**

In Enderman, one player takes the Enderman role while the others become the hunted players. The players have to search the map and collect pages before time runs out. Once all pages have been collected, the Enderman becomes vulnerable and the hunted players can fight back.

That transition is the centre of the gamemode. The first part of a match is about surviving and finding the objectives; finishing them changes what both sides can do.

The project includes round timers, map configuration, player disguises, spectator handling, random power-up spawns, and light effects. The Enderman ability set includes leap, blackout, power-up blocking, and jumpscare mechanics. The opposing players have tools such as invisibility, stun, flashbangs, and slowdown effects.

**Technologies:** Java, Spigot/Bukkit, event-driven game logic, map tools, and player disguises.

### Apocolypse

**A zombie-apocalypse project inspired by movies.**

Apocolypse was a way to bring that kind of survival setting into Minecraft: dangerous infected enemies, firearms, military elements, and moments of panic.

The code explores zombies climbing obstacles, custom weapons with ammunition and reload timings, flashbangs, military NPCs, and an airstrike mechanic. Loot replenishment and airdrops were also part of the direction, with some of those systems still at a prototype stage.

The story behind it is different from Citylife. Citylife is about building ordinary life into a world; Apocolypse is about what happens when that world becomes hostile.

**Technologies:** Java, Paper/Spigot APIs, custom entities, weapons, timed effects, and resource-pack work.

[Public Apocolypse texture pack](https://github.com/dfcgaming/apocolypsetexturepack)

### Spigot Auto Reloader

**A development helper for testing changes to Minecraft plugins.**

Working on plugins involves a repeated cycle: change code, build the plugin, put it on the server, and test again. Spigot Auto Reloader came from that part of the work.

It watches plugin JAR modification times and reacts when a file changes. Its reload path can disable and re-enable the plugin, with an optional full-server reload mode. This is my hot-reload / hot-patch workflow helper; the implementation uses plugin lifecycle reloads rather than JVM bytecode replacement.

It is a smaller project than the gamemodes, but it belongs in the same story: building tools around the work I spend time doing.

**Technologies:** Java, Bukkit plugin lifecycle APIs, scheduling, and file-change detection.

## Hosting and infrastructure

### Cloud Haven

**A hosting control panel that can run on one server or connect several nodes.**

Cloud Haven brings my Laravel development and hosting interests together. It manages sites, customer and reseller accounts, application runtimes, operations, and connected nodes through a Laravel and Filament panel.

The starting point is a standalone host. Connecting nodes adds a shared site directory and routing between servers, so an entry node can direct a request to the server hosting that site.

A major part of the design is **isolation between hosted sites**. Each site gets its own Docker Compose project and data boundary. WordPress and Laravel workloads have their own web runtime, database, and Redis services; static sites avoid those unnecessary services.

The project also covers runtime provisioning, site moves, backup workflows, monitoring, and Git-based deployment features. Some operational and recovery features are still developing. Cluster-aware routing is part of the project; automatic website failover and continuous site-data replication remain future work.

For me, this project is about taking the work around hosting and making it manageable through software.

**Technologies:** Laravel, PHP, Filament, Livewire, Docker Compose, PostgreSQL, Redis, Traefik, Nginx, and PHP-FPM.

### StructlyDiagrams

**An infrastructure diagram builder that runs in the browser.**

[View repository](https://github.com/dfcgaming/StructlyDiagrams) · [Open the application](https://dfcgaming.github.io/StructlyDiagrams/)

StructlyDiagrams addresses another infrastructure problem: documenting how everything connects.

You can drag servers, firewalls, switches, VLANs, Active Directory, Microsoft 365, VPNs, and other components onto a canvas. Connections can be labeled, and an inspector holds properties, attached services, and notes.

It includes automatic layout, collapsible branches, label highlighting, and zoom-to-fit. Diagrams can be saved and reopened as **JSON**, or shared as **SVG and PNG**.

The application uses **TypeScript, SCSS, and Webpack**, with vanilla DOM manipulation and no runtime dependencies. It runs as a static page without a backend or login, and is deployed through GitHub Pages.

## Research, reading, and collaboration

### Timelino

**Investigation software connected to a personal ambition.**

I want to become a private investigator so I can help people. Timelino comes from that goal and the need for a safe, flexible way to collect information, keep it organised, and find it again.

Investigation work can involve a growing amount of material. My aim is to build a workspace where information can be stored dynamically and retrieved when it matters, rather than becoming scattered across separate files and notes.

The repository is currently at an early stage, with a **Laravel scaffold and a Docker-based development environment**. Safe information handling and useful retrieval are design goals for the project, rather than a claim that a finished investigation platform is already available.

### Schrift / BibleApp

**A Bible reader built for personal study and reading together.**

BibleApp, named **Schrift** in the application, goes beyond displaying chapters. It combines reading with tools for comparing translations, keeping notes, and exploring words and references.

The project includes personal notes and marks, translation comparison, word-frequency indexing, and a visual word web. Study boards let passages become cards that can be arranged and connected.

Shared study sessions add a collaborative side: participants can join a session, share reading positions, exchange messages and notes, and receive live updates. Reader settings include different themes and a dyslexia-friendly font option.

The repository also records a move from an earlier Node application to a **Laravel and Livewire** implementation, with Reverb handling real-time updates.

**Technologies:** Laravel, Livewire, MySQL, Redis, Reverb, background jobs, Docker, and browser-side interactions.

## Mobile and real-time applications

### MotoMeeting

**An app for people who want to ride together and stay connected.**

MotoMeeting was built around a social part of riding: seeing where other people are, finding each other, arranging a meeting, and communicating while out on the road.

The project spans an **Android application**, a **Node.js backend**, and a **Flutter version**. Live position updates are exchanged through sockets and shown as rider markers on the map. The app includes location-sharing controls, routes to other riders, friend features, and meeting requests.

Communication was also part of the idea, including calls over WebSockets. Traffic information, traffic jams, and caution reports added context to what was happening around the riders.

That made MotoMeeting a project across several layers at once: the phone's location services, the map interface, the social features, and the server keeping connected users up to date.

**Technologies:** Kotlin/Android, Flutter/Dart, Node.js, Express, Socket.IO, MySQL, Google Maps, and Firebase integrations.

## Development experience

<p>
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel" />
  <img src="https://img.shields.io/badge/Livewire-4E56A6?style=for-the-badge&logo=livewire&logoColor=white" alt="Livewire" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge" alt="Java" />
  <br/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML" />
  <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css&logoColor=white" alt="CSS" />
  <img src="https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="SCSS" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=181825" alt="JavaScript" />
</p>

| Area | Where I use it |
| :--- | :--- |
| **Laravel, PHP & Livewire** | Web applications, Cloud Haven, Schrift, and the foundation of Timelino |
| **HTML, CSS, SCSS & JavaScript** | Website interfaces, application layouts, styling, and browser behaviour |
| **Node.js & sockets** | Real-time backend communication, MotoMeeting, and connected game systems |
| **Java & Minecraft APIs** | Citylife, Enderman, Apocolypse, and plugin development tools |
| **TypeScript** | StructlyDiagrams and its browser-side editing tools |
| **Hosting infrastructure** | SiteNomads and the runtime, routing, and isolation work in Cloud Haven |
| **Ethical hacking** | My interest in investigating systems and understanding their security boundaries |

## Open-source projects I follow

Alongside my own work, I keep forks of projects connected to hosting, PHP development, and remote access.

| Fork | Upstream project |
| :--- | :--- |
| [laravel-exact-online](https://github.com/dfcgaming/laravel-exact-online) | [websmurf/laravel-exact-online](https://github.com/websmurf/laravel-exact-online) |
| [wsl2-php-development](https://github.com/dfcgaming/wsl2-php-development) | [enflow/wsl2-php-development](https://github.com/enflow/wsl2-php-development) |
| [panel](https://github.com/dfcgaming/panel) | [pterodactyl/panel](https://github.com/pterodactyl/panel) |
| [rustdesk-usbip](https://github.com/dfcgaming/rustdesk-usbip) | [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk) |

## Find me

**[SiteNomads.nl](https://sitenomads.nl)** — my business for self-hosting services, website development, and SEO optimisation.  
**[Public repositories](https://github.com/dfcgaming?tab=repositories)** — source code, tools, game assets, and forks available on my GitHub.

<p align="center"><sub>Dylan / dfcgaming · Owner of SiteNomads.nl · Developer & ethical hacker</sub></p>
