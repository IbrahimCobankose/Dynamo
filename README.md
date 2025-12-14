# 🏋️‍♂️ Sports & Fitness Tracking Automation

A Windows Forms (WinForms) desktop application designed to track physical activities, calculate calorie burn, and monitor personal progress levels across different sports.

> **⚠️ Note / Disclaimer:**
> This project was developed as a **university coursework assignment**. It represents our learning process in C#, ADO.NET, and Database Management at that time. Therefore, the code structure, naming conventions, or security implementations (such as connection strings) might not reflect professional industry standards. It is shared here for educational and portfolio purposes.

## 🚀 Features

The application allows users to track their development in 4 main branches:

* **🔐 User System:** Secure login and registration with SQL Server integration.
* **📊 Health Analysis:** Automatic Body Mass Index (BMI) calculation based on height and weight.
* **🏊‍♂️ Swimming Module:** Track distances for styles like Freestyle, Butterfly, and Backstroke.
* **🏃‍♂️ Running Module:** Monitor walking, jogging, and marathon training sessions.
* **💪 Fitness & Gym:** Track sets/reps for exercises like Bench Press and Squat.
* **🏀 Basketball:** Time-based tracking for shooting and dribbling drills.
* **📈 Gamification:** A "Level System" that increases as you complete workouts, visualized with progress bars.

## 🛠️ Tech Stack

* **Language:** C# (.NET Framework)
* **UI Framework:** Windows Forms (WinForms)
* **Database:** Microsoft SQL Server (MSSQL)
* **Data Access:** ADO.NET

## ⚙️ How to Run

Since this is a database-driven application, you need to configure it on your local machine:

1.  **Clone** this repository.
2.  **Database Setup:** Create a database named `DynamoDataBase` in your local SQL Server and import the necessary schema (or create `Table_1` with columns matching the `.cs` files).
3.  **Connection String:** Open the `App.config` file and update the connection string to match your local SQL Server instance:
    ```xml
    <add name="SporDB" connectionString="Data Source=.;Initial Catalog=DynamoDataBase;Integrated Security=True" ... />
    ```
4.  **Build & Run:** Open the solution in Visual Studio and click Start.

## 👥 Contributors & Team

This project was a collaborative effort developed as a group assignment.

* **[İbrahim Çobanköse](https://github.com/IbrahimCobankose)** 
* **[Emir Karayılan](https://github.com/emirkarayilan)** 
* **[Enes Türkmenoğlu](https://github.com/enestrkmngll)** 

---

*Thank you for visiting our repository!*
