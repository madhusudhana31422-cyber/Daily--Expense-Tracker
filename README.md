# Daily--Expense-Tracker

Daily Expense Tracker (Python)

This is a simple Python project that helps users record their daily expenses and analyze spending.
The program accepts multiple expense values, stores them in a list, and calculates the total expense, average expense, highest expense, and lowest expense.

🔹 Features

User input for multiple expenses

Stores data using Python lists

Calculates total, average, maximum, and minimum expenses

Beginner-friendly and easy to understand


🔹 Concepts Used

Lists

Loops

Built-in functions (sum, max, min)

Basic arithmetic operations


This project is ideal for Python beginners to practice real-life problem solving.


---
🔷CODE
Daily_Expense=[]
Num=int(input("Ente the Number of work:"))
for i in range(Num):
    list=int(input(f"Enter Work {i+1} Amount: "))
    Daily_Expense.append(list)
print(f"Daily Expense:{Daily_Expense}")

Total=sum(Daily_Expense)
print("Total Expense=",Total)

print("Average of Expense=",Total//Num)
print("Highest expense=",max(Daily_Expense))
print("lowest expense=",min(Daily_Expense))

🔷 Sample Output
Enter the Number of work:5
Enter Work 1 Amount: 200
Enter Work 2 Amount: 750
Enter Work 3 Amount: 999
Enter Work 4 Amount: 125
Enter Work 5 Amount: 180
Daily Expense:[200, 750, 999, 125, 180]
Total Expense= 2254
Average of Expense= 450
Highest expense= 999
lowest expense= 125

🔷 Author 
Madhusudhana 
