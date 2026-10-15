<p align="center">
  <img src="https://raw.githubusercontent.com/dfcgaming/dfcgaming/05e7988d7c5165d6e07356790cd87ea2ef66a317/assets/header.svg" alt="Dylan — developer and owner of SiteNomads.nl" width="100%" />
</p>

<p align="center"><b>Owner of SiteNomads.nl · Full stack developer · Ethical hacker</b></p>
<p align="center">
  <a href="https://sitenomads.nl">SiteNomads.nl</a> &nbsp; / &nbsp;
  <a href="#citylife">Citylife</a> &nbsp; / &nbsp;
  <a href="#selected-work">Selected work</a> &nbsp; / &nbsp;
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

## Selected work

<p><b>Minecraft worlds</b> &nbsp; / &nbsp; <b>Hosting &amp; infrastructure</b> &nbsp; / &nbsp; <b>Research &amp; collaboration</b> &nbsp; / &nbsp; <b>Connected applications</b></p>

### Featured project

<table>
<tr>
<td valign="top">
<a id="citylife"></a>
<img src="https://raw.githubusercontent.com/dfcgaming/dfcgaming/main/assets/portfolio/citylife.svg" alt="Citylife — minecraft life simulation" width="100%" />
<h3>Citylife</h3>
<p>A dedicated life simulator with banking, businesses, employment, property, and a connected city.</p>
<table><tr><td width="33%" align="center"><b>Economy &amp; transactions</b></td><td width="33%" align="center"><b>Jobs &amp; businesses</b></td><td width="33%" align="center"><b>Property &amp; access</b></td></tr></table>
<p><sub><a href="https://github.com/dfcgaming/cityliferesourcepack">Resource pack</a></sub></p>

<details>
<summary><b>Read the Citylife story</b></summary>

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

Citylife represents the kind of development I enjoy most: several systems working together over time, with people giving them a purpose. It is a substantial part of my Minecraft development history.

**Technologies:** Java, Spigot/Bukkit APIs, Socket.IO integration, custom inventory interfaces, backend services, and resource-pack assets.

