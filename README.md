# Python Challenge: PyBank & PyPoll

## Background  
Welcome to the **Python Challenge**, where you'll analyze datasets and automate calculations using Python. This project includes two separate tasks, **PyBank** and **PyPoll**, each simulating real-world scenarios where Python scripting can replace manual data processing tools like Excel.

---

## Repository Structure  
The repository is organized as follows:  

```
python-challenge/  
│  
├── PyBank/  
│   ├── main.py            # Python script for financial analysis  
│   ├── Resources/         # Folder containing the input CSV file (budget_data.csv)  
│   └── analysis/          # Folder containing the output text file with results  
│  
├── PyPoll/  
│   ├── main.py            # Python script for election data analysis  
│   ├── Resources/         # Folder containing the input CSV file (election_data.csv)  
│   └── analysis/          # Folder containing the output text file with results  
│  
└── README.md              # This README file  
```

---

## PyBank: Financial Data Analysis  

### Objective:  
Analyze financial records from a CSV file (`budget_data.csv`) to calculate:  
- Total number of months  
- Net total of "Profit/Losses"  
- Average change in "Profit/Losses"  
- Greatest increase in profits (date and amount)  
- Greatest decrease in profits (date and amount)  

### Output:  
The script generates an analysis summary like this:  
```
Financial Analysis  
----------------------------  
Total Months: 86  
Total: $22564198  
Average Change: $-8311.11  
Greatest Increase in Profits: Aug-16 ($1862002)  
Greatest Decrease in Profits: Feb-14 ($-1825558)  
```  

The results are printed to the terminal and saved to a text file in the `analysis/` folder.

---

## PyPoll: Election Data Analysis  

### Objective:  
Analyze election data from a CSV file (`election_data.csv`) to calculate:  
- Total number of votes cast  
- List of candidates who received votes  
- Percentage of votes each candidate won  
- Total votes for each candidate  
- Winner based on popular vote  

### Output:  
The script generates an election results summary like this:  
```
Election Results  
-------------------------  
Total Votes: 369711  
-------------------------  
Charles Casper Stockham: 23.049% (85213)  
Diana DeGette: 73.812% (272892)  
Raymon Anthony Doane: 3.139% (11606)  
-------------------------  
Winner: Diana DeGette  
-------------------------  
```  

The results are printed to the terminal and saved to a text file in the `analysis/` folder.

---

## Prerequisites  

- Python 3.x  
- Required libraries: None (uses built-in libraries like `csv` and `os`)  

---

## Instructions  

1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/your-username/python-challenge.git  
   cd python-challenge  
   ```  

2. **Run PyBank Analysis**:  
   ```bash  
   cd PyBank  
   python main.py  
   ```  

3. **Run PyPoll Analysis**:  
   ```bash  
   cd PyPoll  
   python main.py  
   ```  

4. **Check Results**:  
   - The output will be printed to the terminal.  
   - Results are also saved as text files in the `analysis/` folder.  

---
