# 🏫 SPSU University Web App

A modern ASP.NET Core Razor Pages web application built for SPSU University. This project is adapted from Microsoft's Contoso University sample app and customized to reflect SPSU branding, content, and layout.

---

## 📸 Screenshots

### ✅ Home Page

![Home](screenshort/Screenshot%202025-12-14%20210313.png)

---

## 🚀 Features

* Razor Pages with clean architecture (Application, Core, Infrastructure, Web)
* Entity Framework Core for data access
* Bootstrap-based responsive UI
* Custom SPSU branding and logo
* Full CRUD for Students, Courses, Instructors, and Departments

---

## 🧱 Project Structure

```
src/
├── SPSUUniversity.Application/   # Application layer logic
├── SPSUUniversity.Core/         # Domain entities and interfaces
├── SPSUUniversity.Infrastructure/ # Infrastructure and data access
├── SPSUUniversity.Web/          # Razor Pages and web UI
└── database/                    # SQL scripts and seed data
```

---

## ⚙️ Getting Started

### Prerequisites

* [.NET Core SDK 3.1 or later](https://dotnet.microsoft.com/download)
* Visual Studio 2019/2022 or VS Code

### Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/spsu-university.git
   cd spsu-university
   ```

2. **Restore Packages:**

   ```bash
   dotnet restore
   ```

3. **Build the Solution:**

   ```bash
   dotnet build
   ```

4. **Run the App:**

   ```bash
   cd src/SPSUUniversity.Web
   dotnet run
   ```

5. Open a browser and navigate to `https://localhost:xxxx`

---

## ✍️ Customization

* Change layout and logos in: `Pages/Shared/_Layout.cshtml`
* Static files (CSS, images): `wwwroot`
* Entity logic: `Core` and `Infrastructure` layers

---

## 🛡 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Acknowledgements

* Original Contoso University app by Microsoft
* SPSU Branding provided by JK Cement initiative
