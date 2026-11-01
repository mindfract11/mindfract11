
<svg xmlns="http://www.w3.org/2000/svg" width="960" height="320" viewBox="0 0 960 320">
  <defs>
    <pattern id="grid" width="32" height="32" patternUnits="userSpaceOnUse">
      <path d="M32 0H0V32" fill="none" stroke="#fff" stroke-opacity=".045"/>
    </pattern>
    <radialGradient id="glow">
      <stop offset="0" stop-color="#fff" stop-opacity=".16"/>
      <stop offset="1" stop-color="#fff" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="border" x1="0" y1="0" x2="1" y2="1">
      <stop stop-color="#fff" stop-opacity=".18"/>
      <stop offset="1" stop-color="#10b981" stop-opacity=".4"/>
    </linearGradient>
    <linearGradient id="name">
      <stop stop-color="#fff"/>
      <stop offset="1" stop-color="#a1a1aa"/>
    </linearGradient>
    <clipPath id="card">
      <rect width="960" height="320" rx="20"/>
    </clipPath>
  </defs>

  <style>
    .mono { font-family: ui-monospace, Consolas, monospace; }
    .sans { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Arial, sans-serif; }

    .rise { animation: rise .8s ease-out both; }
    .r2 { animation-delay: .15s; }
    .r3 { animation-delay: .3s; }

    @keyframes rise {
      from { opacity: 0; transform: translateY(12px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .dot { animation: pulse 2s infinite; }
    @keyframes pulse { 50% { opacity: .35; } }

    .line {
      opacity: 0;
      clip-path: inset(0 100% 0 0);
      animation: typing 12s steps(40,end) infinite;
    }

    .l2 { animation-delay: 4s; }
    .l3 { animation-delay: 8s; }

    @keyframes typing {
      0%, 3% { opacity: 0; clip-path: inset(0 100% 0 0); }
      5%, 27% { opacity: 1; clip-path: inset(0 0 0 0); }
      32%, 100% { opacity: 0; clip-path: inset(0 0 0 0); }
    }

    .cursor { animation: blink 1s steps(1) infinite; }
    @keyframes blink { 50% { opacity: 0; } }

    .float { animation: float 5s ease-in-out infinite alternate; }
    @keyframes float { to { transform: translateY(-6px); } }
  </style>

  <g clip-path="url(#card)">
    <rect width="960" height="320" fill="#09090b"/>
    <circle cx="170" cy="80" r="190" fill="url(#glow)"/>
    <circle cx="830" cy="250" r="180" fill="#10b981" opacity=".09"/>
    <rect width="960" height="320" fill="url(#grid)"/>
  </g>

  <rect x=".5" y=".5" width="959" height="319" rx="20"
        fill="none" stroke="url(#border)"/>

  <g class="rise">
    <rect x="48" y="40" width="205" height="32" rx="16"
          fill="#fff" fill-opacity=".055" stroke="#fff" stroke-opacity=".1"/>
    <circle class="dot" cx="66" cy="56" r="4" fill="#10b981"/>
    <text x="80" y="61" class="mono" font-size="13" fill="#d4d4d8">
      learning · building · improving
    </text>
  </g>

  <g class="rise r2">
    <text x="46" y="158" class="sans" font-size="64"
          font-weight="700" letter-spacing="-2" fill="url(#name)">
      Hey, I'm Illia.
    </text>
    <text x="50" y="192" class="sans" font-size="17" fill="#a1a1aa">
      Aspiring Software Developer
    </text>
  </g>

  <g class="rise r3 mono" font-size="19">
    <text x="48" y="252" fill="#71717a">~</text>
    <text x="66" y="252" fill="#34d399">❯</text>
    <g fill="#f4f4f5">
      <text class="line" x="92" y="252">
        building real projects<tspan class="cursor" fill="#34d399"> ▌</tspan>
      </text>
      <text class="line l2" x="92" y="252">
        learning to code independently<tspan class="cursor" fill="#34d399"> ▌</tspan>
      </text>
      <text class="line l3" x="92" y="252">
        Python · JavaScript · SQL<tspan class="cursor" fill="#34d399"> ▌</tspan>
      </text>
    </g>
  </g>

  <g class="rise r3">
    <g class="float">
      <rect x="640" y="56" width="272" height="166" rx="14"
            fill="#18181b" fill-opacity=".85"
            stroke="#fff" stroke-opacity=".1"/>

      <circle cx="662" cy="78" r="5" fill="#ff5f57"/>
      <circle cx="680" cy="78" r="5" fill="#febc2e"/>
      <circle cx="698" cy="78" r="5" fill="#28c840"/>

      <text x="890" y="82" text-anchor="end"
            class="mono" font-size="11" fill="#71717a">
        ~/projects
      </text>

      <line x1="640" y1="96" x2="912" y2="96"
            stroke="#fff" stroke-opacity=".08"/>

      <g class="mono" font-size="14" fill="#d4d4d8">
        <circle cx="664" cy="124" r="4" fill="#34d399"/>
        <text x="680" y="129">price-tracker</text>

        <circle cx="664" cy="159" r="4" fill="#34d399"/>
        <text x="680" y="164">telegram-bots</text>

        <circle cx="664" cy="194" r="4" fill="#34d399"/>
        <text x="680" y="199">learning-by-building</text>
      </g>
    </g>
  </g>

  <text x="912" y="282" text-anchor="end"
        class="mono" font-size="12" fill="#52525b">
    one step at a time.
  </text>
</svg>


# Illia Slovitskyi | Junior Python Backend Developer

I am a motivated Junior/Intern Backend Developer specializing in asynchronous Python. Currently focusing on building clean APIs, Telegram bots, and automation tools. I am deeply passionate about backend engineering, love solving complex problems, and am looking for an opportunity to grow under technical mentorship within a production team.

---

## 📊 GitHub Activity & Progress

📈 **Profile Views:** ![Views](https://komarev.com/ghpvc/?username=mindfract11&color=blue&style=flat-square)  
🌱 **Current Status:** Actively learning, writing code daily, and open to internship opportunities!

---

## 🛠️ Tech Stack & Tools I Use

| Layer | Technologies & Tools |
| :--- | :--- |
| **Backend & Async** | Python 3.11+, Asyncio, FastAPI, Aiogram 3.x, Pydantic, HTTPX |
| **Databases** | PostgreSQL, SQLAlchemy 2.0 (Async Engine) |
| **DevOps & Workflow** | Docker, Docker Compose, Git, GitHub, Linux basics |

---

## 🎯 My Focus

* **Asynchronous Architecture:** Mastering non-blocking code and building efficient event-driven systems.
* **Database Optimization:** Learning how to design scalable database schemas, optimize async queries, and handle migrations properly.
* **Production Best Practices:** Constantly improving code quality by studying OOP, SOLID principles, and Clean Architecture.
* **CI/CD & DevOps:** Deepening my knowledge in Docker and learning how to automate deployments.

---

## 📈 GitHub Analytics

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <img src="https://github-readme-stats-salesp07.vercel.app/api?username=mindfract11&show_icons=true&theme=github_dark&hide_border=true&count_private=true" alt="GitHub Stats" width="100%"/>
    </td>
    <td width="50%" align="center">
      <img src="https://github-readme-stats-salesp07.vercel.app/api/top-langs/?username=mindfract11&layout=compact&theme=github_dark&hide_border=true" alt="Top Langs" width="100%"/>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=mindfract11&theme=github_dark&hide_border=true" alt="GitHub Streak" width="100%"/>
    </td>
  </tr>
</table>

---

## 📬 Contact Me

If your team is looking for a dedicated, fast-learning intern who cares about code quality and is ready to give 100% to real tasks:

* **Telegram:** [@aspiring_developer2](https://t.me/aspiring_developer2)
* **LinkedIn:** [Illia Slovitskyi](https://www.linkedin.com/in/illia-slovitskyi-a692883b6/)
* **Email:** [illia.slov.dev@gmail.com](mailto:illia.slov.dev@gmail.com)
