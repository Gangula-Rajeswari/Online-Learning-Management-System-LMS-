# Online-Learning-Management-System-LMS-

An end-to-end Learning Management System built with ASP.NET Core MVC, Entity Framework Core, and SQL Server, designed to provide an engaging online education experience for students, teachers, and administrators.

🚀 Features

Role-based access: Admin, Teacher, and Student dashboards.

Course Management: Upload and manage courses, documents, and videos.

Assessments & Leaderboards: Create quizzes, evaluate results, and track performance with leaderboards.

Authentication: Secure login via Google & Facebook OAuth integration.

Payments: Stripe integration for course enrollments.

Reports: Auto-generated PDF reports using QuestPDF.

Responsive UI: User-friendly design for desktop and mobile.

🛠️ Tech Stack

Frontend: Razor Pages, HTML, CSS, JavaScript, Bootstrap

Backend: ASP.NET Core MVC, Web API, C#

Database: SQL Server with Entity Framework Core

Authentication: Google & Facebook OAuth, ASP.NET Identity

Payment Gateway: Stripe

Other Tools: PuppeteerSharp, QuestPDF, Git, Azure App Service

📦 Installation

Clone the repository:

git clone https://github.com/your-username/Online-LMS.git
cd Online-LMS


Configure the database in appsettings.json.

Run migrations:

dotnet ef database update


Start the application:

dotnet run
