<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1E1E2E,100:CBA6F7&height=220&section=header&text=Rafi&fontSize=70&fontColor=CDD6F4&fontAlignY=38&desc=Full-Stack%20Developer%20%7C%20Kolkata%2C%20India&descAlignY=58&descSize=18&animation=fadeIn" />

<a href="https://rafiera.com"><img src="https://img.shields.io/badge/🌐_rafiera.com-1E1E2E?style=for-the-badge&logoColor=89B4FA" /></a>
<a href="https://linkedin.com/in/therafiniac"><img src="https://img.shields.io/badge/in_LinkedIn-1E1E2E?style=for-the-badge&logoColor=89B4FA" /></a>
<a href="https://instagram.com/therafiniac"><img src="https://img.shields.io/badge/Instagram-1E1E2E?style=for-the-badge&logo=instagram&logoColor=F5C2E7" /></a>
<a href="https://facebook.com/therafiniac"><img src="https://img.shields.io/badge/Facebook-1E1E2E?style=for-the-badge&logo=facebook&logoColor=89B4FA" /></a>
<a href="https://x.com/therafiniac"><img src="https://img.shields.io/badge/X-1E1E2E?style=for-the-badge&logo=x&logoColor=CDD6F4" /></a>
<a href="mailto:therafiniac@gmail.com"><img src="https://img.shields.io/badge/Email-1E1E2E?style=for-the-badge&logo=gmail&logoColor=FAB387" /></a>

<br><br>

<a href="https://github.com/therafiniac">
<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=26&duration=3000&pause=800&color=CBA6F7&center=true&vCenter=true&width=650&lines=Building+full-stack+products+end-to-end;React+%2B+Next.js+%2B+Node.js+%2B+MongoDB;Shipped+150%2B+client+sites+solo;Currently%3A+building+a+SaaS+platform+from+scratch" />
</a>

</div>

<br>

<div align="center">

<a href="#-about">About</a> &nbsp;·&nbsp;
<a href="#-proof-of-work">Proof of Work</a> &nbsp;·&nbsp;
<a href="#-stack">Stack</a> &nbsp;·&nbsp;
<a href="#-currently-exploring">Currently Exploring</a> &nbsp;·&nbsp;
<a href="#-activity">Activity</a> &nbsp;·&nbsp;
<a href="#lets-build-something-worth-shipping">Connect</a>

</div>

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1E2E,100:CBA6F7&height=3" />

<a name="-about"></a>

### 👤 About

Full-stack developer based in Kolkata, four years deep into shipping things that go live, not just demos that run locally.

I started as the sole developer on 150+ client websites — every requirement, deadline, and design call was mine to own. That solo-ownership habit carried forward: today I architect full products end-to-end, from database schema to deployment pipeline, while managing client relationships across three countries without a project manager in between.

Currently building a SaaS platform from scratch and an AI-driven automation layer that's already cutting manual work down. Alongside that, I mentor a junior developer through the exact debugging sessions I used to have to figure out alone.

<br>

<img src="https://img.shields.io/badge/📍_Kolkata%2C_India-1E1E2E?style=flat-square&logoColor=CDD6F4" /> <img src="https://img.shields.io/badge/🧭_4%2B_years_experience-1E1E2E?style=flat-square&logoColor=CDD6F4" /> <img src="https://img.shields.io/badge/🚀_150%2B_sites_shipped-1E1E2E?style=flat-square&logoColor=CDD6F4" /> <img src="https://img.shields.io/badge/🤝_India_·_US_·_UK-1E1E2E?style=flat-square&logoColor=CDD6F4" /> <img src="https://img.shields.io/badge/🎯_Product--first_companies-1E1E2E?style=flat-square&logoColor=CDD6F4" />

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1E2E,100:89B4FA&height=3" />

<a name="-proof-of-work"></a>

### 🧩 Proof of work

#### Reddit Clone — full-stack forum app

Not a tutorial clone. I built a **linear-to-tree algorithm in TypeScript** that resolves infinite-depth threaded comments in O(N) time via hash map lookup — eliminating the N+1 query problem most clone projects ignore. Real-time voting runs on Next.js Server Actions, so there's no extra API layer and cache revalidation is instant.

