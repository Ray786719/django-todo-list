# 📝 Django To-Do List Application  

A full-stack **Django web application** that allows users to create, manage, and track their tasks.  
Built as part of the **Code Institute Full-Stack Software Development Program**.  

![Django](https://img.shields.io/badge/Django-3.2-green?style=flat-square&logo=django)  
![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat-square&logo=python)  
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple?style=flat-square&logo=bootstrap)  
![Status](https://img.shields.io/badge/Status-In%20Development-yellow?style=flat-square)  

---

## 📑 Table of Contents
- [🎯 Project Goals](#-project-goals)  
- [💡 User Experience (UX)](#-user-experience-ux)  
  - [User Stories](#user-stories)  
  - [Wireframes](#wireframes)  
- [🗄️ Database Design](#%EF%B8%8F-database-design)  
- [📌 Agile Methodology](#-agile-methodology)  
- [✨ Features](#-features)  
- [🎨 Front-End Design](#-front-end-design)  
- [🛠️ Technologies Used](#%EF%B8%8F-technologies-used)  
- [🚀 Deployment](#-deployment)  
- [🧪 Testing](#-testing)  
- [🔮 Future Enhancements](#-future-enhancements)  
- [🙏 Credits](#-credits)  

---

## 🎯 Project Goals
- ✅ Provide a **simple, user-friendly platform** to manage personal tasks.  
- ✅ Ensure **accessibility, responsiveness, and good UX**.  
- ✅ Demonstrate **full-stack Django development**.  
- ✅ Apply **Agile methodology** for planning and delivery.  

---

## 💡 User Experience (UX)

### 👤 User Stories
- As a user, I want to **create a task** so I can track my to-dos.  
- As a user, I want to **mark tasks as completed** so I can monitor progress.  
- As a user, I want to **edit or delete tasks** so I can keep my list up to date.  
- As a user, I want to **filter tasks by category or priority** so I can focus on what matters.  
- As a user, I want to **see overdue tasks highlighted** so I don’t miss deadlines.  

## 🖼️ Wireframes
The following wireframes were created using Balsamiq to illustrate the planned design for desktop, tablet, and Android mobile layouts.

All wireframe PNGs are stored in `/docs/wireframes/`.

### Home Page
**Desktop** ![Home Desktop](docs/wireframes/Home%20Page%20Desktop.png) **Tablet** ![Home Tablet](docs/wireframes/Home%20Page%20Tablet.png) **Android** ![Home Android](docs/wireframes/Home%20Page%20Android.png) ### Task List Page **Desktop** ![Task List Desktop](docs/wireframes/Task%20List%20Desktop.png) **Tablet** ![Task List Tablet](docs/wireframes/Task%20List%20Tablet.png) **Android** ![Task List Android](docs/wireframes/Task%20List%20Android.png) ### Edit Task Page **Desktop** ![Edit Task Desktop](docs/wireframes/Edit%20Task%20Desktop.png) **Tablet** ![Edit Task Tablet](docs/wireframes/Edit%20Task%20Tablet.png) **Android** ![Edit Task Android](docs/wireframes/Edit%20Task%20Android.png) ### Login Page **Desktop** ![Login Desktop](docs/wireframes/Login%20Details%20Desktop.png) **Tablet** ![Login Tablet](docs/wireframes/Login%20Details%20Tablet.png) **Android** ![Login Android](docs/wireframes/Login%20Details%20Android.png)


---

## Database Design

The To-Do List application uses a relational database with three main entities:

- **User**: Stores user account details (username, email, password).  
- **Task**: Represents tasks created by a user, including fields for title, description, due date, and completion status.  
- **Category**: Groups tasks into categories for better organization and is linked to a specific user.  

### Entity-Relationship Diagram (ERD)
![ERD Diagram](docs/erd/todo_app_erd.png)


---

🏃 Agile Methodologies

This project was planned and developed using Agile principles, following an iterative and incremental approach. The focus was on delivering small, usable features regularly while allowing for continuous feedback and improvements.

Project Planning

A GitHub Project Board was set up using a Kanban workflow with three columns: To Do, In Progress, and Done.

Each task was created as a GitHub Issue, linked to a User Story.

MoSCoW prioritisation was applied to clearly define what features were:

Must Have – essential for project success.

Should Have – important but not critical.

Could Have – desirable if time permits.

Won’t Have – excluded from this release.

Epics and User Stories
Epic 1: User Management

As a new user, I want to register an account so I can access the app.

As a returning user, I want to log in securely so that I can use my to-do list.

Epic 2: Task Management

As a user, I want to add tasks so I can remember things to do.

As a user, I want to edit or delete tasks so I can keep my list accurate.

As a user, I want to mark tasks as complete so I can track my progress.

Epic 3: UI/UX

As a user, I want the app to be mobile responsive so I can use it on my phone.

As a user, I want clear navigation so I can find features easily.

Evidence of Agile in Action

GitHub Issues were created for each user story and labelled using MoSCoW.

The Kanban board tracked progress and demonstrated how tasks moved from To Do → In Progress → Done.

Screenshots of the board at different stages of development are included below as evidence:

📸 [Placeholder: Insert board screenshots here]

MoSCoW Prioritisation
Priority	Feature
Must Have	User registration and login functionality
	Add new tasks to the to-do list
	Edit and delete existing tasks
	Mark tasks as complete/incomplete
	Responsive design for desktop, tablet, and mobile
Should Have	Categorise tasks (e.g., Work, Personal)
	Display completed tasks separately from pending ones
Could Have	Add due dates and reminders for tasks
	Search or filter tasks
Won’t Have	Sharing tasks with other users (out of current scope)
	Integration with external calendar apps (e.g., Google Calendar, Outlook)

---

## ✨ Features
- 🔐 User authentication (register, login, logout).  
- ➕ Add, ✏️ Edit, ❌ Delete, and ✅ Complete tasks (CRUD).  
- 🔎 Filter and search tasks.  
- 📱 Responsive UI with Bootstrap.  
- ♿ Accessibility checked against **WCAG guidelines**.  

---

## 🎨 Front-End Design
- 🧭 Navigation bar with key links.  
- 📐 Responsive layout using Bootstrap Grid/Flexbox.  
- 🏷️ Semantic HTML (`header`, `main`, `nav`, `footer`).  
- 🎨 Accessible colors and contrast.  

---

## 🛠️ Technologies Used
- [Django](https://www.djangoproject.com/) (Python framework)  
- [SQLite / PostgreSQL](https://www.postgresql.org/) (database)  
- [Bootstrap 5](https://getbootstrap.com/) (CSS framework)  
- HTML5, CSS3, JavaScript  
- Git & GitHub (version control)  
- Heroku / Render (deployment)  

---

## 🚀 Deployment
Deployment instructions will include:  
1. Clone the repository  
2. Create and activate a virtual environment  
3. Install dependencies from `requirements.txt`  
4. Set up environment variables  
5. Run migrations  
6. Start the server  

---

## 🧪 Testing
- ✅ Unit tests for models, views, forms  
- ✅ Manual testing for all user stories  
- ✅ Accessibility testing (Lighthouse, WAVE)  
- ✅ Responsiveness on multiple devices  

---

## 🔮 Future Enhancements
- 📧 Task reminders via email notifications  
- 📂 Categories as a separate model  
- ↔️ Drag-and-drop task ordering  
- ⚡ AJAX for smoother interactions  

---

## 🙏 Credits
- Developed by Rehan Iqbal  
- Part of the **Code Institute Full-Stack Software Development** course.  



