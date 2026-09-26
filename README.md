 💳Your Wallet's Year-End Story
> **Spotify Wrapped for your money.**
THis is a Python-based transaction analytics project that analyzes six months of synthetic Indian bank/UPI transactions. It cleans messy financial data, normalizes merchant descriptions, categorizes spending, analyzes monthly and time-of-day patterns, detects unusually large transactions using a manually implemented z-score, and assigns quantitative spending archetypes.
✨ Features
 
1. Transaction Parser
2. Vendor Extractor
3. Category Tagger
4. Spending Overview
5. Monthly Trend Analysis
6. Time-of-Day Patterns
7. Anomaly Detection
8. Spending Archetype Detection

🛠️ Tech Stack
Python
Pandas
NumPy
Jupyter Notebook / Google Colab
📁 Project Structure
```text

├── Minor_Project.ipynb
├── rahul_transactions.csv
├── README.md
```
▶️ Run the Project
Google Colab
Upload 'Minor_Project.ipynb` to Google Colab.
Upload `rahul_transactions.csv` into the same Colab session.
Run all cells from top to bottom.
Local Jupyter
```bash
pip install -r requirements.txt
jupyter notebook
```
Open `Minor_Project.ipynb` and run all cells.
📊 Dataset
The supplied dataset contains 1,328 rows including duplicate records and represents a fictional Bengaluru-based software engineer named Rahul Sharma over January–June 2024.
The data intentionally contains:
Four date formats
Multiple currency formats
`DR` / `CR` and `Debit` / `Credit`
Messy merchant descriptions
P2P transfers
ATM withdrawals
Duplicate rows
Synthetic anomaly transactions
🧠 Archetypes
The notebook evaluates quantitative rules for:
THE FOODIE
THE QUICK COMMERCE JUNKIE
THE SHOPAHOLIC
THE INVESTOR
THE LATE-NIGHT SNACKER
THE CAB COMMUTER
THE SUBSCRIPTION LOVER
THE YOLO SPENDER
THE DISCIPLINED SAVER
THE BENGALURU COFFEE REGULAR (bonus)
🚫 Constraints
The implementation intentionally uses Pandas, NumPy, Python fundamentals, and manual statistical calculations. It does not require scikit-learn, scipy, statsmodels, or automated profiling libraries.
🔐 Privacy
The included dataset is synthetic. Do not upload personal bank statements or UPI exports to a public GitHub repository.
👨‍💻 Author
Mangesh Shankar Hatekar
Minor Project —Your Wallet's Year-End Story

Built with 🐍 Python + 🐼 Pandas + 🔢 NumPy
