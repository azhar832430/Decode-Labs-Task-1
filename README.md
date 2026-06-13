Simple Rule-Based Chatbot
Project Goal
The goal of this project is to create a simple rule-based chatbot that responds to predefined user inputs.
This chatbot uses basic Python programming concepts such as:
Control flow
Decision-making logic
If-else statements
Continuous loop
Basic AI concept
Project Description
This is a beginner-level chatbot project. The chatbot does not use advanced Artificial Intelligence or Machine Learning. Instead, it works using predefined rules.
The chatbot checks the user's input and gives a response according to fixed conditions written in the program.
For example:
```text
User: hello
Bot: Hello! How can I help you?
```
Key Requirements
1. Handle Greetings
The chatbot can respond to greetings such as:
hello
hi
hey
assalamualaikum
salam
2. Handle Exit Commands
The chatbot stops when the user types:
bye
exit
quit
goodbye
3. Use If-Else Logic
The chatbot uses `if`, `elif`, and `else` conditions to decide which response to give.
4. Run in a Continuous Loop
The chatbot keeps running until the user enters an exit command.
Files Included
```text
rule_based_chatbot_project/
│
├── chatbot.py
├── README.md
├── sample_output.txt
└── .gitignore
```
How to Run the Project
Step 1: Install Python
Make sure Python is installed on your computer.
Check Python version:
```bash
python --version
```
or
```bash
python3 --version
```
Step 2: Run the Chatbot
Open terminal or command prompt inside the project folder and run:
```bash
python chatbot.py
```
or
```bash
python3 chatbot.py
```
Sample Output
```text
====================================
       Simple Rule-Based Chatbot
====================================
Bot: Hello! I am SimpleBot.
Bot: Type 'help' to see commands or type 'bye' to exit.
You: hi
Bot: Hello! How can I help you?
You: what is your name
Bot: My name is SimpleBot.
You: what can you do
Bot: I can reply to simple predefined questions using rule-based logic.
You: bye
Bot: Goodbye! Have a nice day.
```
Concepts Used
Control Flow
Control flow means controlling the order in which program statements are executed.
Decision-Making Logic
Decision-making logic means the program decides what to do based on conditions.
Basic AI Concept
This chatbot gives the feeling of talking to a bot, but it only follows predefined rules. That is why it is called a rule-based chatbot
