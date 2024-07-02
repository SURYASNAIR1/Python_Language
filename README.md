# Python_Language.md

- Compiler/Interpreter : Convert the programming code to lanuage which machine(computer) can understand.
  
- Compiler : in single line
  
- Interpreter : as a whole program 

- Python is a high level language
  
- Python is simple and easy
  
- Freen and open source
  
- Develpoed by Guido van Rossum
  
- Portable
  
- Data science , web devlepoment, AI, to develop games

# Our first program
print("Hello World")

- python3 --version : to see python version

# Python character set
- Letters -> A to Z, a to z
- Digits - 0 to 9
- Special symbol - + * / etc
- Whitespaces
- ASCII and unicode characters as part of dara or literals

- print("surya, s nair") output: surya, s nair
- print("surya", "s nair") output: surya s nair
- print (23) output: 23
- print (35+23)  output: 58

# Variables
Is a name given to a memory location in a program

**Syntax:** variable = value

eg: name = "Surya"

    age = 23
    
    price = 25.99

- name = "Surya"
  
  print(name)

  output: Surya

-  name = "Surya"

    age = 23
    
    price = 25.99

    print("name","age","price") ---> output : name age price

- name = "Surya"

    age = 23
    
    price = 25.99

    print(name,age,price) ---> output : surya 23 25.99

- name = "Surya"

    age = 23
    
    price = 25.99

    print("my name is : ", name)
  
    print("my age is : ", age)
  
    print("my price is : ", price)

    output: my name is :  Surya
  
    my age is :  23
  
    my price is :  25.99

-   name = "Surya"

    age = 23
    
    price = 25.99

    age2=age

    print(age)

    output: 23

- name = "Surya"

    age = 23
    
    price = 25.99

    print(type(name))
    
    print(type(age))
    
    print(type(price))

    output: <class 'str'>
  
    <class 'int'>
  
    <class 'float'>

**Note:** we cannot print a function which we defined.

**Data type:** Integer(+ve, -ve and 0), float(3.99), string("surya")('surya')("""surya"""), Boolean: True or False, None : a = None

# Keywords

- and - else - nin - return
- as - except - is - True
- assert - finally - lambda - try
- break -False - nonlocal - with
- class - for -None - while
- continue - from - not - yield
- def - global - or
- del
- elif

- Python is case sensitive

- a = 10
  
  b = 20
  
  sum = a + b
  
  print (sum)

- a = 10

  b = 20
  
  sum = a - b
  
  print (subtraction)


- a = 10

  b = 20
  
  sum = a * b
  
  print (multiplication)

- a = 10

  b = 20
  
  Division = a / b
  
  print (Division)

- To get remainder :
  
  - a = 10

  b = 20
  
  sum = a % b
  
  print (Remainder)


- **+=1** --> for one time increment

- **-=1** --> for one time decrement

- ** a**b ** = a^b (raise to)

** == ** --> equal to

** = ** --> assignment operator (assigning)

**Note**: a%=b   =     a=a%b  


- Logical operators: and, or, not

- print(not False)  output: True

- print(not True)  output: False

- val1 = True
- val2 = True
- print("and operator:", val1 and val2)
  output: True

- val1 = True
- val2 = False
- print("OR operator:", val1 or val2)
  output: True

FALSE FALSE AND: FALSE
FALSE  TRUE AND: FALSE
TRUE TRUE AND: TRUE

FALSE FALSE OR: FALSE

# Type conversion and Type Casting

- Type conversion : done automatically
- Eg: a = 10
- b = 20.5
- sum = a + b
- o/p: 30.5 (it will be float)
  
- Type casting : due manually
- Eg: a = 10
- b = 20.5
- c = 10
- b = int(c)
  
# Concatenation 
- con1="surya"
  
con2=str("3")

print(con1+con2)

**Note:** we can add a float with integer but for all others it should be of same like both should be string like this both values should be same(2 chars)

# input
- input("enter your name: ")

name = input("enter name: ")
age = int(input("enter age: "))
marks = float(input("enter marks: "))
print ("Welcome", name)
print ("age =", age)
print ("marks =", marks)





  
