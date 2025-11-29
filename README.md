# 🦁 CodeSavanna: Zoo Management System

A Java-based data analysis & management toolkit for wildlife parks

## 🌍 Overview

CodeSavanna is a command-line Java application designed to manage and analyze data for a simulated zoo or wildlife park.
It processes structured CSV files to generate statistics, rankings, and interactive features, all while using pure Java, manual arrays, and no modern data structures like ArrayLists or Maps.

This project demonstrates proficiency in:

- File I/O & CSV Parsing: Efficiently reading and splitting data from multiple structured CSV files.
- Manual Data Structures: Utilizing primitive Java arrays (String[], int[]) for storage and manipulation in place of dynamic Collections (like ArrayList or HashMap).
- Custom Sorting & Aggregation: Implementing custom logic (e.g., Bubble Sort-style logic) for calculating rankings and generating grouped statistics.

## ✨ Features

🎮 1. Interactive & Gamified Tools

- Adivinha a Espécie (Guess the Species)
Randomly selects an animal and gives clues (habitat, diet, extinction status).

- Simular Apadrinhamento (Sponsorship Simulation)
Captures client data, assigns sponsorship plans (Simples / Gold / Diamond), and logs the transaction.

📊 2. Reporting & Statistics

- Generate Habitat Performance Reports
Counts animals, interactions, and total revenue per habitat type.

- Total Revenue Report
Calculates park-wide revenue broken down by interaction type (Visits, Shows, Feedings, Sponsorships).

🥇 3. Rankings & Analytics

- Prioritize Endangered Species (Ranking)
Lists endangered species sorted by interaction count and revenue.

- Most Profitable Show
Identifies which show generates the most revenue and the featured animal.

- Top 3 Sponsorships
Shows the three most sponsored species and their monthly revenue totals.

- Most Popular Animal
Finds the single animal with the highest total interactions.

🔎 4. Data Lookup Tools

- Animal Catalog
Displays all animals grouped by habitat.

- Animal Activities
For a given Animal ID, lists all associated Shows and Feedings.

- List Sponsors
For a given Animal ID, displays sponsor info, email, and plan.

## 🛠 Tech Stack

| Component       | Technology                                              |
| --------------- | ------------------------------------------------------- |
| Language        | **Java (CLI Application)**                              |
| I/O             | `java.io`, `Scanner` for CSV parsing                    |
| Data Structures | Primitive Java arrays (`String[]`, `int[]`, `double[]`) |
| Paradigm        | Modular functions                                  |

🚀 How to Run the CodeSavanna Application (IntelliJ IDEA)
---------------------------------------------------------

Since this application relies on reading data from specific CSV files (animais.csv, interacoes.csv, etc.), the file path must be correctly configured for the program to execute successfully.

### 1\. 📂 Configure the Project Structure

The code is structured to look for files in a relative path (./files/). To ensure this works in IntelliJ:

1.  **Create the Data Directory:** In the root directory of your project (the same level as your src folder), create a new folder named files.
    
2.  **Add CSV Files:** Place all necessary semicolon-separated data files (e.g., animais.csv, interacoes.csv, clientes.csv) into the newly created files folder.
    

Your project structure should look like this:

```plaintext
CodeSavanna/
├── .idea/
├── src/
│   └── Main.java
└── files/
    ├── animais.csv
    ├── interacoes.csv
    └── clientes.csv
```

### 2\. ⚙️ Configure the Run/Debug Configuration

By default, IntelliJ uses the project root as the "Working Directory," but it's good practice to verify this.

1.  **Open Configurations:** Click on the current run configuration menu (usually labeled **"Main"** or the class name) in the top-right toolbar next to the run button (▶️), and select **"Edit Configurations..."**
    
2.  **Set Main Class:** Ensure the **Main class** field is correctly set to Main (or the fully qualified name if it's within a package, e.g., com.project.Main).
    
3.  **Verify Working Directory:** Confirm that the **Working directory** field is set to the **root directory of your project** (the directory containing the src and files folders). This is usually the default setting, but it is crucial for the relative path ./files/animais.csv to resolve correctly.
    

### 3\. ▶️ Run the Application

1.  Click the **Run** button (▶️) in the top-right toolbar.
    
2.  The application will compile and start in the **Run window** at the bottom of the screen.
    
3.  Follow the command-line prompts to interact with the various features (Guess the Species, Sponsorship Simulation, Reports, etc.).

## 👨‍💻 Author

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/joaodias23)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jo%C3%A3o-dias23/)
