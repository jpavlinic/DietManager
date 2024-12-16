🛠️ DietManager Project

A Java application with a JavaFX user interface, focusing on backend logic and design patterns for managing user diets and food-related calculations.

🔥 About the Project

The DietManager project is a collaborative Java application built as part of a group project, with a strong emphasis on backend development. The user interface is built using JavaFX, while the business logic employs several well-known software design patterns such as MVC, Factory, Composite, and Adapter. The application interacts with CSV files that serve as a simple database for storing and retrieving information on users, foods, and dietary data.
This project allows users to manage their dietary intake, add food items, and track nutritional information. Calculations are performed on user input to help users maintain healthy eating habits.

🎉 Features

📋 Food Database: Interacts with CSV files to store and retrieve food-related data.

🔄 Design Patterns: Implements MVC, Factory, Composite, and Adapter patterns for maintainability, flexibility, and extensibility.

🧮 Nutritional Calculations: Performs real-time calculations based on user input, such as calorie totals, macronutrients, and portion sizes.

🔧 JavaFX User Interface: A graphical user interface (GUI) built using JavaFX for an interactive and user-friendly experience.

🤝 Collaborative Development: Developed as part of a team, leveraging GitLab for version control and collaborative coding.

🛠️ Tech Stack

Languages:

Java

Frameworks & Libraries:

JavaFX (for UI design)

Design Patterns Used:

MVC (Model-View-Controller): For separation of concerns, keeping the logic, UI, and data handling separate.

Factory Pattern: For the creation of different types of food objects, ensuring cleaner and more modular code.

Composite Pattern: To organize and manage hierarchies of food categories and items.

Adapter Pattern: To bridge incompatibilities between components or external libraries.


Other Tools:

GitLab (for collaborative development and version control)

CSV files (used as a lightweight database)

JavaFX Scene Builder (for UI design)


📡 Core Functionalities

1️⃣ CSV Database Integration

The application reads and writes data to CSV files to simulate a basic database.

Food items, user data, and dietary information are stored and managed through CSV files.

2️⃣ Nutritional Calculations

Calculates total calories, macronutrients, and other user-specific nutritional metrics.

Users can input portion sizes or amounts to see how it affects the overall diet plan.

3️⃣ Design Patterns in Use

MVC: Ensures a clear separation between the data (Model), the user interface (View), and the business logic (Controller).

Factory: Dynamically creates new food objects (like vegetables, fruits, or meals) from a single, unified interface.

Composite: Allows groups of food items to be treated the same way as individual items (e.g., a "meal" can be a collection of multiple food items).

Adapter: Bridges the data from the CSV files to be usable within the system's internal logic.
