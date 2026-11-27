# <p align="center">🎓 Smart Coaching Institute App </p>

<p align="center">
  <strong>A Digital Platform for Coaching Institute Management & Student Learning</strong>
</p>

<p align="center">
  An Android application designed to simplify institute administration, streamline academic operations, and provide students with a centralized digital learning experience.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android"/>
  <img src="https://img.shields.io/badge/Language-Java-orange?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/UI-XML-blue?style=for-the-badge&logo=android" alt="XML"/>
  <img src="https://img.shields.io/badge/Backend-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase"/>
  <img src="https://img.shields.io/badge/Database-Cloud%20Firestore-FF6F00?style=for-the-badge&logo=firebase&logoColor=white" alt="Firestore"/>
</p>

---

## 📌 Table of Contents

- [📖 About the Project](#-about-the-project)
- [🎯 Problem Statement](#-problem-statement)
- [🎯 Project Objectives](#-project-objectives)
- [✨ Key Features](#-key-features)
- [👨‍💼 Admin Panel](#-admin-panel)
- [🎓 Student Panel](#-student-panel)
- [🤖 AI-Assisted Features](#-ai-assisted-academic-features)
- [🔐 Demo Login Credentials](#-demo-login-credentials)
- [🛠️ Technology Stack](#️-technology-stack)
- [🏗️ Application Architecture](#️-application-architecture)
- [🔑 Authentication & Authorization](#-authentication--authorization)
- [🔥 Firebase Integration](#-firebase-integration)
- [⚙️ Installation & Setup](#️-installation--setup)
- [▶️ Build & Run](#️-build--run)
- [📂 Project Structure](#-project-structure)
- [🎨 UI & Design Guidelines](#-ui--design-guidelines)
- [🛡️ Security](#️-security)
- [🧪 Testing](#-testing)
- [🚧 Development Status](#-development-status)
- [🚀 Future Enhancements](#-future-enhancements)
- [👨‍💻 Developer](#-developer)
- [📄 License](#-license)

---

## 📖 About the Project

**Smart Coaching Institute App** is an Android-based application developed to digitize and simplify the daily operations of a coaching institute.

The application provides two dedicated interfaces:

- 👨‍💼 **Admin Panel** – For managing institute operations and academic activities.
- 🎓 **Student Panel** – For accessing academic information and learning resources.

Administrators can manage admissions, student records, batches, digital study materials, attendance, fees, announcements, and assessments.

Students can access their academic information, published notes, institute announcements, attendance details, fee information, practice papers, and online quizzes.

The application uses **Firebase Authentication** and **Cloud Firestore** for authentication and cloud-based data management.

### 🌟 Project Vision

To create a centralized digital ecosystem that connects institute administration and students, reduces manual work, and improves the overall learning experience.

---

## 🎯 Problem Statement

Traditional coaching institutes often depend on manual processes and disconnected systems for managing admissions, student records, batch allocation, attendance, fees, study materials, announcements, and examinations.

These processes can be time-consuming, difficult to maintain, and prone to errors. Students may also face difficulties accessing study materials, tracking academic information, and staying updated with institute announcements.

The Smart Coaching Institute App aims to solve these challenges by providing a centralized Android-based digital platform for coaching institute management and student learning.

---

## 🎯 Project Objectives

- 📌 Digitize traditional coaching institute operations.
- 👨‍🎓 Simplify student admission and batch allocation.
- 📚 Provide centralized digital study materials.
- 📢 Improve communication between administrators and students.
- 📊 Organize attendance and academic information.
- 💰 Simplify student fee tracking.
- 📝 Support online quizzes and academic assessments.
- ⚡ Reduce manual administrative work.
- 🔒 Provide controlled, role-based access to application data.

---

## ✨ Key Features

### 👨‍💼 Admin Panel

The Admin Panel provides administrative tools to manage institute operations from a centralized interface.

#### 📊 Dashboard
- Centralized administrative dashboard.
- Quick access to important modules.
- Overview of relevant academic and administrative information.

#### 👨‍🎓 Student Management
- View and manage student records.
- Maintain student information.
- Activate or deactivate student accounts.
- Manage student-related operations.

#### 📝 Admission Management
- View admission requests.
- Review student admission information.
- Approve or reject admission requests.
- Allocate students to academic batches.
- Maintain enrollment records.

#### 🏫 Batch Management
- Create and manage batches.
- Organize students into academic batches.
- Manage batch allocation and transfers.
- Maintain batch-related information.

#### 📚 Digital Notes Management
- Upload study materials.
- Convert note photographs into PDF documents.
- Organize notes according to batches.
- Publish study materials for students.
- Manage published academic resources.

#### 📢 Announcements & Notices
- Create institute announcements.
- Publish important academic updates.
- Share notices with students.

#### 📅 Attendance Management
- Create attendance sessions.
- Maintain attendance records.
- Manage student attendance information.

#### 💰 Fee Management
- Maintain student fee information.
- Track fee payments.
- Monitor outstanding fee balances.
- Access student fee records.

#### 📝 Practice Papers & Previous Papers
- Create question papers.
- Upload question paper PDFs.
- Organize academic practice materials.
- Publish papers for students.

#### 🧠 Online Quiz Management
- Create online quizzes.
- Generate AI-assisted quiz drafts.
- Review and customize questions.
- Publish quizzes to selected batches.
- Manage student quiz results.

---

### 🎓 Student Panel

The Student Panel provides students with easy access to academic information and learning resources.

#### 🏠 Student Dashboard
- View relevant academic information.
- Access important student features.
- View attendance and fee summaries.
- Navigate to academic resources.

#### 📚 Digital Notes
- Access published study materials.
- View notes assigned to the active batch.
- Open and read PDF documents.

#### 📢 Announcements
- View institute notices.
- Stay updated with academic information.

#### 📅 Attendance
- View personal attendance information.
- Check attendance records.

#### 💰 Fee Information
- View fee-related information.
- Check outstanding fee balances.

#### 📝 Practice Papers
- Access published practice papers.
- View previous question papers.

#### 🧠 Online Quizzes
- View quizzes published for the student's batch.
- Attempt available quizzes.
- View results where enabled.

---

## 🤖 AI-Assisted Academic Features

The application includes separate AI-assisted workflows designed to support teachers.

### 📄 AI Question Paper Generation

- Generate question-paper drafts using AI assistance.
- Review and edit generated content.
- Keep AI-generated question papers as teacher-side drafts.
- No student-facing publishing workflow for AI-generated question-paper drafts.

### 📝 Teacher-Created Practice Papers

- Teachers can independently create or upload question papers.
- Teacher-created papers can be published separately.
- Students can access published papers through Practice Papers / Previous Papers.

### 🧠 AI-Assisted Quizzes

- Generate quiz question drafts using AI assistance.
- Review and customize generated questions.
- Publish reviewed quizzes to selected batches.
- Allow students to attempt published quizzes.
- Manage quiz results.

> **Note:** AI-generated question-paper drafts, teacher-created practice papers, and online quizzes are separate workflows.

---

## 🔐 Demo Login Credentials

The following sample accounts are provided for demonstration and testing.

| 👤 Account Type | 📧 Email Address | 🔑 Password |
|---|---|---|
| 👨‍💼 Admin | `admin.test@gmail.com` | `Admin@123` |
| 🎓 Student | `saurabhgore44@gmail.com` | `123456` |

### 👨‍💼 Admin Account

```text
Email:    admin.test@gmail.com
Password: Admin@123
Panel:    Admin Panel
```

### 🎓 Student Account

```text
Email:    saurabhgore44@gmail.com
Password: 123456
Panel:    Student Panel
```

### ⚠️ Important Notes

- These are sample demonstration credentials.
- Both accounts must exist in Firebase Authentication.
- The Admin account must have the `ADMIN` role in its corresponding Firestore user document.
- The Student account must have a valid student profile and admission/access mapping.
- Public student registration is disabled.
- Student accounts are provisioned and managed by authorized administrators.

**Security Warning:** These credentials are intended only for controlled demonstrations. The student password is weak, so use a disposable test account and change the password before any public release. Never use these credentials for production accounts. If the repository is public, anyone can view them.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| ☕ Java | Android application development |
| 📱 XML | User interface development |
| 🤖 Android Studio | Development environment |
| 🔥 Firebase Authentication | User authentication |
| ☁️ Cloud Firestore | Cloud database |
| ⚙️ Gradle | Build automation |
| 🎨 Material Design | UI components and design |

### 💻 Development Environment

| Configuration | Details |
|---|---|
| Platform | Android |
| Programming Language | Java |
| UI Technology | XML |
| Package Name | `com.saurabh.smartcoaching` |
| IDE | Android Studio |
| JDK | JDK 26 |
| Backend | Firebase |
| Authentication | Firebase Authentication |
| Database | Cloud Firestore |

> **Note:** The installed JDK must be compatible with the Gradle wrapper and Android Gradle Plugin versions used by the project.

---

## 🏗️ Application Architecture

The application follows a modular architecture that separates UI components, data models, and data operations.

### 📦 Main Components

| Component | Responsibility |
|---|---|
| Activities | Screen-level application functionality |
| Fragments | Modular UI sections |
| Adapters | Displaying lists and collections |
| Models | Representing application data |
| Repositories | Managing data operations |
| Firebase Authentication | User identity verification |
| Cloud Firestore | Cloud data storage |

### 🔄 Application Workflow

```text
                 SMART COACHING APP
                         |
                   LOGIN SCREEN
                         |
              FIREBASE AUTHENTICATION
                         |
                  USER VERIFICATION
                         |
                 FIRESTORE USER ROLE
                         |
                ROLE-BASED NAVIGATION
                     /       \
                    /         \
              ADMIN PANEL   STUDENT PANEL
                   |             |
             ADMIN MODULES   STUDENT MODULES
                    \           /
                     \         /
                       FIREBASE
                          |
                    CLOUD FIRESTORE
```

---

## 🔑 Authentication & Authorization

The application uses a shared email and password authentication system.

### 🔄 Login Workflow

1. User enters email and password.
2. Firebase Authentication verifies the credentials.
3. The application retrieves the corresponding user profile from Firestore.
4. The user's role is identified.
5. The application opens the appropriate panel.

### 👥 User Roles

#### ADMIN
- Access to authorized administrative features.
- Student and admission management.
- Batch management.
- Academic content management.
- Attendance and fee operations.

#### STUDENT
- Access to the Student Panel.
- Personal academic information.
- Authorized batch learning materials.
- Published notices and practice papers.
- Available quizzes and results.

### 📝 Student Account Creation Policy

- Public student registration is disabled.
- Student accounts are provisioned by the institute.
- Admission requests are reviewed by administrators.
- Administrators can approve or reject admissions.
- Students can access their accounts from supported devices.
- Access to batch-specific content depends on valid authorization.

---

## 🔥 Firebase Integration

Firebase provides the authentication and cloud database services required by the application.

### 🔐 Firebase Authentication

Used for:
- Email and password login.
- User identity verification.
- Authentication session management.

### ☁️ Cloud Firestore

Used for storing and managing:

- User profiles.
- Student records.
- Admission requests.
- Enrollment records.
- Batch information.
- Student access mappings.
- Digital notes.
- Announcements.
- Attendance records.
- Fee information.
- Practice papers.
- Quiz information and results.

### 🛡️ Firestore Security Rules

Firestore Security Rules enforce access permissions.

Important requirements:

- Administrative operations require administrator authorization.
- Students can only access permitted information.
- Batch-specific resources are restricted to authorized students.
- Students can only access published academic materials.
- Unauthenticated users cannot access protected data.
- Deactivated or unauthorized students must not retain access to restricted resources.

> Security Rules must be tested before deployment. Client-side checks alone are not sufficient to protect Firestore data.

---

## ⚙️ Installation & Setup

Follow these steps to set up the project locally.

### 📋 Prerequisites

Install the following:

- Android Studio.
- JDK 26 or a compatible JDK version.
- Android SDK.
- Git.
- Firebase account.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Smart-Coaching-Institute-App.git
```

### 2️⃣ Open the Project

1. Launch Android Studio.
2. Select **Open**.
3. Choose the cloned project directory.
4. Wait for Gradle synchronization to complete.

### 3️⃣ Configure Firebase

1. Open the Firebase Console.
2. Create a Firebase project.
3. Register an Android application.
4. Use the following package name:

```text
com.saurabh.smartcoaching
```

5. Download `google-services.json`.
6. Place the file inside the Android app module directory.

```text
app/google-services.json
```

7. Enable Email/Password authentication.
8. Configure Cloud Firestore.
9. Set up the required Firestore collections and Security Rules.

### 4️⃣ Configure Demo Accounts

Create the sample accounts in Firebase Authentication:

**Admin:**

```text
Email: admin.test@gmail.com
Password: Admin@123
```

**Student:**

```text
Email: shreyas@gmail.com
Password: 123456
```

Configure the Admin role in the corresponding Firestore `users` document.

Configure the Student profile and valid admission/access records according to the application's data model.

### 5️⃣ Configure Gradle JDK

In Android Studio:

1. Open **File → Settings**.
2. Navigate to **Build, Execution, Deployment → Build Tools → Gradle**.
3. Select the installed and compatible JDK.
4. Synchronize the project.

Example JDK installation path:

```text
C:\Program Files\Java\jdk-26.0.1
```

---

## ▶️ Build & Run

Run the following commands from the project root directory on Windows.

### 🔍 Verify Gradle Environment

```powershell
.\gradlew.bat -version
```

### 🧪 Run Unit Tests

```powershell
.\gradlew.bat testDebugUnitTest --no-configuration-cache
```

### 📦 Build Debug APK

```powershell
.\gradlew.bat assembleDebug --no-configuration-cache
```

### 📱 APK Output Location

```text
app/build/outputs/apk/debug/app-debug.apk
```

---

## 📂 Project Structure

The following represents the conceptual organization of the application. Actual directory names may differ according to the current implementation.

```text
Smart-Coaching-Institute-App/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/
│   │   │   │       └── saurabh/
│   │   │   │           └── smartcoaching/
│   │   │   │               │
│   │   │   │               ├── data/
│   │   │   │               │   ├── model/
│   │   │   │               │   └── repository/
│   │   │   │               │
│   │   │   │               ├── ui/
│   │   │   │               │   ├── admin/
│   │   │   │               │   ├── student/
│   │   │   │               │   └── auth/
│   │   │   │               │
│   │   │   │               └── utils/
│   │   │   │
│   │   │   ├── res/
│   │   │   │   ├── drawable/
│   │   │   │   ├── layout/
│   │   │   │   ├── mipmap/
│   │   │   │   ├── menu/
│   │   │   │   └── values/
│   │   │   │
│   │   │   └── AndroidManifest.xml
│   │   │
│   │   └── test/
│   │
│   └── build.gradle
│
├── gradle/
├── build.gradle
├── gradle.properties
├── settings.gradle
├── firestore.rules
├── README.md
└── .gitignore
```

---

## 🎨 UI & Design Guidelines

The application follows a clean, modern, and consistent design direction.

### 🎨 Color Palette

| Color | Hex Code | Usage |
|---|---|---|
| Warm Off-White | `#F8F7F2` | Main backgrounds |
| Deep Navy | `#2E3B78` | Primary accent and emphasis |

### ✨ Design Principles

- Modern and professional interfaces.
- Consistent typography.
- Clean layouts and spacing.
- Reusable UI components.
- Clear information hierarchy.
- Consistent Admin and Student experiences.
- Responsive layouts for different Android screen sizes.

---

## 🛡️ Security & Data Protection

Security is an important part of the application.

- 🔐 Firebase Authentication is used for identity verification.
- 🛡️ Firestore Security Rules enforce authorization.
- 👨‍💼 Administrative operations require appropriate permissions.
- 🎓 Students are restricted to their own authorized information.
- 🏫 Batch resources are restricted to authorized batch members.
- 📚 Unpublished academic content remains inaccessible to students.
- 🔄 Access must be synchronized after admission, batch transfer, deactivation, or removal.
- 🔑 Service account private keys and passwords must never be committed to GitHub.
- 🧪 Security Rules should be tested using the Firebase Emulator before production deployment.

---

## 🧪 Testing

Testing is necessary to ensure the application works correctly and securely.

### ⚙️ Functional Testing

- Admin and Student login.
- Role-based navigation.
- Admission approval and rejection.
- Student record management.
- Batch allocation and transfers.
- Notes publishing and viewing.
- Announcement management.
- Attendance operations.
- Fee management.
- Practice paper access.
- Online quiz creation and attempts.

### 🔒 Security Testing

- Unauthenticated access restrictions.
- Administrator authorization.
- Student-specific data restrictions.
- Batch-specific content access.
- Published versus unpublished note access.
- Student deactivation.
- Admission and re-enrollment lifecycle.

### 📦 Build Verification

Run unit tests and build the debug APK after significant changes.

---

## 🚧 Development Status

The project is being developed incrementally.

The following table describes the project's development scope and is not a claim that every module is production-ready.

| Module | Development Scope |
|---|---|
| 🔐 Authentication | Email/password login and role-based access |
| 👨‍💼 Admin Panel | Administrative operations |
| 🎓 Student Panel | Student learning interface |
| 📝 Admission Management | Admission lifecycle |
| 🏫 Batch Management | Allocation and transfers |
| 📚 Digital Notes | Uploading and publishing |
| 📢 Announcements | Institute notices |
| 📅 Attendance | Attendance management |
| 💰 Fee Management | Fee tracking |
| 📝 Practice Papers | Teacher-created papers |
| 🧠 Online Quizzes | Teacher-managed assessments |
| 🤖 AI Assistance | Teacher-side academic workflows |
| 🛡️ Security | Firestore authorization and testing |

---

## 🚀 Future Enhancements

Potential improvements include:

- 📊 Enhanced academic analytics.
- 📅 Detailed attendance reports.
- 📈 Improved student performance tracking.
- 📝 Advanced assessment tools.
- 🔔 Better notification management.
- 📑 Administrative reporting.
- 🎨 UI and accessibility improvements.
- 🧪 Expanded automated testing.

---

## 👨‍💻 Developer

<p align="center">
  <strong>Saurabh Gore</strong>
  <br/>
  Android Application Developer
  <br/>
  <br/>
  <strong>Project:</strong> Smart Coaching Institute App
  <br/>
  <strong>Platform:</strong> Android
  <br/>
  <strong>Language:</strong> Java
  <br/>
  <strong>Backend:</strong> Firebase
</p>

---

## 📄 License

No open-source license has been specified for this project.

All rights are reserved by the project owner unless a separate license is added.

---

<p align="center">
  <strong>🎓 Smart Coaching Institute App</strong>
  <br/>
  <em>Simplifying Institute Management. Empowering Student Learning.</em>
</p>
