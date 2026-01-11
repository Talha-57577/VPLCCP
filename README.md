# VPLCCP
Student Record Manager

# VPLAssistPlus 🎓💻

**VPLAssistPlus** is a Windows-based desktop application built using **C# and WPF** that assists with managing and handling student-related data in a Virtual Programming Lab (VPL) or academic support environment. The project follows a clean repository-based structure and demonstrates practical use of WPF UI design with backend data handling.

---

## 📌 Project Overview

VPLAssistPlus is designed as a lightweight academic utility tool that manages student records efficiently through a user-friendly graphical interface. It is suitable for university-level projects, software engineering coursework, or as a base system for further LMS/VPL enhancements.

---

## 🛠️ Tech Stack

* **Language:** C#
* **Framework:** .NET (WPF)
* **IDE:** Visual Studio
* **UI Technology:** XAML (WPF)
* **Architecture Pattern:** Repository Pattern
* **External Library:**

  * `Newtonsoft.Json (v13.0.4)` – for JSON handling

---

## 📂 Project Structure

```
VPLAssistPlus/
│
├── VPLAssistPlus.sln           # Visual Studio solution file
├── VPLAssistPlus/
│   ├── App.xaml                # Application-level UI definitions
│   ├── App.xaml.cs             # Application startup logic
│   ├── MainWindow.xaml         # Main UI layout
│   ├── MainWindow.xaml.cs      # UI logic and event handling
│   ├── Student.cs              # Student model
│   ├── StudentRepository.cs    # Data access & management logic
│   ├── App.config              # Application configuration
│   ├── packages.config         # NuGet package references
│   └── VPLAssistPlus.csproj    # Project file
│
├── packages/
│   └── Newtonsoft.Json.13.0.4/
│
└── bin/                         # Compiled binaries
```

---

## ✨ Features

* 📋 Student data modeling using C# classes
* 🗂️ Repository-based data management
* 🖥️ Clean and responsive WPF user interface
* 🔄 JSON support via Newtonsoft.Json
* 🧩 Easy to extend and integrate with other academic systems

---

## 🚀 How to Run the Project

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/VPLAssistPlus.git
   ```

2. **Open the solution**

   * Launch **Visual Studio**
   * Open `VPLAssistPlus.sln`

3. **Restore NuGet packages**

   * Visual Studio will auto-restore packages
   * If not, go to:

     ```
     Tools → NuGet Package Manager → Restore
     ```

4. **Build & Run**

   * Press **Ctrl + F5** or click **Start**

---

## 📈 Future Enhancements

* Database integration (SQL Server / SQLite)
* Authentication & role management
* VPL assignment tracking
* Reporting & analytics dashboard
* Cloud-based student data sync

---

## 🎯 Use Cases

* University VPL systems
* Academic management tools
* Software Engineering / WPF learning project
* LMS feature extension prototype

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repository, create a feature branch, and submit a pull request.

---

## 📄 License

This project is for **educational purposes**.
You are free to modify and extend it as needed.

---

