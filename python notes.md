# Python Notes

\n is a new line; \t is a new tab

## Datatypes
- tuple is a Python datatype used for representing fixed width records. they behave like lists but are immutable*

- Python has a ```dictionary``` datatype for representing name-value pairs

- Python has a ```set``` datatype too - unordered collection of elements

Python has a special type called ```None``` to represent nothing

---

## Variables

Important to notice the difference between variables and strings. Spot the error:

```name = “Alice” print(“name”)```

---

## Functions

```print``` : most commonly used, prints to terminal

```len``` : computes length of a string, list or other collections

```int()``` : string into a number
```str()``` : any value into a string

---

## String Formatting

%s - String (or any object with a string representation, like numbers)

%d - Integers

%f - Floating point numbers

%. 'number of digits' f - Floating point numbers with a fixed amount of digits to the right of the dot.

%x/%X - Integers in hex representation (lowercase/uppercase)

--

## Arithmetic

```
a=6
b=2
print('Addition : ', a + b)
print('Subtraction : ', a - b)
print('Multiplication : ', a * b)
print('Division (float) : ', a / b)
print('Division (floor) : ', a // b)
print('Modulus : ', a % b)
```

---

## Slicing 

```
msg='Welcome to Python 101: Strings'
    #012345678 string index starts at 0
print(msg)
#slicing
print(msg[2:3])
print(msg[2:-1]) #-1 will go backwards on the string
```

---

```
msg='Welcome'

print(msg)
print(msg+msg)
print(msg * 2)
print(msg,msg)
print(msg.upper())
print(msg.lower())
print(msg.capitalize())
print(msg.title())

print(len(msg))
print(msg.count('o'))
```

