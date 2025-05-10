# LA‑stack‑bootcamp — Micro‑Bootcamp **Laravel + Angular**

Welcome to the *KleinUX* public repository for our micro‑bootcamp.
Here we will build a series of progressive mini‑projects that culminate in the **Media Vault** capstone (a lightweight evidence manager for multimedia MFA flows).

> **Audience** – Designers & devs with basic JS/PHP who want a fast, practice‑first path to a modern SPA + REST stack.
> **Format** – Short sprints, each delivering a working feature. All code is open‑source.

---

## Why are we doing this?

| Goal                            | How we hit it                                                                |
| ------------------------------- | ---------------------------------------------------------------------------- |
| *Understand the full dev cycle* | local → CI → staging → production with GitHub Actions & Docker               |
| *Master core concepts*          | Angular components, RxJS, Laravel Eloquent, Sanctum auth, file storage, i18n |
| *Build portfolio value*         | Each mini‑app stands alone; the capstone is a showcase piece for **KleinUX** |
| *Document & reflect*            | EXECUTE methodology – every sprint ends with a brief retro + README update   |

---

## Prerequisites

* **Node.js 20 LTS** + **npm**
* **PHP 8.3** + **Composer 2**
* **Docker Desktop** (or Podman)
* **Git** & a GitHub account
* Text editor: VS Code + recommended extensions

Setup instructions live here → [https://github.com/klein-ux/la-stack-bootcamp/tree/main/00-setup](https://github.com/klein-ux/la-stack-bootcamp/tree/main/00-setup) *(placeholder)*

---

## Bootcamp Roadmap

| Phase | Days (≈) | Mini‑Project               | Key Topics                           | Milestone URL                                                                                                                                                    |
| ----- | -------- | -------------------------- | ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 0     | 0.5      | Workspace & Git            | Node, PHP, Composer, Docker, Git     | [https://github.com/klein-ux/la-stack-bootcamp/tree/main/00-setup](https://github.com/klein-ux/la-stack-bootcamp/tree/main/00-setup)                             |
| 1     | 3        | **Checklist SPA**          | Angular CLI, routing, reactive forms | [https://github.com/klein-ux/la-stack-bootcamp/tree/main/01-checklist-spa](https://github.com/klein-ux/la-stack-bootcamp/tree/main/01-checklist-spa)             |
| 2     | 3        | **Checklist API**          | Laravel 11, Eloquent, migrations     | [https://github.com/klein-ux/la-stack-bootcamp/tree/main/02-checklist-api](https://github.com/klein-ux/la-stack-bootcamp/tree/main/02-checklist-api)             |
| 3     | 2        | Full‑stack Checklist       | CORS, HttpClient, Observables        | [https://github.com/klein-ux/la-stack-bootcamp/tree/main/03-checklist-fullstack](https://github.com/klein-ux/la-stack-bootcamp/tree/main/03-checklist-fullstack) |
| 4     | 3        | Auth Layer                 | Laravel Sanctum, Angular guards      | [https://github.com/klein-ux/la-stack-bootcamp/tree/main/04-auth](https://github.com/klein-ux/la-stack-bootcamp/tree/main/04-auth)                               |
| 5     | 3        | **Gallery**                | File uploads, storage, hashes        | [https://github.com/klein-ux/la-stack-bootcamp/tree/main/05-gallery](https://github.com/klein-ux/la-stack-bootcamp/tree/main/05-gallery)                         |
| 6     | 4        | State & Tests              | NGXS/Signals, Jasmine, PHPUnit, i18n | [https://github.com/klein-ux/la-stack-bootcamp/tree/main/06-state-tests](https://github.com/klein-ux/la-stack-bootcamp/tree/main/06-state-tests)                 |
| 7     | 2        | CI/CD & Staging            | GitHub Actions, SiteGround deploy    | [https://github.com/klein-ux/la-stack-bootcamp/tree/main/07-cicd](https://github.com/klein-ux/la-stack-bootcamp/tree/main/07-cicd)                               |
| 8     | 6        | **Media Vault** (capstone) | All above + verification flow        | [https://github.com/klein-ux/la-stack-bootcamp/tree/main/08-media-vault](https://github.com/klein-ux/la-stack-bootcamp/tree/main/08-media-vault)                 |
| 9     | 0.5      | Retro & Portfolio          | EXECUTE report, screenshots          | [https://github.com/klein-ux/la-stack-bootcamp/tree/main/09-retro](https://github.com/klein-ux/la-stack-bootcamp/tree/main/09-retro)                             |

Total ≈ **28 working days** (flexible).

---

## Folder structure

```text
la-stack-bootcamp/
├─ 00-setup/
├─ 01-checklist-spa/
├─ 02-checklist-api/
├─ 03-checklist-fullstack/
├─ 04-auth/
├─ 05-gallery/
├─ 06-state-tests/
├─ 07-cicd/
├─ 08-media-vault/
└─ 09-retro/
```

Each directory contains its own README with task lists, commands and checkpoints.

---

## Learning outcomes

* Spin up **Angular 17** projects, generate components and manage state.
* Craft **Laravel 11** REST APIs with Eloquent, migrations, seeders and queues.
* Implement secure **token auth** with Laravel Sanctum + Angular guards.
* Handle **file uploads** safely, generate hashes and serve signed URLs.
* Configure **GitHub Actions** for automated testing, building and deployment.
* Deploy to **SiteGround** (shared hosting) and later to containerised AlmaLinux servers.
* Apply the **EXECUTE** methodology to iteratively design, build, test and document features.

---

## How to participate

1. **Fork** this repo or clone directly if you’re an internal contributor.
2. Follow the phase README in order – *don’t skip the checklists*.
3. Commit with **conventional commits** (`feat:`, `fix:`, `chore:`…).
4. Open a PR for review after each phase – use the PR template provided.
5. Update placeholder links (demos, diagrams, videos) as you progress.

Questions? Open an **Issue** or ping @klein-ux in Discussions.

---

> *Happy coding — see you in Phase 0!*
