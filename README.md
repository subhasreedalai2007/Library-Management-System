# Library-Management-System
The project aims to create a library management system that digitizes inventory and member data, allows easy book issue and return, provides real-time availability status and maintains transaction history.
Features
Add, remove, update books
User registration and management
Issue & return books
Search books
Track transactions
Data stored in JSON/DB
Technologies Used
Python
JSON file storage / SQLite
UML diagrams
Git for version control
Folder Structure
src/ → All source code  
docs/ → All diagrams  
data/ → Sample data storage  
tests/ → Test cases  
How to Run
cd library-management-system
python src/main.py
Running Tests
pytest tests/
library-management-system/
│
├── README.md
├── statement.md
├── src/
│   ├── main.py
│   ├── user_module.py
│   ├── book_module.py
│   ├── transaction_module.py
│   ├── database.py
│   ├── utils.py
│
├── docs/
│   ├── architecture.png
│   ├── usecase.png
│   ├── workflow.png
│   ├── sequence.png
│   ├── class_diagram.png
│   ├── er_diagram.png
│
├── data/
│   ├── books.json
│   ├── users.json
│   ├── transactions.json
│
└── tests/
    ├── test_books.py
    ├── test_users.py
    ├── test_transactions.py
