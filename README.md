# Project Charter: SnapFridge

## 1. Project Purpose and Objectives
SnapFridge is a web application where users upload a photo of their fridge or kitchen counter, and artificial intelligence automatically recognizes the ingredients they have and suggests matching recipes. The goal is to reduce food waste and quickly answer the question "what should I cook today?".

## 2. Stakeholders & Roles
* *Product Owner:* Biray Dağlı (daglibiray@gmail.com)
* *Software Engineering Team:*
    * Biray Dağlı : Project Manager + Backend Developer
    * Ahmet İlker Yıldızlı : Configuration Manager + Frontend Developer
    * Umut Uğurlu : Test Manager + Backend Developer
    * Talha Arpacık : Documentation Lead + AI Integration Developer
    * İdil Emiral : Communication Lead + Database Developer
* *GH Repo/Project URL:* <repo link> (user captanc added if the repo is private)

## 3. Project Scope
### Project domain
Food and lifestyle. Possible customers are recipe platforms and companies developing smart kitchen applications. Key users are students, employees, and home users who want to cook practical meals at home.
### In-Scope
* User registration, login, and role-based authorization (User / Admin)
* Photo upload and AI-based ingredient recognition
* Import of a ready-made recipe dataset (TheMealDB / Kaggle) into the database
* Recipe suggestions based on recognized ingredients
* Favorite recipes and analysis history
* Admin panel (recipe and category management)

### Out-of-Scope
* Native mobile application
* Online grocery ordering / payment system
* Social features (follow, comment, share)
* Calorie and diet tracking

## 4. Technology Stack

### Backend Stack
* Python FastAPI (REST API)
* PostgreSQL
* JWT-based authentication and role-based authorization
* Render (cloud hosting)
* GitHub Actions (CI)

### Frontend Stack
* React
* Tailwind CSS

### AI Stack
* Vision-capable LLM API (ingredient recognition and recipe generation)
* In-team AI agent: Claude Code / GitHub Copilot (its work, effort spent, human review effort, and error types it introduced will be reported)

## 5. Project Milestones
| Deliverable                       | Deadline          |
|---                                |---                |
| Project Charter                   | 13.10.2026 23:59  |
| Project Plan                      | 28.10.2026 23:59  |
| Requirement Specification Report  | 10.11.2026 23:59  |
| Requirement Analysis Report       | 24.11.2026 23:59  |
| Software Design Report            | 08.12.2026 23:59  |
| Software Test Report              | 22.12.2026 23:59  |
| Codebase                          | 27.12.2026 23:59  |
| Demo                              | 30.12.2026 12:30  |
| Presentation                      | 30.12.2026 12:30  |
