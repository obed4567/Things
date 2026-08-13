# Things
Cod

# 1. DECLARE A VARIABLE

name = "Daniel"
age = 20

print(name)
print(age)


# 2. ADD TWO NUMBERS

num1 = 10
num2 = 20

sum = num1 + num2

print(sum)


# 3. USING IF ELSE

age = 20

if age >= 18:
    print("You are an adult")
else:
    print("You are a minor")


# 4. USING ELIF ELSE

score = 75

if score >= 80:
    print("Grade A")
elif score >= 70:
    print("Grade B")
elif score >= 60:
    print("Grade C")
else:
    print("Fail")


# 5. USING A FUNCTION

def greet():
    print("Hello, welcome to Python")

greet()


# FUNCTION WITH PARAMETERS

def add(a, b):
    return a + b

result = add(10, 20)
print(result)


# 6. CREATE A CLASS

class Student:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def display(self):
        print("Name:", self.name)
        print("Age:", self.age)

student1 = Student("Daniel", 20)
student1.display()


# 7. USING WHILE LOOP

count = 1

while count <= 5:
    print(count)
    count = count + 1


# 8. USING RANGE

for number in range(1, 6):
    print(number)


# 9. RANGE TO LIST OF EVEN NUMBERS

even_numbers = list(range(2, 21, 2))

print(even_numbers)


# 10. TUPLE

my_tuple = (10, 20, 30, 40, 50)

print(my_tuple)


# ADD TO A TUPLE

my_tuple = (10, 20, 30)

my_tuple = my_tuple + (40,)

print(my_tuple)


# 11. LIST

my_list = [10, 20, 30, 40, 50]

print(my_list)


# ADD TO A LIST

my_list.append(60)

print(my_list)


# ADD MULTIPLE ITEMS TO A LIST

my_list.extend([70, 80])

print(my_list)


# 12. DICTIONARY

car = {
    "brand": "Toyota",
    "model": "Camry",
    "year": 2020
}

print(car)
print(car["brand"])


# ADD TO A DICTIONARY

car["color"] = "Black"

print(car)
