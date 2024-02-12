# PythonBeginnerCode

#

print("Hello world")

# variables and basic data types

firstName = 'Labid'
lastName = 'Saad'

fullName = firstName + ' ' + lastName

print(fullName)

myName = 'Labid Saad'  # String
age = 17  # Number
job = 'Web developer'  #string
student = True  # boolean

print(student)

# Numerical operations

a = 20
b = 10

sum = a + b
print(sum)

minus = a - b
print(minus)

multiplication = a * b
print(multiplication)

division = a / b
print(division)

mod = a % b
print(mod)

# User input

nameInput =  input("What's is your Name: "  )
print('Welcome back ' + nameInput)

ageInput = int(input("How old are you: "))
print("You are " + str (ageInput) +  "ýears old")

# Type casting

name = 'Labid Saad'
print(type(name))

student = True
print(type(student))

age = 17
print(type(age))

height = 5.8
print(type(height))

# conditionals

age = int(input('How old are you: '))

if age >= 18:
  print('You can vote!!')
else:
  print('Ýou cannot vote..')

student = False

if student == True:
  print('Ýou are welcome')
else:
  print('Keep pace up your skills')

name = input("What is your name: ")

if name == 'Labid':
  print('Welcome Back!!')
else:
  print('You are not allowed to enter.')

  # elif

if age < 18:
  print('You are a kid')
elif age >= 18 and age <= 40:
  print('Young Blood!!')
else:
  print('Always respect..')

  # inner if statement (conditionals-3)

if age >= 18:
  print("Welcome to the young rage.")
elif age >= 26:
  print('Keep up your skills..')


# Ternary Operator

num1 = 20
num2 = 22

if num1 > num2:
  print('num1 is ' , num1)
else:
  print('num2 is ' , num2)

  # Using ternery operator in this program

print(num1 if num1 > num2 else num2)


# Logical operator

age = int(input('How old are you: '))

if age >= 18 and age <= 30:
  print('Young Blood!!')
elif age < 18 and age >= 0:
  print('Kiddo!!')
else:
  print('Newest leader')


student = False
rollNo = 4

if rollNo == 2 or 3 or 5 or 11:
  print('You are granted')
else:
  print('You are in another serial.')

if not student:
  print('Hello')
else:
  print('Byee')


# While loop

name = input('What is your name: ')

while name == False:
  print(name)
  break

# list

x = [1,2,3,4,5]
print(dir(x))

x.pop()
print(x)

x.append(6)
print(x)

# x.clear()
# print(x)

x.reverse()
print(x)

x.remove(2)
print(x)

x.sort()
print(x)

x.insert(0,3)
print(x)

print(list(range(10)))

# For Loop

for i in range(20):
  print('Hello world' + str(i+1))


for i in range(60):
  print('hello world')

name = input('What is your name: ')
age = int(input('How old are you: '))
job = input('What are you doing: ')

if name == 'Labid' and age == 17 and not job == "web developer":
  for i in range(15):
    print('Its good to see you back' + name + str(i+1))
else:
  print('How you doing: ')

# series

n = int(input('Enter the last number: '))
sum = 0

for x in range(2,n+1,2):
  sum = sum + x

print(sum)

# Dictionary


capitals = {
  'USA' : 'Washington D.C.',
  'Russia' : 'Moscow',
  'China' : 'Beijing'
}


print(dir(capitals))
print(capitals.keys())
print(capitals.get('USA'))
print(capitals.items())
# print(capitals.pop('USA'))
# print(capitals)
# print(capitals.popitem())
# print(capitals)
print(capitals.setdefault('USA'))


# Tuples

tuples = (
  ('Steave Rogers',96,'Captain America'),
  ('Robert Downey jr.', 'IronMan'),
  ('Cristian Bale' , 'Batman')
)

print(tuples[0])
print(dir(tuples))
print(tuples.count('Cristian Bale'))



# Set

x = {1,2,3,4,5,6}
y = {1,2,3,4,7,8,9}
name = {'John', 'Ron'}

print(dir(x))
print(x.add(7))
# print(x.clear())
print(x.copy())
print(x.difference(y))
print(x & y)
print(x | y)
print(x.isdisjoint('John'))
print(x.issuperset('John'))
print(x.update(y))
print(x)


# Stack and Queue

books = []
books.append('Html')
books.append('CSS')
books.append('JavaScript')
books.append('Python')

print(books)

books.pop()
print(books)

books.pop()
print(books)

books.pop()
print(books)

books.pop()
if not books:
  print('No books left..')


# Function

def name(name1,name2):
  print(name1,name2)

name('Labid' , 'Saad')

def function(*details):
  return details

print(function('Labid' , 17 , 'Web Developer'))



# Anonymus Function

# print(list(lambda x : x * x )




# Mapping


def function(x):
  return x + x


num = [1, 2, 3, 4]

print(list(map(function, num)))
print('Square number of list', list(map(lambda x: x * x, (num))))
print("çube number of list is", list(map(lambda x: x * x * x, (num))))

# filter


def function2(x):
  return x % 2 == 0


num2 = [5, 6, 7, 8, 9]

print(list(filter(function2, num2)))
print(list(filter(lambda x: x % 2 == 0, num2)))

# List comprehension


num = [2,3,4,5]

filterx = list(x for x in num if x%2 == 0)
mapx = list( x * x for x in num)

print(filterx)
print(mapx)

# Exception


try:
  value1 = int(input('Enter first valid number: '))
  value2 = int(input('Enter a second valid number: '))
  
  result = value1 / value2
  print(int(result))
  
except: ZeroDivisionError
finally:
  if value2 == 0:
    print('You can not divide by zero')
  elif value2 == '':
    print('No value')
  else:
    print('Invalid Number')


# Zipping

num = [1,2,3,4,5,6]
name = ['Steave Rogers' , 'Robert Downey jr.' , 'Cristian Bale' , 'Nick Fury' , 'SuperMan' , 'BatMan']

zipper = list(zip(num,name))
print(zipper)


# swapping

a = 10
b = 6

print(a, b)

a, b = b, a  # after swapping,,,
print('a is ', a)
print("b is ", b)




def function(x):
  return x * x

function(2)

num = [1,2,3,4,5]

result = list(map(function,num))

print(result)



def function1(x):
  return x % 2 == 0

function1(1)

result1 = list(filter(function1,num))

print(result1)

result3 = list(map(lambda x : x * x , num))
print(result3)