[Public Citylife resource pack](https://github.com/dfcgaming/cityliferesourcepack)

</details>

</td>
</tr>
</table>

### Hosting and infrastructure

<table>
<tr>
<td width="50%" valign="top">
<a id="cloud-haven"></a>
<img src="https://raw.githubusercontent.com/dfcgaming/dfcgaming/main/assets/portfolio/cloud-haven.svg" alt="Cloud Haven — hosting & infrastructure" width="100%" />
<h3>Cloud Haven</h3>
<p>A hosting control panel for isolated applications, customers, resellers, and connected server nodes.</p>
<p><b>Per-site isolation</b><br/><b>Runtime provisioning</b><br/><b>Cross-node routing</b></p>
<p><sub>Private source</sub></p>

<details>
<summary><b>Read the Cloud Haven story</b></summary>

Cloud Haven brings my Laravel development and hosting interests together. It manages sites, customer and reseller accounts, application runtimes, operations, and connected nodes through a Laravel and Filament panel.

The starting point is a standalone host. Connecting nodes adds a shared site directory and routing between servers, so an entry node can direct a request to the server hosting that site.

A major part of the design is **isolation between hosted sites**. Each site gets its own Docker Compose project and data boundary. WordPress and Laravel workloads have their own web runtime, database, and Redis services; static sites avoid those unnecessary services.

The project also covers runtime provisioning, site moves, backup workflows, monitoring, and Git-based deployment features. Some operational and recovery features are still developing. Cluster-aware routing is part of the project; automatic website failover and continuous site-data replication remain future work.

For me, this project is about taking the work around hosting and making it manageable through software.

**Technologies:** Laravel, PHP, Filament, Livewire, Docker Compose, PostgreSQL, Redis, Traefik, Nginx, and PHP-FPM.

</details>

</td>
<td width="50%" valign="top">
<a id="structlydiagrams"></a>
<img src="https://raw.githubusercontent.com/dfcgaming/dfcgaming/main/assets/portfolio/structlydiagrams.svg" alt="StructlyDiagrams — browser tooling" width="100%" />
<h3>StructlyDiagrams</h3>
<p>A browser-based canvas for documenting infrastructure, connecting components, and exporting diagrams.</p>
<p><b>Drag-and-drop editor</b><br/><b>Auto layout</b><br/><b>JSON / SVG / PNG</b></p>
<p><sub><a href="https://dfcgaming.github.io/StructlyDiagrams/">Open application</a> &nbsp; / &nbsp; <a href="https://github.com/dfcgaming/StructlyDiagrams">Source code</a></sub></p>

<details>
<summary><b>Read the StructlyDiagrams story</b></summary>

[View repository](https://github.com/dfcgaming/StructlyDiagrams) · [Open the application](https://dfcgaming.github.io/StructlyDiagrams/)

StructlyDiagrams addresses another infrastructure problem: documenting how everything connects.

You can drag servers, firewalls, switches, VLANs, Active Directory, Microsoft 365, VPNs, and other components onto a canvas. Connections can be labeled, and an inspector holds properties, attached services, and notes.

It includes automatic layout, collapsible branches, label highlighting, and zoom-to-fit. Diagrams can be saved and reopened as **JSON**, or shared as **SVG and PNG**.

The application uses **TypeScript, SCSS, and Webpack**, with vanilla DOM manipulation and no runtime dependencies. It runs as a static page without a backend or login, and is deployed through GitHub Pages.

</details>

</td>
</tr>
</table>

### Research and collaboration

<table>
<tr>
<td width="50%" valign="top">
<a id="timelino"></a>
<img src="https://raw.githubusercontent.com/dfcgaming/dfcgaming/main/assets/portfolio/timelino.svg" alt="Timelino — research & investigation" width="100%" />
<h3>Timelino</h3>
<p>An early investigation workspace, tied to my ambition to become a private investigator and help people.</p>
<p><b>Investigation workspace</b><br/><b>Information retrieval</b><br/><b>Early development</b></p>
<p><sub>Private source</sub></p>

<details>
<summary><b>Read the Timelino story</b></summary>

I want to become a private investigator so I can help people. Timelino comes from that goal and the need for a safe, flexible way to collect information, keep it organised, and find it again.

Investigation work can involve a growing amount of material. My aim is to build a workspace where information can be stored dynamically and retrieved when it matters, rather than becoming scattered across separate files and notes.

The repository is currently at an early stage, with a **Laravel scaffold and a Docker-based development environment**. The focus at this stage is on laying the foundation for safe information handling and useful retrieval.

</details>

</td>
<td width="50%" valign="top">
<a id="schrift--bibleapp"></a>
<img src="https://raw.githubusercontent.com/dfcgaming/dfcgaming/main/assets/portfolio/schrift.svg" alt="Schrift / BibleApp — reading & collaboration" width="100%" />
<h3>Schrift / BibleApp</h3>
<p>A Bible reader that connects translation comparison, personal notes, visual study boards, and shared sessions.</p>
<p><b>Translation comparison</b><br/><b>Linked study boards</b><br/><b>Live shared sessions</b></p>
<p><sub>Private source</sub></p>

<details>
<summary><b>Read the Schrift / BibleApp story</b></summary>

BibleApp, named **Schrift** in the application, goes beyond displaying chapters. It combines reading with tools for comparing translations, keeping notes, and exploring words and references.

The project includes personal notes and marks, translation comparison, word-frequency indexing, and a visual word web. Study boards let passages become cards that can be arranged and connected.

Shared study sessions add a collaborative side: participants can join a session, share reading positions, exchange messages and notes, and receive live updates. Reader settings include different themes and a dyslexia-friendly font option.

The repository also records a move from an earlier Node application to a **Laravel and Livewire** implementation, with Reverb handling real-time updates.

**Technologies:** Laravel, Livewire, MySQL, Redis, Reverb, background jobs, Docker, and browser-side interactions.

</details>

</td>
</tr>
</table>

### Minecraft gamemodes

<table>
<tr>
<td width="50%" valign="top">
<a id="enderman"></a>
<img src="https://raw.githubusercontent.com/dfcgaming/dfcgaming/main/assets/portfolio/enderman.svg" alt="Enderman — multiplayer horror" width="100%" />
<h3>Enderman</h3>
<p>An asymmetric horror gamemode where collecting every page turns the Enderman from hunter into a target.</p>
<p><b>Timed objectives</b><br/><b>Role-based abilities</b><br/><b>Round management</b></p>
<p><sub>Private source</sub></p>

<details>
<summary><b>Read the Enderman story</b></summary>

In Enderman, one player takes the Enderman role while the others become the hunted players. The players have to search the map and collect pages before time runs out. Once all pages have been collected, the Enderman becomes vulnerable and the hunted players can fight back.

That transition is the centre of the gamemode. The first part of a match is about surviving and finding the objectives; finishing them changes what both sides can do.

The project includes round timers, map configuration, player disguises, spectator handling, random power-up spawns, and light effects. The Enderman ability set includes leap, blackout, power-up blocking, and jumpscare mechanics. The opposing players have tools such as invisibility, stun, flashbangs, and slowdown effects.

**Technologies:** Java, Spigot/Bukkit, event-driven game logic, map tools, and player disguises.

</details>

</td>
<td width="50%" valign="top">
<a id="apocolypse"></a>
<img src="https://raw.githubusercontent.com/dfcgaming/dfcgaming/main/assets/portfolio/apocolypse.svg" alt="Apocolypse — zombie survival" width="100%" />
<h3>Apocolypse</h3>
<p>A movie-inspired zombie apocalypse with climbing enemies, firearms, military elements, and survival experiments.</p>
<p><b>Custom enemy behaviour</b><br/><b>Ammunition & reloads</b><br/><b>Cinematic effects</b></p>
<p><sub><a href="https://github.com/dfcgaming/apocolypsetexturepack">Texture pack</a></sub></p>

<details>
<summary><b>Read the Apocolypse story</b></summary>

Apocolypse was a way to bring that kind of survival setting into Minecraft: dangerous infected enemies, firearms, military elements, and moments of panic.

The code explores zombies climbing obstacles, custom weapons with ammunition and reload timings, flashbangs, military NPCs, and an airstrike mechanic. Loot replenishment and airdrops were also part of the direction, with some of those systems still at a prototype stage.

The story behind it is different from Citylife. Citylife is about building ordinary life into a world; Apocolypse is about what happens when that world becomes hostile.

**Technologies:** Java, Paper/Spigot APIs, custom entities, weapons, timed effects, and resource-pack work.

[Public Apocolypse texture pack](https://github.com/dfcgaming/apocolypsetexturepack)

</details>

</td>
</tr>
</table>

### Connected applications and developer tools

<table>
<tr>
<td width="50%" valign="top">
<a id="motomeeting"></a>
<img src="https://raw.githubusercontent.com/dfcgaming/dfcgaming/main/assets/portfolio/motomeeting.svg" alt="MotoMeeting — mobile & real-time systems" width="100%" />
<h3>MotoMeeting</h3>
<p>A social riding app combining live rider positions, routes, meetings, communication, and traffic information.</p>
<p><b>Live rider map</b><br/><b>Socket communication</b><br/><b>Android & Flutter</b></p>
<p><sub>Private source</sub></p>

<details>
<summary><b>Read the MotoMeeting story</b></summary>

MotoMeeting was built around a social part of riding: seeing where other people are, finding each other, arranging a meeting, and communicating while out on the road.

The project spans an **Android application**, a **Node.js backend**, and a **Flutter version**. Live position updates are exchanged through sockets and shown as rider markers on the map. The app includes location-sharing controls, routes to other riders, friend features, and meeting requests.

Communication was also part of the idea, including calls over WebSockets. Traffic information, traffic jams, and caution reports added context to what was happening around the riders.

That made MotoMeeting a project across several layers at once: the phone's location services, the map interface, the social features, and the server keeping connected users up to date.

**Technologies:** Kotlin/Android, Flutter/Dart, Node.js, Express, Socket.IO, MySQL, Google Maps, and Firebase integrations.

</details>

</td>
<td width="50%" valign="top">
<a id="spigot-auto-reloader"></a>
<img src="https://raw.githubusercontent.com/dfcgaming/dfcgaming/main/assets/portfolio/spigot-auto-reloader.svg" alt="Spigot Auto Reloader — developer tooling" width="100%" />
<h3>Spigot Auto Reloader</h3>
<p>A plugin development helper that detects changed JAR files and triggers plugin or server reloads.</p>
<p><b>JAR change detection</b><br/><b>Plugin lifecycle hooks</b><br/><b>Reload configuration</b></p>
<p><sub>Private source</sub></p>

<details>
<summary><b>Read the Spigot Auto Reloader story</b></summary>

Working on plugins involves a repeated cycle: change code, build the plugin, put it on the server, and test again. Spigot Auto Reloader came from that part of the work.

It watches plugin JAR modification times and reacts when a file changes. Its reload path can disable and re-enable the plugin, with an optional full-server reload mode. It uses plugin lifecycle reloads to shorten my development and testing cycle.

It is a smaller project than the gamemodes, but it belongs in the same story: building tools around the work I spend time doing.

**Technologies:** Java, Bukkit plugin lifecycle APIs, scheduling, and file-change detection.

</details>

</td>
</tr>
</table>


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
