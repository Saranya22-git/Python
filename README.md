Hey everybody!!!

**PYTHON**

### **Table of Contents**
- [**Table of Contents**](#table-of-contents)
- [**Introduction to Python**](#introduction-to-python)
  - [**Real-Time Applications developed by Python Programming**](#real-time-applications-developed-by-python-programming)
  - [**History of Python**](#history-of-python)
  - [**Versions of Python**](#versions-of-python)
  - [**Features of Python**](#features-of-python)
- [**Python Program Structure**](#python-program-structure)
  - [**Keywords**](#keywords)
  - [**Identifiers**](#identifiers)
  - [**Variables**](#variables)
  - [**Rules for Identifiers/Variables in Python Programming:**](#rules-for-identifiersvariables-in-python-programming)
  - [**Comments**](#comments)
    - [**Single-Line Comment**](#single-line-comment)
    - [**Multi-Line Comment**](#multi-line-comment)
  - [**Indentation**](#indentation)
  - [**Case-Sensitivity**](#case-sensitivity)
  - [**Multiple Assignment**](#multiple-assignment)
  - [**Multiple Variable Assignment**](#multiple-variable-assignment)
  - [**Swapping Variables**](#swapping-variables)
- [**Memory Model \& Internal Concepts**](#memory-model--internal-concepts)
  - [**Objects**](#objects)
  - [**References**](#references)
  - [**Variables Store References**](#variables-store-references)
  - [**id() function**](#id-function)
  - [**type() function**](#type-function)
  - [**Object Identity**](#object-identity)
  - [**Reference Assignment**](#reference-assignment)
  - [**Shared Object Referencing**](#shared-object-referencing)
  - [**Integer Caching**](#integer-caching)
  - [**Mutable vs Immutable**](#mutable-vs-immutable)
  - [**Garbage Collection**](#garbage-collection)
  - [**is vs ==**](#is-vs-)
- [**Data Types in Python**](#data-types-in-python)
  - [**Fundamental Category data type**](#fundamental-category-data-type)
    - [**int**](#int)
    - [**float**](#float)
    - [**bool**](#bool)
    - [**complex**](#complex)
  - [**Sequence Category data type**](#sequence-category-data-type)
    - [**str**](#str)
    - [**List Category data type**](#list-category-data-type)
    - [**Set Category data type**](#set-category-data-type)
    - [**Dict Category data type**](#dict-category-data-type)
    - [**None Category data type**](#none-category-data-type)


---
### **Introduction to Python**

**What is Python?**

*Python is a high-level, interpreted, dynamically typed, general-purpose programming language.*

- ***Created by:** Gudio Van Rossum*
- ***Official release:** 1991*
- ***Official website:** python.org*

**Why was Python created?**

*Simple and readable programming language*

**Why python becomes very popular?**

*Because python is easy to learn, easy to write, less code, huge libraries and supports AI/Data Science/Web Development.*

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

- *Python Programming Language concevied (foundation stone) in the year 1980.*
- *Python Programming Language implementation was began in the year 1989.*
- *Python Programming Language officially released in the year 1991 Feb.*
- *Python Programming Language developed by **Guido van Rossum** (Father of Python)*.
- *Python Programming Language developed at CWI (Centrum Winkunde Informatica) institute in Netherlands.*
- *Python Programming Language managed and maintained by a Non-Commercial Organization called Python Software Foundation(PSF).*
- *The official website of python software foundation(PSF) is www.python.org*

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

   - **Python Interpreter:** 
   
      - *This is the engine of Python.*
      - *It reads your .py file.*
      - *Converts it into something the computer understands.*
      - *Executes it line by line.*
  
   - **Source code(.py file):**
      ```python
        print("Saranya")
      ```

   - **Compilation to Bytecode:**
      - *Python does a hidden step: Your code is converted into Bytecode.*
      - *Stores as .pyc files(inside __pycache__)*
      - *Not human readable.*
      - *Platform independent.*
  

   - **Python Virtual Machine(PVM):**
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
  
    **Low Level Programming Language:** *In Low Level Languages, data is always stored in the form of low level values such as Binary data, Octal data, Hexadecimal data. These number systems are not directly understandable by end-users.*

    **High Level Programming Language:** *In these languages, internally even the programmer specifies the data in the form of low level format such binary data, octal data and hexadecimal data, automatically python programming language execution environment converts into high level data which is understandable by end-users. Hence python is one of the **High Level Programming Language.***

7. **Robust**(Strong)
   
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

### **Python Program Structure**

#### **Keywords**

- *Keywords are reserved words in Python that already have predefined meaning.*
- *Python interpreter already understands them so we should not use keywords as variable names.*

**Examples of Keywords:**

*False    None    True    and   as    assert    async        await    break   class   continue    def   del  elif  else  except  finally  for  from  global  if  import  in  is  lambda  nonlocal  not  or  pass  raise  return  try  while  with  yield*

**How to see all Keywords:**

```python
import keyword
print(keyword.kwlist)
```

#### **Identifiers**

*An identifier is the name used to identify variables, functions, classes, modules, objects.*

**Example:**
```python
  student_name="Saranya"
```
*Here student_name is Identifier and "Saranya" is Value.*

#### **Variables**

- *A Variable is a memory container used to store data temporarily during program execution.*
- *In Python, variables store references to objects not actual values directly.*

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

#### **Comments**

*Comments are non-executable statements used for explanation/documentation.*

##### **Single-Line Comment**

```python
# This is Single-Line comment
print("Hello")
```

##### **Multi-Line Comment**

```python
"""
This is Multi-Line
Comment
"""
```

---

#### **Indentation**

- *Space/tabs given before code statements.*
- *Python uses indentation to define code blocks instead of curly braces {}.*

#### **Case-Sensitivity**

*Python is Case-Sensitive.*

```python
name="Saranya"
Name="Python"

print(name)
print(Name)
```

---

#### **Multiple Assignment**

```python
a=b=c=100

print(a)
print(b)
print(c)
```
*This is called Share object referencing.*

#### **Multiple Variable Assignment**

```python
a,b,c=10,20,30

print(a)
print(b)
print(c)
```

#### **Swapping Variables**

```python
a=10
b=20

a,b=b,a

print(a)
print(b)
```
- *Python special feature.*
- *Internally, Python uses tuple packing/unpacking.*

---

### **Memory Model & Internal Concepts**

#### **Objects**

- *Everything in python is treated as an Object.*
- *Object contains value/data, datatype, memory location.*

**Examples:** *int, float, bool, list, function, class*

```python
a=10

# Here 10 is Object.
```

```python
name="Saranya"

# Here "Saranya" is String Object.
```

#### **References**

- *Reference is the memory link/address pointing to an object.*
- *Python variables do not store actual values directly. They store references to objects.*

```python
a=10

# Memory representation a->10
# Here a-reference/variable, 10-object
```

#### **Variables Store References**

```python
a=[1,2,3]

# Memory-a->[1,2,3]
# Variable-a stores reference. NOT actual list internally.
```

#### **id() function**

- *id() returns unique identity/memory reference value of object.*

```python
a=10

print(id(a))         # 140728203512 (number changes system-to-system)
```

- *If two variables have same id() then both reference same object.*

```python
a=10
b=a

print(a)
print(b)
```

#### **type() function**

*type() returns datatype/class of object.*

```python
a=10

print(type(a))      # <class 'int'>
```

#### **Object Identity**

- *Identity means uniqueness of object in memory.*
- *Python checks identity using id() or is operator.*

```python
a=10
b=10

print(id(a))        
print(id(b))        
```

*Possibly same IDs because Integer Caching.*

#### **Reference Assignment**

```python
a=[1,2]
b=a

print(a)
print(b)
```

- *Both variables reference SAME object.*
- *b=a does NOT create copy. It copies reference.*

#### **Shared Object Referencing**

```python
a=100
b=100

print(id(a))
print(id(b))

id(a)==id(b)
```

*Especially for -5 to 256 due to Integer Caching.*

#### **Integer Caching**

- *Python internally caches small integers from -5 to 256.*
- *Instead of creating new objects repeatedly python reuses existing objects.*

```python
a=100
b=100

print(id(a))
print(id(b))
```
*Same IDs*

```python
a=10002
b=10002

print(id(a))
print(id(b))
```

*May produce same IDs or different IDs depending on optimization.*

#### **Mutable vs Immutable**

**Immutable Objects:** *Objects whose values cannot be changed after creation.*

**Immutable Types:** 

- *int*
- *float*
- *bool*
- *complex*
- *str*
- *tuple*
- *frozenset*

```python
a=10
print(id(a))

a=a+1
print(a,id(a))
```

*IDs change because new object created. Old object unchanged.*

**Mutable Objects:** *Objects whose values can be modified after creation.*

**Mutable Types:**

- *list*
- *dict*
- *set*
- *bytearray*

```python
a=[1,2]
print(id(a))

a.append(3)
print(a,id(a))
```

*Usually same ID because object modified internally. NOT recreated.*

#### **Garbage Collection**

*Python automatically removes unused objects from memory.*

```python
a=10
a=20

print(a)
```

*Old=10 may become unused. Garbage collector can clean it. Without Garbage collection memory waste.*

#### **is vs ==**

- ***==** checks VALUE equality.*
- ***is** checks OBJECT identity.*

```python
a=[1,2]
b=[1,2]

print(a is b)          # True
print(a==b)          # False
```

```python
a=b=[1,2]

print(a==b)
print(a is b)
```

---

### **Data Types in Python**

- *Data types define the type of value a variable holds.*
- *Python automatically identifies datatype. This is Dynamic Typing.*
- *Python programming provides 14 data types and classified into 6 categories. They are*
  - *Fundamental Category data type*
  - *Sequence Category data type*
  - *List Category data type*
  - *Set Category data type*
  - *Dict Category data type*
  - *None Category data type*
  
#### **Fundamental Category data type**

- *The purpose of fundamental category data types is that **"To store single values."***
- *In python programming we have 4 data types in fundamental category. They are*
  1. int
  2. float
  3. bool
  4. complex

##### **int**
- *'**int**' is an immutable type.*
- *'**int**' is one of the predefined class name and treated as fundamental data type.*
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
*IDs change because new integer object created.*

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
   - *In python programming to store hexadecimal data, Hexadecimal data must be preceded by letter either 0X or 0x.*
   -  *hex() is used converting any number system data into Hexadecimal number system type.*
   
   ```python
   a=0x90
   print(a,type(a))         # 144 <class 'int'>

   hex(144)                 # '0x90'
   ```

---

##### **float**

- *'**float**' is an immutable data type.*
- *'**float**' is one of the pre-defined class name and treated as fundamental data type.*
- *The purpose of float data type is to store decimal values or floating point numbers.*
- *float data type does not support binary, octal and hexadecimal representations directly.*
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
print(a,id(a))          # 12.5 2707329680496

a=a+1
print(a,id(a))          # 13.5 2707329680208
```

---

**Possible Float Object Reuse OR Interpreter Optimization**

- *Python does not officially cache float values like integers.*
- *Same float IDs may occur due to interpreter optimization or object reuse behavior.*

```python
a=10.98
b=10.98

print(id(a))          # 1959594296688
print(id(b))          # 1959600251888
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

print(a==b)                 # True
print(a is b)               # False
```

---

**Type casting to float**

```python
print(float(89))          # 89.0
print(float(87.99))       # 87.99
print(float(True))        # 1.0
print(float("90"))        # 90.0
print(float("89.76"))     # 89.76
print(float("3e2"))       # 300.0
```

- ***float()** does not support:*
  - complex values         -> TypeError
  - str-str                -> ValueError
  - str-complex            -> ValueError
  - str-bool               -> ValueError

---

##### **bool**
- *'**bool**' is an immutable type.*
- *'**bool**' is one of the predefined class name and treated as fundamental data type.*
- *The purpose of bool data type is "To store True and False values."*
- *In python programming, True and False are called keywords and treated as boolean values.*
- *In python programming internally, True is treated as 1 and False is treated as 0.*
- *Used for conditions, decision making, comparisons, logical operations.*

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

**Truthy Values**

```python
print(bool(100))            # True
print(bool(" "))            # True
print(bool(' '))            # True
print(bool("Saran"))        # True
print(bool([1,2]))          # True
print(bool((1,2)))          # True
print(bool({1:3}))          # True
print(bool("False"))        # True         
```

---

**Falsy Values**

```python
print(bool(0))              # False
print(bool(0.0))            # False
print(bool(0+0j))           # False
print(bool(""))             # False
print(bool(False))          # False
print(bool(''))             # False
print(bool([]))            # False
print(bool(()))             # False
print(bool({}))            # False
print(bool(set()))          # False
print(bool(None))           # False
```

---

##### **complex**

- *'**complex**' is an immutable type.*
- *'**complex**' is one of the predefined class names and treated as fundamental data type.*
- *The purpose of complex data type is "To store complex numbers containing real and imaginary parts."*
- *The general notation of complex data type is given below*
  
          x+yj or x-yj

  - *Here "x" is called Real part*.
  - *Here "y" is called Imaginary part.*
  - *"j" is called imaginary unit and represents √(-1)*

**Examples:**

**Complex datatype representation**

```python
a=2+5j
print(a,type(a))                  # (2+5j) <class 'complex'>
```

---

**Complex Immutability**

```python
a=2+5j
print(a,id(a),type(a))              # (2+5j) 2023119824368 <class 'complex'>

a=a+1
print(a,id(a),type(a))              # (3+5j) 2023119824976 <class 'complex'>
```

**Separate Object Creation OR Object Referencing**

```python
a=3+3j
b=3+3j

print(a,id(a))                # (3+3j) 2023119820784
print(b,id(b))                # (3+3j) 2023119824944              
```

---

**Reference Assignment**

```python
a=3+3j
b=a

print(a,id(a))                # (3+3j) 2023119824976
print(b,id(b))                # (3+3j) 2023119824976
```

---

**Real and Imaginary parts**

```python
a=2+3j

print(a.real)             # 2.0
print(a.imag)             # 3.0
```

---

**Two-Argument complex()**

```python
complex(real, imaginary)

print(complex(2,9))         # (2+9j)
```

---

**is vs ==**

```python
a=2+3j
b=2+3j


print(a==b)           # True
print(a is b)         # False
```

---

**No ordering comparison**

```python
(2+3j) >= (2+3j)
```

- *Complex numbers cannot use: < > >= <=*
  
---

**Type Casting to complex**

```python
print(complex(10))              # (10+0j)
print(complex(9.9))             # (9.9+0j)
print(complex(True))            # (1+0j)
print(complex(False))           # 0j
print(complex("10"))            # (10+0j)
print(complex("67.98"))         # (67.98+0j)
print(complex("2+5j"))          # (2+5j)
```

 - *complex() does not support:*
   - str-bool->ValueError
   - str-str->ValueError
  
---

**Complex values do not support direct int/float conversion**

```python
int(2+3j)                   # TypeError
float(2+7j)                 # TypeError 
```

---

**Complex literals do not support spaces inside string conversion**

```python
complex("2 + 3j")            # ValueError
```

---

#### **Sequence Category data type**

- *The purpose of sequence category data types is that "To store sequence of values."*
- *In python programming, we have 4 data types in Sequence category. They are*
  1. str
  2. bytes
  3. bytearray
  4. range

##### **str**


- *'**str**' is an immutable type.*
- *'**str**' is one of the predefined class and treated as Sequence data type.*
- *The purpose of str data type is "To store string data or text data or alphanumeric data or numeric data or special symbols within double quotes or single quotes or tripple double quotes or tripple single quotes."*

**Example:**

```python
name="Python"
print(name,type(name))           # Python <class 'str'>

name                             # 'Python'
```

---

**Types of str**

- *In python programming we have two types of str data. They are*
  1. Single line string data
  2. Multi line string data

 **Single Line String data**

  ```python
  varname='Single line string data'
              OR
  varname="Single line string data"
  ```

  - *With the help of double quotes("") and Single quote('') we can store Single line str data only but not possible to store multi line string data.*

   **Example:**

   ```python
    name="Saranya"
    branch='Ai&ds'

    print(name)           # Saranya
    print(branch)         # Ai&ds
   ```

 **Multiple Line String data**

  ```python
  varname='''String data 1
             String data 2
             -------------
             String data-n'''
              OR
  varname="""String data 1
             String data 2
             -------------
             String data-n"""
  ```

  - *With the help of triple double quotes(""" """) and tripple single quote(''' ''') we can store Single line str data and multi line string data.*

   **Example:**

   ```python
   name="""Hello, Saranya. 
        How are you?"""

   branch='''Artificial Intelligence and
          Data Science'''


  print(name)
  print(branch)
  ```

---

**Immutability type**

  ```python
   name="Python"

   print(name,id(name))             # Python 2902389817632

   name="Python"+'123'

   print(name,id(name))             # Python123 2902490339312
   ```

---

**Operations on str data**

- *On str data, we can perform two types of operations. They are*
    **1. Indexing**

     - *The process of obtaining single value from given main str object is called **Indexing**.*
     - **Syntax:** *strobj[index]*
        - *Here strobj is an ojbect of <class 'str'>*
        - *Index represents either +ve index or -ve index.*
        - *If we enter valid index value then we get corresponding indexed value.*
        - *If we enter invalid index value then we get IndexError.*
     - **Example:**
        ```python
        a="Python"
        ``` 

        **Positive Indexing:**

          P   y   t   h   o   n

          0   1   2   3   4   5

        **Negative Indexing:**

          P   y   t   h   o   n

         -6  -5  -4  -3  -2  -1

     - **Access Characters**
        ```python
        s="Python"

        print(s,type(s))             # Python <class 'str'>
        print(s[0])                  # P
        print(s[-6])                 # P
        print(s[5])                  # n
        s[2]                         # 't'

        print(s[-7])                 # IndexError
        ```

        ```python
        >>> s="123456789"
        >>> print(s,type(s))         123456789 <class 'str'>
        >>> s[2]                     '3'
        >>> s[-1]                    '9'
        >>> s[len(s)-1]              '9'
        >>> s[-len(s)]               '1'
        ```

    **2. Slicing**

     - *The process of obtaining range of values or substring from given main str object is called Slicing.*
     - *To perform slicing operations, we have 5 syntaxes. They are:*
      
        **NOTE:** *start included...end excluded*

       - **Syntax-1:** *strobj[BEGIN:END]*
        
         - *This syntax generates ranges of values or substring from BEGIN Index to END-1 index provided **BEGIN<END** otherwise we never get any result or space or '' as a result.* 
         - **Examples:**
            ```python
            s="PYTHON"

            print(s,type(s))          # PYTHON <class 'str'>
            print(s[0:3])             # PYT
            print(s[2:6])             # THON
            print(s[1:6])             # YTHON
            print(s[0:6])             # PYTHON
            s[2:1]                    # '' because here BEGIN index is greater than END index
            ``` 

         - **Sub Rule:** ***strobj[BEGINPOSINDEX:ENDNEGATIVEINDEX]***
         - *This syntax gives range of characters from BEGINPOSINDEX to ENDNEGATIVEINDEX-1 provided BEGINPOSINDEX>ENDNEGATIVEINDEX. Otherwise we get space or no result or '' as a result.*
         - **Examples:**
          ```python
          s='saranya'

          print(s[3:8])           # anya
          print(s[3:-8])          # 
          print(s[2:-1])          # rany
          s[2:-2]                 # 'ran'
          ``` 
          
       - **Syntax-2:** *strobj[BEGIN:]*

         - *In this syntax, we are specifying BEGIN index and we didn't specify END index.* 
         - *If we don't specify END index then PVM takes END index as len(strobj).*
         - **Examples:** 
          ```python
          s='saranya'

          print(s[3:])            # anya
          print(s[4:])            # nya
          print(s[-1:])           # a
          ```

       - **Syntax-3:** *strobj[:END]*
         
         - *In this syntax, we are specifying END index and we didn't specify BEGIN index.*
         - *If we don't specify BEGIN index then PVM takes BEGIN index as 0 or -len(strobj).*
         - **Examples:**
           ```python
            s='saranya'

            print(s[:5])            # saran
            print(s[:-1])           # sarany
            print(s[:90])           # saranya
            s[:-89]                 # ''
           ``` 
           
       - **Syntax-4:** *strobj[:]*

         - *In this syntax, we are not specifying BEGIN index and END index.*
         - *If we don't specify BEGIN index and END index then PVM takes BEGIN index as 0 or -len(strobj) and END index as len(strobj) or -1.*
         - *Hence this syntax always gives total string data.*
         - **Examples:**
           ```python
            s='saranya'

            print(s[:])           # saranya
            print(s[0:])          # saranya
            print(s[:len(s)])     # saranya
            print(s[-len(s):])    # saranya
            s[:0]                 # ''
           ```  
        - **NOTE:** *All the above syntaxes are extracting the data from strobj in forward direction with default step value 1.*
         
       - **Syntax-5:** *strobj[BEGIN:END:STEP]* 

         - **RULE-1:** *Here BEGIN, END and STEP values can be either +ve or -ve.*
         - **RULE-2:** *If STEP value is +ve then PVM takes the range of characters from BEGIN Index to END-1 index in FORWARD direction with step value provided **BEGIN INDEX<END INDEX** otherwise we get space or ' ' as a result.*
           - **Examples:** 
           ```python
            s="saranya"

            print(s[::1])               # saranya
            print(s[0:-1:1])            # sarany
            print(s[0::2])              # srna
            print(s[::3])               # saa
            print(s[-6:-1:2])           # aay
           ```  
         - **RULE-3:** *If STEP value is -ve then PVM takes the range of characters from BEGIN Index to END-1 index in BACKWARD direction with step value provided **BEGIN INDEX>END INDEX** otherwise we get space or ' ' as a result.*
           - **Examples:**
            ```python
              s="saranya"

              print(s[::-1])          # aynaras
              print(s[::-3])          # aas
              print(s[7::-1])         # aynaras
              print(s[::2][::-1])     # anrs
              print(s[-1:-7:-1])      # aynara
            ``` 
         - **RULE-4:** *In FORWARD direction, if END value is 0 then we get space or ' ' as a result.*
           - **Examples:**
            ```python
              s='saranya'

              print(s[:0:])           # 
              print(s[2:0:1])         #
            ``` 
         - **RULE-5:** *In BACKWARD direction, if END value is -1 then we get space or ' ' as a result.*
           - **Examples:**
            ```python
              s='saranya'

              print(s[:-1:-1])        #
              print(s[:-1:])          # sarany
              print(s[:-1:-3])        #
            ```


  

   

  
##### **List Category data type**
##### **Set Category data type**
##### **Dict Category data type**
##### **None Category data type**


