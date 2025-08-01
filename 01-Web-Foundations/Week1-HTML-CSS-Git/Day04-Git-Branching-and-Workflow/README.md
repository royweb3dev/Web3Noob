# 📚 Day 04 – Git Branching and Workflow

**Skill Development Track:** Frontend Foundations & UX Engineering  
**Phase:** Web Foundations – Week 1  
**Status:** ✅ Completed  
**Project Folder:** `01-Web-Foundations/Week1-HTML-CSS-Git/Day04-Git-Branching-and-Workflow`

---

## 🎯 Objectives

- Learn to use Git branching strategies used by real-world engineering teams.
- Create and work with `feature`, `bugfix`, and `hotfix` branches.
- Simulate collaborative Pull Requests using solo workflows.
- Resolve merge conflicts and rebase safely.
- Establish branch protection rules and contribution standards.

---

## 🧰 Branching Strategy

| Branch Type   | Naming Convention      | Purpose                                 |
|---------------|------------------------|-----------------------------------------|
| `main`        | `main`                 | Always production-ready and deployable  |
| `dev`         | `dev`                  | Integration branch for all features     |
| `feature/*`   | `feature/name`         | Isolated development of new features    |
| `bugfix/*`    | `bugfix/name`          | Minor bug resolutions                   |
| `hotfix/*`    | `hotfix/name`          | Emergency patches for production        |

---

## 🛠 Simulated Git Workflow (Solo Practice)

1. Create a new feature branch:
   ```bash
   git checkout -b feature/day04-branching

