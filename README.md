<p><img src="./assets/header.svg" alt="Chahin Boudra — Software Engineer, full-stack web development" width="100%" /></p>

**Chahin Boudra / Tangier, Morocco**  
Full-stack web development across interfaces, services, and persistent data.

<p><a href="https://www.linkedin.com/in/chahin-boudra/"><img src="./assets/linkedin.svg" alt="LinkedIn profile" height="36" /></a>&nbsp; <a href="https://www.upwork.com/freelancers/~01cecbb79b180c1cac"><img src="./assets/upwork.svg" alt="Upwork profile" height="36" /></a></p>

## System in focus: OpsDesk

A multi-tenant support inbox and CRM built with a separate frontend, API, and background worker.

<p><img src="./assets/architecture-flow.gif" alt="Animated illustrative OpsDesk data flow: Next.js connects to the NestJS API; the API connects to PostgreSQL and Redis/BullMQ, with a separate worker" width="100%" /></p>

<sub>Illustrative data flow · <a href="./assets/architecture.svg">View static diagram</a></sub>

| Boundary | Implementation to inspect |
| :--- | :--- |
| **Identity → data** | Auth0 sessions, organization membership, role checks, and tenant-scoped queries. |
| **Request → background job** | BullMQ email processing, retry behavior, and webhook deduplication. |
| **API → browser** | Authorized Socket.IO rooms and reconnect recovery. |
| **Code → verification** | Integration tests, GitHub Actions, Docker builds, and OpenAPI. |

[Case study](https://github.com/It-shahin/opsdesk/blob/master/docs/PORTFOLIO.md) · [Repository](https://github.com/It-shahin/opsdesk)

<sub>OpsDesk is a staging portfolio project. The case study is public; hosted access requires an authorized account.</sub>

## Related systems

**[Project Management](https://github.com/It-shahin/Project-Management-App)** — Next.js client → Express API → PostgreSQL. Board, list, and timeline task planning.

**[Collaborative Docs](https://github.com/It-shahin/GDocs-clone)** — Next.js + Convex + Liveblocks + TipTap. Google Docs-inspired editing and document workspaces.

**[Property Booking](https://github.com/It-shahin/airbnb-clone)** — Next.js + Prisma + MongoDB. Airbnb-inspired listings, reservations, and host workflows.

## Building blocks

<p><img src="./assets/typescript.svg" alt="TypeScript" title="TypeScript" width="30" height="30" />&nbsp;
<img src="./assets/react.svg" alt="React" title="React" width="30" height="30" />&nbsp;
<img src="./assets/nextdotjs.svg" alt="Next.js" title="Next.js" width="30" height="30" />&nbsp;
<img src="./assets/nodedotjs.svg" alt="Node.js" title="Node.js" width="30" height="30" />&nbsp;
<img src="./assets/nestjs.svg" alt="NestJS" title="NestJS" width="30" height="30" />&nbsp;
<img src="./assets/postgresql.svg" alt="PostgreSQL" title="PostgreSQL" width="30" height="30" />&nbsp;
<img src="./assets/docker.svg" alt="Docker" title="Docker" width="30" height="30" />&nbsp;
<img src="./assets/githubactions.svg" alt="GitHub Actions" title="GitHub Actions" width="30" height="30" /></p>

**Interface:** TypeScript, React, Next.js, Tailwind CSS  
**Services & data:** Node.js, NestJS, Express, PostgreSQL, MongoDB, Prisma  
**Async & delivery:** Redis, BullMQ, Socket.IO, Docker, GitHub Actions

---

[Discuss an engineering role on LinkedIn](https://www.linkedin.com/in/chahin-boudra/) · [Find me on Upwork](https://www.upwork.com/freelancers/~01cecbb79b180c1cac)
