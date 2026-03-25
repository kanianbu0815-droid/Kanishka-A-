# Kanishka-A-


name = input("Enter student name: ")

# Get marks
m1 = int(input("Enter marks for subject 1: "))
m2 = int(input("Enter marks for subject 2: "))
m3 = int(input("Enter marks for subject 3: "))

# Calculate total and average
total = m1 + m2 + m3
average = total / 3

# Find grade
if average >= 90:
    grade = "A"
elif average >= 75:
    grade = "B"
elif average >= 50:
    grade = "C"
else:
    grade = "Fail"

# Display result
print("\n--- Result ---")
print("Name:", name)
print("Total:", total)
print("Average:", average)
print("Grade:", grade)
