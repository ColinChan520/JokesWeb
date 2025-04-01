# 😂 JokesWeb

**JokesWeb** is a fun and interactive Q&A-style joke website where users can browse existing jokes and create their own.

---

## 🚀 Features

- 📝 View a list of jokes  
- ➕ Add new jokes  
- ✏️ Edit existing jokes  
- ❌ Delete jokes  
- 🔍 Search jokes by keywords  
- 🔐 User registration / login / logout  

---

## 🛠 Tech Stack

**Frontend**  
- HTML  
- CSS  
- JavaScript  
- Bootstrap  
- jQuery  

**Backend**  
- C#  
- ASP.NET Core MVC  
- Entity Framework Core  

**Database**  
- MySQL  

**Development Environment**  
- Visual Studio 2022  
- IIS Express (for local testing)  

---

## 📁 Project Structure

JokesWeb/
├── Controllers/       # MVC controllers
├── Models/            # EF models and view models
├── Views/             # Razor pages
│   ├── Jokes/         # Joke CRUD pages
│   ├── Home/          # Home and privacy pages
│   └── Shared/        # Layout and partial views
├── Data/              # EF DbContext and migrations
├── wwwroot/           # Static files
├── appsettings.json   # Configuration file
└── Program.cs         # Application entry point

## 🧪 How to Run Locally

1. **Clone the repository**

    ```bash
    git clone https://github.com/ColinChan520/JokesWeb.git
    cd JokesWeb
    ```

2. **Configure the database**

   Update the MySQL connection string in `appsettings.json`.

3. **Apply migrations and initialize the database**

    Open **Package Manager Console** in Visual Studio and run:

    ```powershell
    Update-Database
    ```

4. **Run the project**

    Press `F5` or click the green play button to start the app using **IIS Express**.

5. **Open in your browser**

    Navigate to:  
    `https://localhost:7080`

---

## 🌐 Deployment

- ✅ Local development using Visual Studio & IIS Express  
- 🚀 Planned deployment to **Amazon Web Services (AWS)**

