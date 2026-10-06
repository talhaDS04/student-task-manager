# Student Task Manager

## Project Description
Student Task Manager is a collaborative, web-based task management application designed to help students organize, track, and complete their academic tasks efficiently. Built as a joint project for demonstrating Git and GitHub version control practices, the application features an intuitive interface for adding task titles and descriptions, managing task statuses, and filtering assignments.

---

## Team Members
* **Muhammad Talha** | Roll No: MSDSF26A004 | GitHub: [@talhaDS04](https://github.com/talhaDS04)
* **Zainab Saeed** | Roll No: MSDSF26M010 | GitHub: [@zainabsaeed27](https://github.com/zainabsaeed27)

---

## Features
* **Task Input Form:** Input field for task titles and descriptions.
* **Task List & Display:** Render newly added tasks with dynamic state updates.
* **Status Tracking:** Mark tasks as complete or pending.
* **Task Search & Filtering:** Quick search bar to locate specific tasks by keyword.
* **Responsive Layout:** Optimized UI for desktop and mobile screen viewports.

---

## Technologies
* **HTML5:** Semantic markup structure.
* **CSS3:** Responsive styling, flexbox layouts, and custom theme variables.
* **JavaScript (ES6+):** Dynamic DOM manipulation and local storage event handling.
* **Git & GitHub:** Distributed version control, collaborative PR workflows, and release management.

---

## Git Workflow
The team adopted a **Feature Branch Workflow** combined with **Pull Requests (PRs)** and **Peer Code Reviews**:
1. Main production code resides strictly on the `main` branch.
2. Each developer creates isolated feature branches prefixed with `feature/` for specific tasks or bugs.
3. Once completed locally, feature branches are pushed to GitHub.
4. A Pull Request is opened targeting `main`, requiring review and approval from the peer partner before merging.
5. Merge conflicts are resolved locally by integrating `main` into the feature branch, resolving markers, and committing.

---

## Branches
* `main`: Production-ready code and release tags.
* `feature/task-form`: Form creation and basic task submission handling (Developed by Muhammad Talha).
* `feature/task-style`: UI enhancement, visual layouts, and CSS polish (Developed by Zainab Saeed).
* `feature/readme-application`: Readme updates and documentation maintenance (Conflict testing branch).

---

## Git Commands Demonstrated
* **Repository Setup & Identity:** `git config`, `git init`, `git remote add origin`
* **Staging & Commits:** `git add`, `git commit -m`, `git status`, `git log --oneline --graph`
* **Branching & Merging:** `git branch`, `git switch -c`, `git checkout`, `git merge`
* **Remote Synchronization:** `git push -u origin <branch>`, `git pull origin main`, `git fetch`
* **Advanced & Undo Operations:** `git stash`, `git stash pop`, `git restore`, `git reset --soft`, `git revert`, `git tag`

---

## GitHub Features Demonstrated
* **Remote Hosting & Tracking:** Synchronization with GitHub remote repository (`origin`).
* **GitHub Issues:** Created, assigned, and linked issues (#1, #2, #3) to track features and bugs.
* **Pull Requests & Code Reviews:** Created PRs (#4, #5) with code discussions, inline feedback, and formal peer approvals.
* **Automated Issue Closing:** Linked PRs to issues using resolution keywords like `Closes #1`.
* **Releases & Version Tagging:** Created git release tag `v1.0.0` and published official GitHub release notes.

---

## How to Run
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/talhaDS04/student-task-manager.git](https://github.com/talhaDS04/student-task-manager.git)
