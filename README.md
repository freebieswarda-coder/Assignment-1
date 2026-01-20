# Assignment-1
Ai Advanced Course Warda Adan
# 1. Create a list named "fruits" and display its items
fruits = ["Apple", "Banana", "Mango"]
print("Fruits:")
for fruit in fruits:
    print(fruit)

print("\n----------------------")

# 2. Create a tuple named "numbers" with five random numbers and display them
numbers = (5, 12, 7, 3, 9)
print("Numbers:")
for num in numbers:
    print(num)

print("\n----------------------")

# 3. Create a set named "colors" with three different colors and display them
colors = {"Red", "Green", "Blue"}
print("Colors:")
for color in colors:
    print(color)

print("\n----------------------")

# 4. Create a dictionary named "student" and display its keys and values
student = {
    "name": "Ali",
    "age": 20,
    "grade": "A"
}

print("Student Dictionary Keys:")
for key in student:
    print(key)

print("Student Dictionary Values:")
for value in student.values():
    print(value)

print("\n----------------------")

# 5. Create a multi-line string named "poem"
poem = """Twinkle, twinkle, little star,
How I wonder what you are!
Up above the world so high,
Like a diamond in the sky."""
print("Poem:")
print(poem)

print("\n----------------------")

# 6. Check if the length of the "fruits" list is greater than 3
if len(fruits) > 3:
    print("You have many fruits!")
else:
    print("You do not have many fruits.")

print("\n----------------------")

# 7. Program to convert numerical grade into letter grade
grade = int(input("Enter your numerical grade: "))

if grade >= 90:
    print("Letter Grade: A")
elif grade >= 80:
    print("Letter Grade: B")
elif grade >= 70:
    print("Letter Grade: C")
elif grade >= 60:
    print("Letter Grade: D")
else:
    print("Letter Grade: F")

print("\n----------------------")

# 8. Program to classify temperature in Celsius
temp = float(input("Enter temperature in Celsius: "))

if temp < -10:
    print("Freezing")
elif -10 < temp < 0:
    print("Cold")
elif 0 < temp < 20:
    print("Moderate")
elif 20 < temp < 30:
    print("Warm")
else:
    print("Hot")
