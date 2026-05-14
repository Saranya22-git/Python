Hey everybody!!!

**PYTHON**

#### **Table of Contents**
- [**Table of Contents**](#table-of-contents)
- [**Real-Time Applications developed by Python Programming**](#real-time-applications-developed-by-python-programming)
- [**History of Python**](#history-of-python)
- [**Versions of Python**](#versions-of-python)
- [**Features of Python**](#features-of-python)
- [**Importance of Identifiers or Variables:**](#importance-of-identifiers-or-variables)
- [**Rules for Identifiers/Variables in Python Programming:**](#rules-for-identifiersvariables-in-python-programming)
- [**Data Types in Python**](#data-types-in-python)
  - [**Fundamental Category data type**](#fundamental-category-data-type)
    - [**int**](#int)
    - [**float**](#float)
    - [**bool**](#bool)
  - [**Sequence Category data type**](#sequence-category-data-type)
  - [**List Category data type**](#list-category-data-type)
  - [**Set Category data type**](#set-category-data-type)
  - [**Dict Category data type**](#dict-category-data-type)
  - [**None Category data type**](#none-category-data-type)


---

#### **Real-Time Applications developed by Python Programming**

- **Web Applications**
  - Java Language: Servlets, JSP, Spring, Hibernate etc..,(SUN, MS-Oracle).
  - C#.net Language: ASP.NET
  - Python Language: Django, Pyramid etc..,
- **Gaming Applications**
- **Artificial Intelligence Applications(ML, DL)**
- **Desktop Applications(GUI Applications) Look & Feel**
- **Image Processing Applications**
- **Text Processing Applications**
- **Business Applications development(B.Apps)**
- **Audio and Video based Applications**
- **Web Scrapping/Harvesting Applications**
- **Data Visualization and Complex Math Calculations**
- **Scientific Applications(NASA, FB)**
- **Software Development**
- **Operating System Installers**
- **CAD and CAM Based Applications(Computer-Aided Manufacturing & Design)**
- **Embedded Applications**
- **IOT Based Applications**
- **Console Based Applications**
- **Automation of Testing**
- **Animation Based Applications**
- **Data Analysis and Data Analytics Applications**
- **Computer Vision**
- **Education Programmes**
- **etc......,**

---

#### **History of Python**
- Python Programming Language concevied (foundation stone) in the year 1980.
- Python Programming Language implementation was began in the year 1989.
- Python Programming Language officially released in the year 1991 Feb.
- Python Programming Language developed by **Guido van Rossum** (Father of Python).
- Python Programming Language developed at CWI (Centrum Winkunde Informatica) institute in Netherlands.
- Python Programming Language managed and maintained by a Non-Commercial Organization called **Python Software Foundation(PSF).**
- The official website of python software foundation(PSF) is www.python.org

---

#### **Versions of Python**

***Version** is a numerical value(integer values) they are using for identification purpose.*
*Python Programming Language contains **3 types of versions**. They are*
1. **Python 1.x(outdated)** - *Here 1 is called major version. Here x represents 0 1 2 3 4 5 6 7 etc..., called Minor Version.*
2. **Python 2.x(outdated)** - *Python 2.x does not support Backward Compatability.*
   
   ***Backward Compatability** means New Versions of Software can still work with stuff made for older versions.*
3. **Python 3.x** - Here 3 is called Major Version. Here x represents 0 1 2 3 4 5 6 7 8 9 (7, 8, 9 are secured) 10 11(10,11 are bug fix) 12(Future release)

---

#### **Features of Python**
- *Features of a language are nothing but services or facilities provided by Language Developers and they are available in Languages and used by Language Programmers for developing real time applications.*
- *Python Programming Language provides 11 features. They are*

1. **Simple**
   *Python is one of the simple programming language because of 3 important technical factors. They are*

   **Factor-1:** *Python Programming provides "Rich set of modules(libraries)". So that python programmers are Re-using the predefined code without writing our own code.*

   **Definition of Module:** *A module is a collection of functions, attributes and class names. Examples are Calendar, math, random, threading, qrcode etc..,*

   **Factor-2:** *Python Programming provides in-built(already present) garbage collection facility by executing garbage collector program. So that garbage collector collects un-used memory space and improves the performance of python based applications.*

   **Definition of Garbage Collector:** 
   - *Grabage collector is one of the in-built python program in Python software and it is running behind of regular python program and whose role is collects un-used memory space and improves the performance of Python Based Applications.*
   - *Hence Garbage collector takes about Automatic Memory management.*
  
   **Factor-3:** *Python Programming Language provides user-friendly syntaxes and makes the programmer to develop error-free programs within Limited Span of time.*

2. **Freeware and Opensource:**
   
   **Freeware:** *If any software downloaded freely and that software comes under freeware. **Example:** Python, JAVA*

   **Opensource:** 
   - *The Standard name of Python Software is "CPYTHON".*
   - *Many software companies came forward and customized CPYTHON and developed their own in-house tools.*
   - *The customized versions of CPYTHON are called "Python Distributions". Some of the Python Distributions are*
        1. **JPYTHON or JYTHON:** *Used for running java based applications.*
        2. **IRON PYTHON or IYTHON:** *Used to run C#.net applications.*
        3. **RUBY PYTHON:** *Used to run ruby applications.*
        4. **MICRO PYTHON:** *Used to run/develop micro controller applications.*
        5. **ANACONDA PYTHON:** *Used to run big data/Hadoop based applications.*
        6. **STACKLESS PYTHON:** *Used for concurrency applications etc..,*
   
3. **Platform and Independent Language:**
   *All datatypes take same memory space on different OS's*

4. **Dynamically Typed:**
   *In IT we have 2 types of programming languages. They are*
   1. Static Typed Programming Languages
   2. Dynamically Typed Programming Languages
   
   **Static Typed Programming Languages:** *In Static Typed Programming Languages it is mandatory to specify variable declaration for storing inputs in main memory of computer.*

   **Example:** int x,y,z;
                x=10
                y=8
                z=x+y

   **Example Languages:** Java, C, C#.net, etc.,

   **Dynamically Typed Programming Languages:** *In Dynamically Typed Programming Languages depends on type of value we are assigning, whose data type automatically/implicitly assigned by python execution environment. There is no need to write variable declaration in Dynamically Typed Programming Languages*

   **Example:** 
   ```python
   >>>a=10
   >>>print(a,type(a)) 10 <class 'int'>
   ```

   **Example Languages:** Python
   
5. **Interpreted Programming Language**
   
   **Interpretation:** *Line by Line conversion of source into destination is called Interpretation.*

   **Interpreter:** *Program performs interpretation process.*

   **Compilation:** *All lines at once conversion is called Compilation.*

   **Compiler:** *Program performs compilation process.*

   **Python Programming Language Execution Environment**

   **Execution Environment:** *It is the complete setup that runs your python code(including tools, memory, interpreter and system support).*

   **Main Components of Python Execution Environment**

   1. **Python Interpreter:** 
   - *This is the engine of Python.*
   - *It reads your .py file.*
   - *Converts it into something the computer understands.*
   - *Executes it line by line.*
  
  2. **Source code(.py file):**
  ```python
   print("Saranya")
  ```

  3. **Compilation to Bytecode:**
   - *Python does a hidden step: Your code is converted into Bytecode.*
   - *Stores as .pyc files(inside __pycache__)*
   - *Not human readable.*
   - *Platform independent.*
  
  4. **Python Virtual Machine(PVM):**
   - *This is where actual execution happens.*
   - *Takes bytecode.*
   - *Executes instructions.*
   - *Works like a mini CPU for Python.*
   - *Python doesn't directly run your code on OS, it runs inside PVM.*
  
  **Execution Modes in Python:** *Python can run code in 2 main ways.*

  1. **Interactive Mode:** *Python Shell*
      - *You type commands - get output immediately.*
      - *Used for Testing, Learning.*
      - **Example:**
         ```python
         >>> 5+3
         8
         ```

  2. **Script Mode:**
      - *You write code in a file(file.py)*
      - *Run it using: python file.py*
      - *Used for real projects.*
  
  **Runtime Environment:** *The runtime environment includes:*
  - **Memory Management:** *Python automatically allocates & frees memory.*
  - **Garbage Collection:** *Removes unused objects.*
  - **Variables & Objects:** *Everything in Python is an object.*
  
  **Libraries & Modules Environment:** *Python execution also depends on:*
  - *Built-in libraries(math, sys)*
  - *External packages.*
  - **Example:** pip install numpy
      
  **Virtual Environment:** *A virtual environment is like a separate Python workspace.*
  - *Avoid version conflicts.*
  - *Keep projects isolated.*
  - **Example:** python -m venv myenv
  
  **Definition of PVM:** *PVM stands for Python Virtual Machine. PVM reads bytecode line by line and converts it into machine-understandable instructions.*
  
6. **High Level Language**
   *In IT, we have 2 types of languages. They are:*
   - *Low Level Programming Language*
   - *High Level Programming Language*
   **Low Level Programming Language:** *In Low Level Languages, data is always stored in the form of low level values such as Binary data, Octal data, Hexa decimal data. These number systems are not directly understandable by end-users.*

   **High Level Programming Language:** *In these languages, internally even the programmer specifies the data in the form of low level format such binary data, octal data and hexa decimal data, automatically python programming language execution environment converts into high level data which is understandable by end-users. Hence python is one of the **High Level Programming Language.***

7. **Robust** (Strong)
   *Python is one of the Robust Programming Language because it provides "Exception handling" facility. If the python programmer uses exception handling then python based application becomes robust.*

   **Definition of Exception:** 
   - *All runtime errors are called Exception.*
   - *By default, all programming language, when exception occurs then we get Technical Error Messages.*
   - *In industry it is not recommended to generate technical error messages because these messages are not understandable by end-users.*
   - *Industry is recommended to generate user-friendly error messages by using "Exception Handling".*
  
   **Definition of Exception Handling:**
   - *The process of converting Technical error messages into user-friendly error messages is called Exception Handling.*

8. **Both functional(Procedure) and Object Oriented Programming Language(OOPs)**
   
9.  **Extensible**
    
    - *A programming language is said to be "Extensible" if it is provides programming facilities to other languages.*
    - **Example:** *Python programming provides it's programming facilities to C, C++, JAVA, etc.., and hence python is one of the extensible programming language.*

10. **Embedded**
    - *A programming language is said to be embedded if it takes the programming services of other languages.*
    - **Example:** *Python programming embedded the programming services of C because C is the faster programming language.*
  
11. **Supports third APIs such as NumPy, Pandas, SciPy, Scikit, Matplotlib, Seaborn etc..,**
    - *First party - Modules*
    - *Second party - OS*
    - *Third party - Numpy(Travis), Pandas(MC Kinney)*

---

#### **Importance of Identifiers or Variables:**
**What is an Identifier?**
*An identifier is the name used to identify:*
- *Variables*
- *Functions*
- *Classes*
- *Objects*
- *Modules*
**Example:**
```python
  student_name="Saranya"
```
*Here student_name is Identifier and "Saranya" is Value.*

**What is Variable?**
*A Variable is a memory container used to store data temporarily during program execution.*
**Example:**
```python
 age=20
```
*Here age is Variable name(Identifier) and 20 is Value stored in memory.*

**Importance:**
*Variables and Identifiers are extremely important because they help programs:*
- *Store data*
- *Process data*
- *Reuse data*
- *Manipulate data*
- *Make programs dynamic*
*Without Variables, programming is almost impossible.*

---

#### **Rules for Identifiers/Variables in Python Programming:**
- **RULE-1:** *The Variable name is a combination of Alphabets, Digits and Special Symbol Underscore(_) only.*
- **RULE-2:** *The first letter of Variable must starts with either Alphabet or Underscore(_) only.*
  **Example:** 
  ```python
   >>> sal=34        # Valid
   >>> sal__=34      # Valid
   >>> 123sal=345    # Invalid
   >>> sal1=34       # Valid
   >>> &sal=34       # Invalid
   >>> _sal=34       # Valid
   >>> __=89         # Valid
  ```
- **RULE-3:** *Within the variable name, special symbols are not allowed except underscore(_).*
  **Example:**
  ```python
   >>> emp_sal=9000  # Valid
   >>> emp%sal=6789  # Invalid
   >>> emp sal=9789  # Invalid
  ```
- **RULE-4:** *We should not use Keywords as Variable names because Keywords are reserved words and they have contains some special meaning to the language compiler.*
  **Example:**
  ```python
  >>> if=937   # Invalid
  >>> _if=898  # Valid
  ```
- **RULE-5:** *All the variable names are case-sensitive.*
  **Example:**
  ```python
  >>> AGE=90
  >>> age=90
  ```
  *Both are different variables.*

---

#### **Data Types in Python**
- *Data types define the type of value a variable holds.*
- *The purpose of data types in python is that **"To allocate sufficient amount of memory space in main memory of computer and inputs can stored."***
- *Python programming provides 14 data types and classified into 6 categories. They are*
  - *Fundamental Category data type*
  - *Sequence Category data type*
  - *List Category data type*
  - *Set Category data type*
  - *Dict Category data type*
  - *None Category data type*
  
##### **Fundamental Category data type**
- *The purpose of fundamental category data types is that **"To store single values."***
- *In python programming we have 4 data types in fundamental category. They are*
  1. int
  2. float
  3. bool
  4. complex

###### **int**
- *'**int**' is an immutable type.*
- *'**int**' is one of the pre defined class name and treated as fundamental data type.*
- *The purpose of int data type is that "**To store integer data or whole numbers or integral data(numbers without decimal places)**".*
- *Python integers have unlimited size. Only integers from -5 to 256 are automatically cached and reused by Python.*

**Example:**
```python
>>> a=123
>>> print(a)        # 123
>>> type(a)         # <class 'int'>
>>> id(a)           # 1407134318018
>>> sno=4567        
>>> print(sno, type(sno))   # 4567 <class 'int'>
```

**NOTE:** *One can use class names as variable names.*

**Example:**
```python
>>> int=34                  # Here int is an object/variable
>>> print(int, type(int))   # 34 <class 'int'>
```
--- 

**Cached Integer** - *The actual cached number itself.*
**Example:** 34

**Integer Caching** - *Python reuses small integers(-5 to 256).*
**Example:** a=34
             b=34
 
**Object Referencing** - *Whenever a variable points to an object.*
**Example:** a=10
             Memory a->10

**Reference Assignment** - *When one variable gets reference from another variable.*
**Example:** a=12345
             b=a
       
**Separate Object Creation**
**Example:** a=12345
             b=12345

--- 

**Integer Caching OR Small Integer Caching and also related to Object Interning**

```python
a=34
b=34
print(a,id(a))       # 34 140733555255448
print(b,id(b))       # 34 140733555255448
```

- *Both variables point to SAME object.*
- *This concept is called Integer Caching OR Small Integer Caching and also related to Object Interning.*

---

**Object Referencing OR Reference Assignment**

```python
c=34
d=c
print(c,id(a))      # 34 140733555255448
print(d,id(d))      # 34 140733555255448
```

*This concept is called Object Referencing OR Reference Assignment because multiple variables reference same object.*

---

```python
a=12345
b=a
print(a,id(a))      # 12345 2334956197840
print(b,id(b))      # 12345 2334956197840
```

---

**No Integer Caching OR Separate Object Creation** 

```python
a=257
b=257
print(a,id(a))      # 257 2334956201840
print(b,id(b))      # 257 2334956199600
```

*This concept is called No Integer Caching OR Separate Object Creation and still Object Referencing.*

---

```python
a=12345
b=12345
print(a,id(a))      # 12345 2334956202000
print(b,id(b))      # 12345 2334956200880
```
--- 

```python
a=1
b=True+False
print(a,id(a),type(a))      # 1 140733555254392 <class 'int'>
print(b,id(b),type(b))      # 1 140733555254392 <class 'int'>
```
---

```python
a=True
b=1
print(a,id(a),type(a))      # True 140733554346752 <class 'bool'>
print(b,id(b),type(b))      # 1 140733555254392 <class 'int'>
```
---

**Integer Immutability**

*Once created, integer objects cannot be changed.*

```python
a=10
print(a,id(a))            # 10 140716343600536

a=a+1
print(a,id(a))            # 11 140716343600568
```
*ID's change because new integer object created.*

---

**is vs ==**

*== checks value equality.*

*is checks object identity.*

```python
a=100
b=100

print(a==b)         # True
print(a is b)       # True

c=1000
d=1000

print(c==d)         # True
print(c is d)       # False
```

--- 

**Garbage Collection Relation**

```python
a=10
a=100
print(a)        # 100
```

- *Old reference removed.*
- *If no references exist, the garbage collector cleans memory.*

---

**Type Casting to int**

```python
print(int(10))                    # 10
print(int(89.98))                 # 89
print(int(True))                  # 1
print(int("678"))                 # 678
```
- *int() removes decimal part from float values.*
- *int() does not support:*
  - complex            -> TypeError 
  - str-float          -> ValueError 
  - str-bool           -> ValueError
  - str-complex        -> ValueError
  - str-str            -> ValueError

*With **int** data type, in python programming along with integer data we can also store different number system values. In any programming language we have 4 types of Number systems. They are*

**Number System**

- *Decimal Number System*
- *Binary Number System*
- *Octal Number System*
- *Hexadecimal Number System*

1. **Decimal Number System:** 
   - *Decimal number system is one of the default number system in programming language.*
   - *This number system contains*
     - **Digits:** 0 1 2 3 4 5 6 7 8 9 - Total digits=10
     - **Base:** 10
   - *Base 10 literals are called Decimal Number System values.*
  
2. **Binary Number System:**
   - *Binary Number system is understandable by OS and processor.*
   - *This number system contains*
     - **Digits:** 0 1 - Total digits=2
     - **Base:** 2
   - *Base 2 literals are called Binary Number System values.*
   - *In python programming to store binary data, Binary data must be preceded by letter either 0b or 0B.*
   - *bin() is used converting any number system data into Binary number system type.*

    ```python
    a=0b1010
    print(a,type(a))        # 10 <class 'int'>

    bin(a)                  # '0b1010'
    ```

3. **Octal Number System:**
   - *Octal number system is understandable by Micro processor kits-8086.*
   - *This number system contains*
     - **Digit:** 0 1 2 3 4 5 6 7 - Total digits=8
     - **Base:** 8
   - *Base 8 literals are called Octal number system values.*
   - *In python programming to store octal data, Octal data must be preceded by letter either 0O or 0o.*
   - *oct() is used converting any number system data into Octal number system type.*
  
    ```python
     a=0o56
     print(a,type(a))       # 46 <class 'int'>

     oct(89)                # '0o131'
    ```

4. **Hexadecimal Number System:**
   - *Hexadecimal number system used in development OSes.*
   - *This number system contains*
     - **Digits:** 0 1 2 3 4 5 6 7 8 9 
                   A(10) B(11) C(12) D(13) E(14) F(15) - Total=16
     -  **Base:** 16
   - *Base 16 literals are called Hexadecimal number system values.* 
   - *In python programming to store hexadecimal data, Hexa decimal data must be preceded by letter either 0X or 0x.*
   -  *hex() is used converting any number system data into Hexadecimal number system type.*
   
   ```python
   a=0x90
   print(a,type(a))         # 144 <class 'int'>

   hex(144)                 # '0x90'
   ```

---

###### **float**
- *'**float**' is an immutable data type.*
- *'**float**' is one of the pre-defined class name and treated as fundamental data type.*
- *The purpose of float data type is to store decimal values or floating point numbers.*
- *float data type do not support binary, octal and hexadecimal representations directly.*
- *float data type allows us to store Scientific Notation data.*

**Example:**
```python
a=13.45
print(a,type(a))        # 13.45 <class 'float'>
```

----

**Float Immutability**

- *IDs change because float objects are immutable and a new object is created after modification.*

```python
a=12.5
print(a,id(a))

a=a+1
print(a,id(a))
```

---

**Possible Float Object Reuse OR Interpreter Optimization**

- *Python does not officially cache float values like integers.*
- *Same float IDs may occur due to interpreter optimization or object reuse behavior.*

```python
a=1.00
print(a,type(a),id(a))          # 1.0 <class 'float'> 2870877521008

b=1.00
print(b,type(b),id(b))          # 1.0 <class 'float'> 2870877521008
```

---

**Reference Assignment**

```python
a=2.34
b=a
print(a,type(a),id(a))          # 2.34 <class 'float'> 2870877520720
print(b,type(b),id(b))          # 2.34 <class 'float'> 2870877520720
```

---

**Scientific Notation**

- *Scientific notation is used to represent very large or very small decimal values.*
- *Advantages of Scientific notation is that to take less memory space for bigger floating point values.*

**Example:**
- 3e2  means 3 × 10² = 300.0
- 3e-2 means 3 × 10⁻² = 0.03

```python
a=3e2
print(a,id(a),type(a))          # 300.0 1642266526544 <class 'float'>

b=3e-2
print(b,id(b),type(b))          # 0.03 1642242380016 <class 'float'>
```

---

**Float precision issue**

- *Float values are internally stored in binary format.*
- *Some decimal values cannot be represented exactly in binary.*
- *Therefore small precision errors may occur.*

```python
print(0.1+0.2)              # 0.30000000000000004
```

---

**is vs ==**

```python
a=12.34
b=12.34

print(a==b)
print(a is b)
```

---

**Type casting to float**

```python
print(float(89))          # 89.0
print(float(87.99))       # 87.99
print(float(True))        # 1.0
print(float("90"))        # 90.0
print(float("89.76"))     # 89.76
```

- ***float()** does not support:*
  - complex values         -> TypeError
  - str-str                -> ValueError
  - str-complex            -> ValueError
  - str-bool               -> ValueError

---

###### **bool**
- *'**bool**' is an immutable type.*
- *'**bool**' is one of the predefined class name and treated as fundamental data type.*
- *The purpose of bool data type is "To store True and False values."*
- *In python programming, True and False are called keywords and treated as boolean values.*
- *In python programming internally, True is treated as 1 and False is treated as 0.*

**Example:**

**Boolean Immutability**

```python
a=True
print(a,id(a))          # True 140728191798016

a=False
print(a,id(a))          # False 140728191798048
```

---

**Object Referencing OR Shared Object Referencing OR Singleton Boolean Objects OR Object Reuse**

```python
a=True
b=True

print(a,id(a))            # True 140728191798016
print(b,id(b))            # True 140728191798016
```

---

**Reference Assignment**

```python
a=True
b=a

print(a,id(a))            # True 140728191798016
print(b,id(b))            # True 140728191798016
```

---

**bool-int relationship OR bool() type casting OR Shared object referencing**

```python
a=True
b=bool(1)

print(a,id(a))            # True 140728191798016
print(b,id(b))            # True 140728191798016
```

---

**Arithmetic operations on bool values return int results**

```python
a=True+False
b=bool(1+0)

print(a,id(a))             # 1 140728192705656
print(b,id(b))             # True 140728191798016
```

---

**is vs ==**

```python
a=True
b=1

print(a==b)           # True
print(a is b)         # False
```

---

**Type Casting to bool**

```python
print(bool(1))               # True
print(bool(1.0))             # True
print(bool(0+1j))            # True
print(bool("Saran"))         # True
print(bool("89"))            # True
print(bool("89.67"))         # True
print(bool("False"))         # True
print(bool("8+8j"))          # True
```

---

**Falsy Values**

```python
print(bool(0))              # False
print(bool(0.0))            # False
print(bool(0+0j))           # False
print(bool(""))             # False
print(bool(" "))            # True
print(bool(False))          # False
print(bool(''))             # False
print(bool([]))            # False
print(bool(()))             # False
print(bool({}))            # False
print(bool(set()))          # False
```

---

##### **Sequence Category data type**
##### **List Category data type**
##### **Set Category data type**
##### **Dict Category data type**
##### **None Category data type**


