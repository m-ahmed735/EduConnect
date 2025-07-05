# 🎓 EduConnect – Modern Android University Management System

A **comprehensive Android application** for university management, designed with **Clean Architecture**, **Jetpack Compose**, **Room**, and **Firebase**. It supports multiple user roles like **Admin**, **Student**, **Teacher**, and **Coordinator**, and provides offline + online data access with a responsive modern UI.

> Built with production-level tools and practices to showcase professional mobile app development skills.

---

## 🚀 Features

- 🔐 **Role-based authentication** (Admin, Student, Teacher, Coordinator)
- 📚 **Course & enrollment management**
- 🧑‍🏫 **Teacher dashboard**: Assignments, grading, attendance
- 🧑‍🎓 **Student dashboard**: Course view, timetable, quizzes, submissions
- 🗓️ **Timetable scheduling**: For classes, events, and exams
- 📥 **Offline support**: Fully working without internet (Room)
- ☁️ **Firebase backend**: Auth, Firestore, Storage
- 🧠 **MVVM + Clean Architecture** (UseCases, Repositories)
- ✨ **Jetpack Compose UI** + Material 3 theming
- 🔁 **Room + Firebase Sync** ready

---

## 🧱 Project Architecture

```
📦 universityapp/
 ┣ 📂 app/
 ┃ ┣ 📂 di/                    # Hilt modules (AppModule, DataModule, etc.)
 ┃ ┣ 📂 core/                  # Shared utils, constants, base classes
 ┃ ┣ 📂 data/                  # Room DB, Firebase, API, Repository impls
 ┃ ┣ 📂 domain/                # UseCases, domain models, repo interfaces
 ┃ ┣ 📂 presentation/          # Compose UI + ViewModels (role-based screens)
 ┃ ┣ 📂 navigation/            # NavGraph & route definitions
 ┃ ┣ 📂 ui/theme/              # Material 3 Theme, Typography, Colors
 ┃ ┗ 📜 MainActivity.kt        # NavHost setup
```

✅ **Architecture Pattern**: Clean Architecture + MVVM  
✅ **Offline First**: Room Database  
✅ **Online Backend**: Firebase (Auth + Firestore)  
✅ **Dependency Injection**: Hilt

---

## 🛠️ Tech Stack

| Layer         | Technologies                             |
|---------------|-------------------------------------------|
| UI            | Jetpack Compose, Material 3               |
| State Mgmt    | ViewModel, StateFlow                      |
| Local DB      | Room, DataStore                           |
| Remote DB     | Firebase Auth + Firestore + Storage       |
| DI            | Hilt                                      |
| Architecture  | Clean Architecture + MVVM + Repository    |
| Navigation    | Navigation-Compose                        |

---

## 📲 Screenshots

> Add images in `screenshots/` folder and update paths below.

| Login            | Dashboard        | Timetable        |
|------------------|------------------|------------------|
| ![](screenshots/login.png) | ![](screenshots/dashboard.png) | ![](screenshots/timetable.png) |

---

## 🧪 Module Status

| Module              | Status        |
|---------------------|---------------|
| Authentication      | ✅ Completed  |
| Student Dashboard   | 🛠 In Progress |
| Teacher Dashboard   | 🛠 In Progress |
| Admin Panel         | ⏳ Planned    |
| Coordinator Panel   | ⏳ Planned    |
| Room + Sync         | 🛠 In Progress |
| Notifications       | ⏳ Planned    |

---

## 🧩 Key Functional Requirements

- [x] Login, register, and role assignment (student, teacher, admin, etc.)
- [x] Add/view courses, enrollments, tasks, quizzes
- [x] Role-based dashboards
- [x] Submit and evaluate tasks/assignments
- [x] Attendance tracking
- [x] Exams & marking system
- [x] Firebase integration for cloud data
- [x] Offline access via Room
- [x] Modern navigation system

---

## 🔧 How to Setup Locally

### Prerequisites

- Android Studio (Hedgehog or later)
- Kotlin 1.9+, Compose Compiler 1.5+
- Firebase Project created
- `google-services.json` file from Firebase console

### Clone the Project

```bash
git clone https://github.com/yourusername/universityapp.git
cd universityapp
```

### Setup Firebase

1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a project and register your app (use same package name)
3. Download `google-services.json` and place it in `app/`
4. Enable the following services:
   - Firebase Authentication (Email/Password)
   - Firestore Database
   - Firebase Storage (optional)

---

## 🧰 Tools Used

- Jetpack Compose
- Hilt (Dependency Injection)
- Firebase Auth + Firestore
- Room Database (with Migrations)
- Material 3 Design System
- StateFlow + UiState/Uievent pattern
- GitHub Actions (CI pipeline - planned)

---

## 📍 Future Enhancements

- 🔔 Push notifications (via FCM)
- 🌐 Web dashboard for admin/staff
- 🗓️ Advanced timetable scheduling with drag-drop
- 💬 Real-time chat (Firestore / Socket)
- 🌍 Multi-language support (Urdu / English)

---

## 👨‍💻 Author

**Muhammad Ahmed**  
🎓 BS Software Engineering — PMAS Arid Agriculture University, Rawalpindi  
📍 Wah, Tehsil Taxila, Pakistan  
💼 Android Developer | Open to Work  
🔗 [GitHub](https://github.com/m-ahmed735)  
🔗 [LinkedIn](https://linkedin.com/in/ahmed.dev735)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> Built with 💙 using Jetpack Compose, Firebase, and clean coding principles to demonstrate real-world Android app development.
