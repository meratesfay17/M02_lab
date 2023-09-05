# SDEV220_M02_Lab_CaseStudy.py
# Author: Merhawi Gebrehiwot
# Date: 9/4/23
# Collect student's names and GPAs and test if the student qualifies for either the Dean's List or the Honor Roll


# Prompt the user to input their last name or 'ZZZ' to quit
l_name = input("Enter your last name or 'ZZZ' to quit: ")

# Start a while loop that continues until the user enters 'ZZZ'
while l_name != "ZZZ" :

    # Prompt the user to enter their first name
    f_name = input("Enter your first name: ")

    # Prompt the user to enter their GPA as a floating-point number
    student_gpa = float(input("Enter your GPA: "))

    # Start an inner while loop to ensure the GPA entered is within the valid range (0 to 4)
    while (student_gpa < 0) or (student_gpa > 4) :
        # Prompt the user to enter a valid GPA if it's out of range
        student_gpa = float(input("Enter a valid GPA: "))

    # Check the student's GPA and print their qualification status
    if student_gpa >= 3.5:
        print(f_name, l_name, "has made the Dean's List.")
    elif (student_gpa >= 3.25):
        print(f_name, l_name, "has made the Honor Roll.")
    else:
        print(f_name, l_name, "has NOT made the Dean's List or the Honor Roll.")

    # Prompt the user to enter their last name or 'ZZZ' to quit again
    l_name = input("Enter your last name or 'ZZZ' to quit: ")

# This line is executed when the user enters 'ZZZ' to quit the outer while loop
print("Thanks for using this program!")