**Live:** [reddit-clone-fivechi.vercel.app](https://reddit-clone-fivechi.vercel.app) &nbsp;·&nbsp; **Code:** [github.com/therafiniac/reddit-clone](https://github.com/therafiniac/reddit-clone)

`Next.js` `TypeScript` `Prisma` `PostgreSQL` `Neon Auth` `Tailwind` `Shadcn UI`

```mermaid
flowchart LR
    A[Client vote click] --> B[Next.js Server Action]
    B --> C{Cache revalidation}
    C --> D[(PostgreSQL via Prisma)]
    D --> E[Threaded comment tree]
    E --> F["Hash map lookup - O(N)"]
    F --> G[Rendered instantly, no API round-trip]

    style A fill:#1E1E2E,stroke:#CBA6F7,color:#CDD6F4
    style B fill:#1E1E2E,stroke:#89B4FA,color:#CDD6F4
    style C fill:#1E1E2E,stroke:#F9E2AF,color:#CDD6F4
    style D fill:#1E1E2E,stroke:#A6E3A1,color:#CDD6F4
    style E fill:#1E1E2E,stroke:#F5C2E7,color:#CDD6F4
    style F fill:#1E1E2E,stroke:#FAB387,color:#CDD6F4
    style G fill:#1E1E2E,stroke:#94E2D5,color:#CDD6F4
```

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1E2E,100:F9E2AF&height=3" />

<a name="-stack"></a>

### 🛠️ Stack

#### Frontend
<img src="https://cdn.simpleicons.org/react/89DCEB" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/nextdotjs/CDD6F4" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/typescript/89B4FA" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/javascript/F9E2AF" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/tailwindcss/74C7EC" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/sass/F5C2E7" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/bootstrap/CBA6F7" height="36" width="36" />

#### Backend
<img src="https://cdn.simpleicons.org/nodedotjs/A6E3A1" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/express/CDD6F4" height="36" width="36" />

#### Data
<img src="https://cdn.simpleicons.org/mongodb/A6E3A1" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/postgresql/89B4FA" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/prisma/CDD6F4" height="36" width="36" />

#### Auth
<img src="https://cdn.simpleicons.org/jsonwebtokens/CBA6F7" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/firebase/FAB387" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/neon/94E2D5" height="36" width="36" />

#### Cloud
<img src="https://cdn.simpleicons.org/googlecloud/89B4FA" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/firebase/FAB387" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/vercel/CDD6F4" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/netlify/94E2D5" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/microsoftazure/89B4FA" height="36" width="36" />

#### Workflow
<img src="https://cdn.simpleicons.org/git/FAB387" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/figma/F5C2E7" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/n8n/F5C2E7" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/githubcopilot/CDD6F4" height="36" width="36" /> &nbsp; <img src="https://cdn.simpleicons.org/claude/FAB387" height="36" width="36" />

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1E2E,100:A6E3A1&height=3" />

<a name="-currently-exploring"></a>

### 🔭 Currently exploring

<div align="center">

Working toward the **AZ-204 Azure Developer Associate** certification, building on the AZ-900 foundation.
Alongside that, researching architecture for a regional OTT platform — React Native on the client, PostgreSQL + Prisma + Redis on the backend.

<img src="https://img.shields.io/badge/AZ--204_in_progress-1E1E2E?style=flat-square&logo=microsoftazure&logoColor=89B4FA" /> <img src="https://img.shields.io/badge/OTT_platform_architecture-1E1E2E?style=flat-square&logoColor=94E2D5" />

</div>

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1E2E,100:F5C2E7&height=3" />

<a name="-activity"></a>

### 📊 Activity

<div align="center">

<img src="https://github-stats-extended.vercel.app/api?username=therafiniac&show_icons=true&theme=catppuccin_mocha&hide_border=true" height="150" />
<img src="https://streak-stats.demolab.com/?user=therafiniac&theme=catppuccin-mocha&hide_border=true" height="150" />
<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=therafiniac&layout=compact&theme=catppuccin_mocha&hide_border=true&langs_count=6" height="150" />

<br>

<img src="https://github-profile-trophy.vercel.app/?username=therafiniac&theme=onedark&no-frame=true&no-bg=true&margin-w=8&margin-h=8&column=7" />

</div>

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1E2E,100:94E2D5&height=3" />

### 🐍 Snake

<div align="center">

<img src="https://raw.githubusercontent.com/therafiniac/therafiniac/output/github-contribution-grid-snake-dark.svg" width="100%" />

</div>

<br>

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:CBA6F7,100:1E1E2E&height=120&section=footer" />

<a name="lets-build-something-worth-shipping"></a>

**Let's build something worth shipping.** &nbsp;·&nbsp; [rafiera.com](https://rafiera.com)

<sub>Bengali · English · Hindi</sub>

</div>
