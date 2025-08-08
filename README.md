# 🔄 Mealy ↔ Moore Machine Converter

> **A colorful C++ program** to seamlessly convert between **Mealy** and **Moore** finite state machines — complete with a beautiful terminal interface.  

---

## ✨ Features
- 🎯 **Two-way conversion**:
  - Mealy ➡ Moore
  - Moore ➡ Mealy
- 🎨 **Color-coded terminal output** for a better experience.
- 📜 Easy-to-follow input prompts.
- 🧮 Handles transition and output tables efficiently.
- 🚀 Runs directly in the terminal with no extra dependencies.

---

## 📂 Project Structure
\`\`\`
MachineConverter/
│
├── machine_converter.cpp   # Main C++ source code
└── README.md               # Project documentation
\`\`\`

---

## 🛠️ How to Run

1. **Clone the repository**  
   \`\`\`bash
   $CLONE_CMD
   \`\`\`

2. **Compile the code**  
   \`\`\`bash
   g++ machine_converter.cpp -o converter
   \`\`\`

3. **Run the program**  
   \`\`\`bash
   ./converter
   \`\`\`

---

## 📸 Demo (Example Run)
```
*************************************************
           WELCOME TO MACHINE CONVERTER
*************************************************

ENTER:
  1: Mealy to Moore
  2: Moore to Mealy
  3: Exit
```

---

## 📚 Understanding Mealy vs Moore

| Feature        | Mealy Machine                        | Moore Machine                         |
|----------------|--------------------------------------|----------------------------------------|
| Output Depends | Current state **+** Input symbol     | Current state only                     |
| States Needed  | Usually fewer                        | Often more                             |
| Output Timing  | Changes immediately with input change| Changes at next state transition       |

---

## 💡 Example

**Mealy Machine Input:**
\`\`\`
From state Q0 --- a/1 --> Q1
From state Q0 --- b/0 --> Q0
...
\`\`\`

**Equivalent Moore Machine Output:**
\`\`\`
From state Q0/1 --a--> Q1/0
From state Q0/1 --b--> Q0/1
...
\`\`\`

---

## 🎯 Why This Project?
This project is designed for **students** and **enthusiasts** learning Automata Theory, helping visualize the relationship between two popular finite state machine models.

---

## 🖋️ Author
**${AUTHOR}**  
💌 Feedback? Reach out via GitHub Issues.

---

## 📜 License
This project is licensed under the **MIT License** — feel free to use and modify it.
EOF
