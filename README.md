
# 🚀 Application-1-Rule-Engine-with-AST

### 📜 Objective
This application is a simple **3-tier rule engine** using **Node.js**. It determines user eligibility based on attributes like age, department, income, spend, etc., with an **Abstract Syntax Tree (AST)** representing conditional rules.

---

## 🏗️ Features
- Dynamic creation of conditional rules.
- Combines multiple rules into a single AST.
- Evaluates the rules based on user data.

---

## ⚙️ Setup & Installation

### 1. **Clone the repository**  
\`\`\`bash
git clone [https://github.com/ashirbadpanda/Application-1-Rule-Engine-with-AST]
\`\`\`

### 2. **Navigate to the project directory**  
\`\`\`bash
cd Application-1-Rule-Engine-with-AST
\`\`\`

### 3. **Install the required dependencies**  
\`\`\`bash
npm install
\`\`\`

*Note: The \`node_modules\` folder is intentionally excluded to keep the repository light. Make sure to run the above command to install all necessary dependencies.*

### 4. **Run the application**  
\`\`\`bash
node app.js
\`\`\`

---

## 🧩 Usage

### Define and Modify Rules:
The system allows for creating rules, combining them, and evaluating them based on the user’s data.

- **Sample Rule:**  
  \`(age > 30 AND department = 'Sales') OR (salary > 50000)\`
- **Combine Rules:**  
  Rules can be combined into a larger AST for more complex evaluations.
- **Evaluate Rules:**  
  The system evaluates user data against the defined rules and returns \`true\` or \`false\`.

---

## 🧪 Testing the Application

1. **Create individual rules** using the \`create_rule\` function.
2. **Combine rules** with \`combine_rules\` and check the AST structure.
3. **Test rule evaluation** using sample JSON data:
    \`\`\`json
    { 
      "age": 35, 
      "department": "Sales", 
      "salary": 60000 
    }
    \`\`\`
4. **Extend functionality** with custom rules or user-defined functions.

---

## 🛠️ Future Enhancements
- Add REST APIs to create, update, and evaluate rules.
- Implement error handling for invalid rule strings and data formats.
- Support for more complex conditional logic.

---

## 📄 License
This project is run and executed without any license...

---
