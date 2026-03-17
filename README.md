This is a simple Python program that takes a user's age as input and classifies them into different age groups such as child, teenager, adult, or senior citizen.

🚀 Features

Takes user input for age

Uses conditional statements (if, elif, else)

Categorizes age into meaningful groups

🧠 Age Categories
Age Range	Category
Less than 13	Child
13 to 19	Teenager
20 to 59	Responsible Adult
60 and above	Senior Citizen
🛠️ How It Works

The program asks the user to enter their age.

It checks the age using conditional statements.

It prints the corresponding category.

💻 Code
age = int(input("Enter your age: "))
print("Your age is:", age)

if age < 13:
    print("you are a child")
elif age < 20:
    print("you are Teenager")
elif age < 60:
    print("you are a responsible Adult")
else:
    print("you are a Senior citizen")
▶️ How to Run

Make sure Python is installed on your system.

Save the code in a file, for example: age_classifier.py

Run the program using:

python age_classifier.py

Enter your age when prompted.

📷 Example Output
Enter your age: 25
Your age is: 25
you are a responsible Adult
📌 Notes

Ensure you enter a valid integer value for age.

The program does not handle invalid inputs (like text or negative numbers).
