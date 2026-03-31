# Bank Management System in Python

A simple **Bank Management System** built with **Python** and **Streamlit**.  
This project allows users to create bank accounts, deposit money, withdraw money, view account details, update information, and delete accounts.

It includes:
- A **Streamlit web interface**
- A **Python backend logic class**
- A **JSON file** for local data storage
- A **CLI version** for basic terminal interaction

---

## Features

- Create a new bank account
- Deposit money
- Withdraw money
- Show account details
- Update user information
- Delete an account
- Store data locally using JSON

---

## Tech Stack

- **Language:** Python
- **Frontend:** Streamlit
- **Storage:** JSON file
- **Backend Logic:** Python class-based methods

---

🚀 How to Run the Project

Follow these steps to run the Bank Management System on your system:

1️⃣ Clone the Repository
git clone https://github.com/AnmolBansiwal/BankManagement_python.git
cd BankManagement_python

2️⃣ Create a Virtual Environment (Recommended)

python3 -m venv venv
source venv/bin/activate

3️⃣ Install Required Dependencies
pip install -r requirements.txt

👉 If requirements.txt is not present, run:

pip install streamlit

4️⃣ Run the Application (Streamlit UI)
streamlit run app.py

📌 After running, open your browser and go to:

http://localhost:8501
5️⃣ (Optional) Run CLI Version

If you want to run the terminal version instead:

python main.py
## Project Structure

```bash
BankManagement_python/
│
├── app.py          # Streamlit UI
├── hello.py        # Main Bank class with banking operations
├── main.py         # CLI-based bank management version
├── data.json       # Local database for storing account data
└── __pycache__/    # Python cache files
