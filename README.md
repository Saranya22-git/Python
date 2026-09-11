Hey everybody!!!

**PYTHON**

# **Table of Contents**
- [**Table of Contents**](#table-of-contents)
- [**Programming Foundations**](#programming-foundations)
  - [**Introduction to Programming**](#introduction-to-programming)
    - [**Programming**](#programming)
    - [**Program**](#program)
    - [**Coding**](#coding)
    - [**Software vs Hardware**](#software-vs-hardware)
    - [**Compiler**](#compiler)
    - [**Interpreter**](#interpreter)
    - [**High-Level Languages**](#high-level-languages)
    - [**Low-Level Language**](#low-level-language)
    - [**Machine Language**](#machine-language)
    - [**Assembly Language**](#assembly-language)
    - [**Procedural Programming**](#procedural-programming)
    - [**Object-Oriented Programming (OOP)**](#object-oriented-programming-oop)
    - [**Why Python?**](#why-python)
  - [**Algorithm Fundamentals**](#algorithm-fundamentals)
    - [**Algorithm**](#algorithm)
    - [**Characteristics of a good algorithm**](#characteristics-of-a-good-algorithm)
    - [**Writing Algorithms**](#writing-algorithms)
    - [**Algorithm Design Basics**](#algorithm-design-basics)
  - [**Flowcharts**](#flowcharts)
    - [**Flowchart Basics**](#flowchart-basics)
    - [**Flowchart Symbols**](#flowchart-symbols)
    - [**Loops in Flowcharts**](#loops-in-flowcharts)
  - [**Pseudocode**](#pseudocode)
    - [**Converting Pseudocode to Python**](#converting-pseudocode-to-python)
- [**Python Fundamentals**](#python-fundamentals)
  - [**Introduction to Python**](#introduction-to-python)
    - [**What is Python?**](#what-is-python)
    - [**History of Python**](#history-of-python)
    - [**Features of Python**](#features-of-python)
    - [**Applications of Python**](#applications-of-python)
    - [**Python Versions**](#python-versions)
    - [**Python Distributions**](#python-distributions)
    - [**Python Execution Environment**](#python-execution-environment)
    - [**Python Compiler**](#python-compiler)
    - [**Python Interpreter**](#python-interpreter)
    - [**Bytecode**](#bytecode)
    - [**Python Virtual Machine (PVM)**](#python-virtual-machine-pvm)
    - [**Python Runtime Environment**](#python-runtime-environment)
    - [**Interactive Mode vs Script Mode**](#interactive-mode-vs-script-mode)
    - [**Python Shell (REPL)**](#python-shell-repl)
    - [**Installing Python and IDLE**](#installing-python-and-idle)
    - [**IDLE**](#idle)
  - [**Python Program Structure**](#python-program-structure)
    - [**Keywords**](#keywords)
      - [**Keywords (Reserved Words)**](#keywords-reserved-words)
      - [**Keywords (Keyword Module)**](#keywords-keyword-module)
    - [**Identifiers**](#identifiers)
    - [**Variables**](#variables)
      - [**Variable Creation**](#variable-creation)
      - [**Variable Swapping**](#variable-swapping)
      - [**Dynamic Typing**](#dynamic-typing)
    - [**Comments**](#comments)
      - [**Single-Line Comment**](#single-line-comment)
      - [**Multi-Line Comment**](#multi-line-comment)
      - [**Docstrings**](#docstrings)
    - [**Indentation**](#indentation)
    - [**Case-Sensitivity**](#case-sensitivity)
- [**Data Types**](#data-types)
  - [**Numeric Types**](#numeric-types)
    - [**Integer (int)**](#integer-int)
      - [**Number Systems**](#number-systems)
        - [**bin()**](#bin)
        - [**oct()**](#oct)
        - [**hex()**](#hex)
    - [**float**](#float)
      - [**Scientific Notation**](#scientific-notation)
      - [**Precision Values**](#precision-values)
    - [**bool**](#bool)
      - [**Boolean Values**](#boolean-values)
      - [**Truthy and Falsy Values**](#truthy-and-falsy-values)
    - [**complex**](#complex)
  - [**Strings**](#strings)
    - [**Creating a String**](#creating-a-string)
    - [**Indexing**](#indexing)
    - [**String Slicing**](#string-slicing)
    - [**Negative Indexing**](#negative-indexing)
    - [**Step Slicing**](#step-slicing)
    - [**String Immutability**](#string-immutability)
    - [**String Interning**](#string-interning)
    - [**Escape Characters**](#escape-characters)
    - [**Raw Strings**](#raw-strings)
    - [**Unicode**](#unicode)
    - [**ASCII**](#ascii)
    - [**ord()**](#ord)
    - [**chr()**](#chr)
  - [**Formatting**](#formatting)
    - [**f-string**](#f-string)
    - [**format()**](#format)
    - [**%**](#)
  - [**String Methods**](#string-methods)
    - [**Case Methods**](#case-methods)
    - [**Search Methods**](#search-methods)
    - [**Validation Methods**](#validation-methods)
    - [**Replace Methods**](#replace-methods)
    - [**Split**](#split)
    - [**Join**](#join)
    - [**Alignment**](#alignment)
      - [**```ljust()```**](#ljust)
      - [**```rjust```**](#rjust)
      - [**```center()```**](#center)
      - [**```zfill()```**](#zfill)
  - [**Lists**](#lists)


---

# **Programming Foundations**

## **Introduction to Programming**

### **Programming**

**What is Programming?**

- *Programming is the process of giving instructions to a computer to perform a specific task.*
- *A computer is a machine. It cannot think, decide, or understand of human language on its own.*
- *It only follows instructions.*
- *Those instructions are called a program and the process of writing those instructions is called Programming.*

OR

- *Programming is the process of designing, writing, testing and maintaining instructions (called programs) that tell a computer how to perform specific tasks.*

---

**Example:** *Imagine you are teaching a robot to make tea.*

  *You must tell it:*
  1. *Take a cup*
  2. *Boil water*
  3. *Add tea powder*
  4. *Add sugar*
  5. *Pour into cup*
      
*The robot will follow only the instructions you provide. Similarly, a computer follows instructions written by a programmer.*

---

**Why do we need Programming?**

- *Without programming:*
   - *No websites*
   - *No mobile apps*
   - *No games*
   - *No Instagram*
   - *No YouTube*
   - *No Whatsapp*
   - *No ChatGPT*

*Everything software-related is created through programming.* 

---

**Applications of Programming**

- **Web Development:** *Websites, E-commerce platforms.*
    
  **Example:** *Amazon, Flipkart* 

- **Mobile Apps**
    
  **Example:** *WhatsApp, Instagram, Telegram.*

- **Data Science:** *Used for Data Analysis, Machine Learning, AI.*
- **Automation**
    
  **Example:** *Instead of manually renaming 1000 files, write a program. Computer does it automatically.* 

- **Game Development**
    
  **Example:** *Minecraft, PUBG: Battlegrounds.* 

- **Cybersecurity:** *Programming is used to detect attacks, create security tools, analyze malware.*

---

### **Program**

**What is a Program?**

- *A program is a collection of instructions written in a programming language to perform a specific task.*
- *A program tells the computer:*
  - *What to do*
  - *How to do it*
  - *When to do it*

**Example:** *Imagine a recipe for making biryani.*

  *The recipe contains steps:*
  1. *Wash rice*
  2. *Cook rice*
  3. *Prepare masala*
  4. *Mix ingredients*
  5. *Serve*

*The recipe is a set of instructions.*

---

### **Coding**

**What is Coding**

- *Coding is the process of converting logic, algorithms, or solutions into a programming language that a computer can understand and execute.*
  
**Example:** *Imagine your teacher asks ```Find the sum of two numbers```.*

**Step-1:** *Think of the logic*
- *Take first number*
- *Take second number*
- *Add them*
- *Display result*

*This is Logic.*

**Step-2:** *Convert Logic into Python*
```python
a=10
b=20
print(a+b)
```

*This conversion of logic into Python code is called Coding.*

---

**Coding vs Programming**

| Coding                   | Programming                                       |
| ------------------------ | ------------------------------------------------- |
| Writing code             | Complete software development process             |
| Converts logic into code | Includes logic design, coding, testing, debugging |
| Smaller activity         | Bigger activity                                   |
| Part of programming      | Entire process                                    |

---

### **Software vs Hardware**

**Hardware:** *Hardware refers to the physical components of a computer that can be seen and touched.*

**Software:** *Software is a collection of programs and instructions that tells the hardware what to do.*

---

**Why do we need both?**

- *Imagine you bought a brand-new laptop. It has CPU, RAM, SSD, Monitor, Keyboard. But windows is not installed.*
- *Can you use it? No.*
- *Now imagine you have Windows on a USB drive but no laptop. Can Windows run by itself? No.*

*Hardware and Software depend on each other.*
- *Hardware without software is useless.*
- *Software without hardware cannot run.*

---

**Hardware Examples**

- **Internal Hardware:** *CPU, RAM, Motherboard, SSD, HDD, GPU*
- **External Hardware:** *Keyboard, Mouse, Monitor, Printer, Speakers*

**Software Examples**

- **System Software:** *Windows, Linux, macOS*
- **Application Software:** *Google Chrome, Microsoft Word, VS Code, WhatsApp, Spotify*

---

**Example:** *Suppose you open Google Chrome. What actually happens?*

*You Click Chrome → Windows loads Chrome → CPU executes instructions → RAM stores temporary data → Monitor displays Chrome.*

---

**Hardware vs Software**

| Hardware                | Software                         |
| ----------------------- | -------------------------------- |
| Physical components     | Programs & instructions          |
| Can be touched          | Cannot be touched                |
| Manufactured            | Developed by programmers         |
| Can wear out physically | Can have bugs or become outdated |
| Examples: CPU, RAM      | Examples: Windows, Chrome        |

---

### **Compiler**

**Problem:** *Computers understand only 0 and 1. This is called Machine Learning and Machine Code.*

**Example:** 

```txt
10110011
01010101
11100010
```

- *Humans cannot easily write programs in this form. So we use languages like Python, Java, C, C++. These are easier for humans.*
- *But the computer still understands only 0s and 1s. So we need a translator.*
- *That translator is called a ```Compiler```.*

**Compiler:** *A compiler is a software program that translates the entire source code into machine code before execution.*

**Example:** *Imagine you speak Telugu and your friend speaks Japanese. Neither of you understands the other's language. A translator converts Telugu-Japanese. Similarly Python/C code - Machine code. Compiler acts as the translator.*

---

**How compiler works**

**Step-1:** *Programmer writes code.*

**Step-2:** *Compiler reads entire code.*

**Step-3:** *Compiler converts code into machine language.*

**Step-4:** *Computer executes machine language.*

**NOTE:** *Compiler translates the whole program at once. Only after successful translation does execution start.*

---

**Compiler Languages**

**Examples:**
- *C*
- *C++*
- *Go*
- *Rust*

*These languages mainly use compilers. Java and Python also use compilation as part of their execution process, but not in the same way as C or C++.*

---

**Characteristics of a Compiler**

*A Compiler*
- *Translates the entire program before execution.*
- *Reports errors after compiling the whole program.*
- *Produces machine code.*
- *Compiled programs generally execute faster after successful compilation.*

---

### **Interpreter**

**Interpreter:** *An Interpreter is a software program that translates and executes source code one line at a time.*

**Example:** *Imagine a translator helping two people talk.*

---

**Compiler Style:**
- *Person A speaks everything. Translator converts everything. Then Person B hears everything.*

**Interpreter Style:**
- *Person A speaks one sentence. Translator translates it. Person B hears it. Then next sentence. Then next sentence. This is how an interpreter works.*

---

**How Interpreter works?**

```python
a=10
b=10
print(a+b)
```

**Step-1:** *Reads a=10 and executes it.*

**Step-2:** *Reads b=10 and executes it.*

**Step-3:** *Reads print(a+b) and executes it.*

**NOTE:** *Interpreter translates and executes code line by line.*

---

**Languages that use Interpreters:**

**Example:**

- *Python*
- *JavaScript*
- *Ruby*
- *PHP*

---

**Characteristics of an Interpreter**

*An Interpreter*
- *Translates one statement at a time.*
- *Executes immediately after translation.*
- *Stops as soon as it encounters an error.*
- *Does not require the entire program to be translated before execution.*

---

### **High-Level Languages**

**High-Level Language:** *A High-Level Language(HLL) is a programming language that is easy for humans to read, write and understand. It uses english-like words and symbols instead of binary (0s and 1s). It requires a translator(compiler or interpreter) to convert it into machine language.*

---

**Why do we need high-level languages?**

- *Imagine writing this every time you wanted to display "Hello": 0101010 010101 010101 0101010000. This is machine language.*
- *It's difficult for humans to read, write, debug and remember. Instead we write `print("Hello")`. This is much easier.*

**Example:** *Imagine you want to tell your friend to open the door.*
- **Human Language:** *Please open the door. Easy to understand.*
- **Machine Language:** *Imagine saying 101010 10101 1010101 010101. Nobody would understand.*
- *Similarly humans prefer High-Level languages. Computers understand machine language. So a compiler or interpreter acts as a translator.*

---

**Examples of High-Level Languages:**

- *Python*
- *Java*
- *C*
- *C#*
- *Ruby*
- *PHP*
- *JavaScript*
- *Swift*
- *Kotlin*
- *Go*

*These languages are designed to be easy for programmers.*

---

**Characteristics of High-Level Languages**

- **Easy to read:** *`print("Hello")`. Even someone new to programming can understand this.*
- **Easy to write:** *You don't need to write binary. Instead of 101010101. You write `print("Hello")`*
- **Easy to debug:** *If there is an error. `print(name)`. Python shows a meaningful error message. This makes debugging easier.*
- **Portable(Platform Independent):** *Many high-level langauges can run on different operating systems. The same python program can run on Windows, Linux, macOS without changing the code(provided python is installed).*
- **Faster Development:** *Because the syntax is simple, developers can write programs quickly. Example: Building a calculator in python requires much less code than in machine language.*
- **Easier Maintenance:** *Programs written in high-level languages are easier to update and modify. Example: If a company wants to add a new feature to its application, developers can understand and modify the code more easily.*

---

**Advantages of High-level language**

- *Easy to learn*
- *Easy to write*
- *Easy to debug*
- *Easy to read*
- *Faster development*
- *More productive*
- *Easy to maintain*
- *Portable across platforms*

**Disadvantages of High-level languages**

- **Slower than low-level languages:** *Because the code must first be translated into machine language.*
- **Uses more memory:** *High-level languages often require more memory than low-level languages.*
- **Less hardware control:** *You cannot directly control hardware as easily as with low-level languages. Example: Writing an operating system is generally done in languages like C rather than Python because they provide lower-level access to hardware.*

---

**Applications**

*High-level languages are used to build:*
- *Websites*
- *Mobile applications*
- *Desktop software*
- *Games*
- *AI applications*
- *Data analysis tools*
- *Automation scripts*

---

### **Low-Level Language**

**Low-Level Language:** *A Low-Level Language is a programming language that is very close to the computer's hardware and machine language. It is not easy for humans but it is easy for the computer to understand.*

---

**Why do we need low-level languages?**

- *Imagine you want to control every small operation of a computer.*
- *For example Access memory directly, Control CPU registers, Write an operating system, Create Device drivers.*
- *High-Level languages hide these details.*
- *Low-Level languages allow programmers to interact much more closely with the hardware.*

---

**Example:** *Think of driving a car.*
- **Automatic Car:** *You only Start, Accelerate, Brake. The car automatically changes gears. This is like a High-Level Language.*
- **Manual Car:** *You must Change gears, Control Clutch, Control engine speed. You have more control but it is harder. This is like a Low-Level Language.*

---

**Types of Low-Level Languages:** *There are two types of Low-Level Languages.*

1. **Machine Language:** *Uses only 0 and 1.*

   **Example:** *1010101010*
    
   *The computer understands this directly. Humans find it very difficult.*

2. **Assembly Language:** 
   - *Instead of binary 101010110. We write MOV A,B ADD A,C SUB A, D.*
   - *Assembly language uses mnemonics(short english-like words) to represent machine instructions.*
   - *An Assembler translates Assembly Language into Machine Language.*

---

**Characteristics of Low-Level Languages**

- **Close to hardware:** *Programs interact directly with hardware.*
  **Example:** *CPU, Memory, Registers*
- **Faster Execution:** *Since the instructions are very close to machine code, execution is very fast.*
- **Efficient memory usage:** *Programs often use less memory.*
- **Difficult to learn:** *Binary numbers and Assembly instructions are harder than Python.*
- **Machine Dependent:** *A program written for one processor architecture may not work on another. For example, Assembly code written for one CPU may need changes for another CPU.*

---

**Advantages of Low-Level languages**

- **Very fast:** *Programs execute quickly.*
- **Higher Performance:** *Suitable for performance-critical applications.*
- **Direct Hardware Control:** *Programmers can directly access hardware resources.*
- **Less memory usage:** *Efficient use of memory.*

**Disadvantages of Low-Level languages**

- **Difficult to read:** *Binary and Assembly are harder for humans.*
- **Difficult to write:** *Writing programs takes more effort.*
- **Difficult to debug:** *Finding and fixing errors is more challenging.*
- **Less portable:** *Programs are often specific to a particular processor.*

---

**Applications of Low-Level languages**

*Low-Level langauges are used in:*
- *Operating Systems*
- *Device Drivers*
- *Embedded Systems*
- *Firmware*
- *Robotics*
- *Microcontrollers*
- *Game Engines(performance-critical parts)*

---

**High-Level vs Low-Level languages**

| High-Level Language      | Low-Level Language                            |
| ------------------------ | --------------------------------------------- |
| Easy for humans          | Difficult for humans                          |
| Uses English-like syntax | Close to machine code                         |
| Easier to debug          | Harder to debug                               |
| Portable                 | Often machine dependent                       |
| Slower than low-level    | Faster execution                              |
| Examples: Python, Java   | Examples: Machine Language, Assembly Language |

---

**Examples:**

- **Windows Operating System:** *Parts of the operating system are written in low-level languages to communicate efficiently with hardware.*
- **Device Drivers:** *Drivers for keyboards, printers, graphics cards and network adapters often use low-level programming.*
- **Embedded Systems:** *Devices like washing machines, microwave ovens, and smart watches use low-level programming to interact directly with hardware.*

---

### **Machine Language**

- *Machine Language is the lowest-level programming language that consists only of binary digits (0 and 1).*
- *It is the only language that a computer's CPU can directly understand and execute.*

---

**Why is it called Machine Language?**

- *It is called Machine Language because it is the native language of the machine(computer).*
- *Just as humans speak English, Telugu or Hindi computer speak only binary(0 and 1).*

---

**Why does a computer understand only 0 and 1?**

- *Computers are built using electronic circuits.*
- *These circuits have only two electrical states: ON and OFF*
- *These are represented as: OFF-0 ON-1*
- *Therefore, computers naturally process information using binary digits.*

---

**Examples of Machine Language**

*A machine language instruction may look like this 1010101 10101 1010111. To us, this looks confusing. But the CPU can understand and execute it directly.*

---

**Example:** *Imagine you and your friend speak Telugu. You don't need a translator. Communication is direct. Similarly CPU - Machine language no compiler, interpreter or assembler is needed.*

---

**Characteristics of Machine Language**

- **Uses only binary numbers:** *Machine language contains only 0 and 1. No english words.*
- **Directly Understand by CPU:** *The CPU executes machine language directly. No translation is required.*
- **Very fast:** *Since there is no translation step, execution is extremely fast.*
- **Difficult for humans:** *Humans cannot easily read, write, remember, debug machine language programs.*
- **Machine dependent:** *Machine language is specific to a processor architecture. A program written for one processor may not work on another.*

---

**Advantages of Machine Language**

- **Faster Execution:** *No translation is needed.*
- **Direct CPU Execution:** *The CPU executes instructions immediately.*
- **Efficient Memory usage:** *Machine language programs use memory efficiently.*

**Disadvantages of Machine Language:**

- **Very difficult to learn:** *Writing binary instructions is extremely hard.*
- **Difficult to debug:** *Finding errors in binary is challenging.*
- **Difficult to modify:** *Changing a program is time-consuming.*
- **Machine Dependent:** *Programs cannot easily be moved between different processor architectures.*

---

**Machine Language vs High-Level Language**

| Machine Language          | High-Level Language                |
| ------------------------- | ---------------------------------- |
| Uses 0s and 1s            | Uses English-like syntax           |
| Easy for CPU              | Easy for humans                    |
| Very difficult for humans | Easy to learn                      |
| No translator required    | Needs compiler/interpreter         |
| Fast execution            | Slightly slower due to translation |

---

**Machine Language vs Assembly Language**

| Machine Language      | Assembly Language                       |
| --------------------- | --------------------------------------- |
| Binary (0s and 1s)    | Mnemonics like MOV, ADD                 |
| Directly executed     | Needs an assembler                      |
| Hard to read          | Easier than binary                      |
| Lowest-level language | Also low-level, but more human-readable |

---

### **Assembly Language**

**What is Assembly Language?**

- *Assembly Language is a low-level programming language that uses mnemonics(short english-like words) instead of binary numbers to represent machine instructions.*
- *It is easier for humans than machine language but still close to the hardware.*

---

**Why was Assembly language created?**

- *Imagine writing this 110011110 every instruction must be written in binary. Problems are very difficult to read, Easy to make mistakes, Difficult to debug, Difficult to remember. So programmers created Assembly language.*
- *Instead of writing 110011110 they write MOV A,B much easier.*

---

**What are Mnemonics?**

- *A Mnemonics is a short english-like word that represents a machine instruction.*

| Mnemonic | Meaning                     |
| -------- | --------------------------- |
| MOV      | Move data                   |
| ADD      | Add two values              |
| SUB      | Subtract                    |
| MUL      | Multiply                    |
| DIV      | Divide                      |
| JMP      | Jump to another instruction |
| CMP      | Compare values              |
| INC      | Increment                   |
| DEC      | Decrement                   |

---

**What is an Assembler?**

*An Assembler is a software program that converts Assembly Language into Machine Language.*

---

**Characteristics of Assembly Language**

- **Uses Mnemonics:** *Instead of binary 1010101010 Use MOV A,B*
- **Machine Dependent:** *Assembly code written for one processor may not work on another.*
- **Faster Execution:** *After being assembled into machine code, programs execute very quickly.*
- **More Hardware control:** *Assembly allows programmers to work closely with CPU registers and memory.*
- **Easier than Machine Language:** *Assembly is still difficult compared to Python, but much easier than binary.*

---

**Advantages of Assembly Language**

- **Easier than machine language:** *Uses readable mnemonics.*
- **Higher Performance:** *Program execute efficiently.*
- **Direct Hardware Access:** *Useful for system programming.*

**Disadvantages of Assembly Language**

- **Difficult to learn:** *Still much harder than Python or Java.*
- **Machine Dependent:** *Different processors use different Assembly Language.*
- **Difficult to Debug:** *Finding errors can be challenging.*
- **Longer Development time:** *Writing Assembly programs takes more time than writing python programs.*

---

**Applications**

*Assembly Language is used in:*
- *Operating Systems*
- *Device Drivers*
- *Embedded Systems*
- *Firmware*
- *Boot Loaders*
- *BIOS/UEFI*
- *Performance-critical routines*

---

**Assembly Language vs Machine Language**

| Machine Language           | Assembly Language            |
| -------------------------- | ---------------------------- |
| Uses 0s and 1s             | Uses mnemonics               |
| Directly understood by CPU | Needs an assembler           |
| Very difficult for humans  | Easier than machine language |
| Fastest execution          | Also fast after assembly     |

---

**Assembly Language vs High-Level Language**

| Assembly Language  | High-Level Language          |
| ------------------ | ---------------------------- |
| Low-Level          | High-Level                   |
| Uses mnemonics     | Uses English-like syntax     |
| Needs an assembler | Needs a compiler/interpreter |
| Machine dependent  | Usually portable             |
| Hard to learn      | Easy to learn                |

---

**NOTE:** 
- *High-Level Language → Human-friendly*
- *Assembly Language → Low-Level (uses mnemonics)*
- *Machine Language → Lowest-Level (uses binary)*

---

### **Procedural Programming**

**What is a Programming Paradigm?**

- *A Programming Paradigm is a style or method of writing programs.*
- *Think of it as a way of solving problems using programming.*
- *Just like there are different ways to travel:*
  - *Car*
  - *Bike*
  - *Train*
- *All reach the destination but in different ways.*
- *Similarly, there are different ways to write programs.*
- *These are called Programming Paradigms.*

---

**Common Programming Paradigms**

- *Procedural Programming*
- *Object-Oriented Programming(OOP)*
- *Functional Programming*
- *Logical Programming*

---

**What is Procedural Programming?**

- *Procedural Programming is a programming paradigm in which a program is written as a sequence of procedures(functions) that execute one after another.*
- *A procedure is simply a function or a set of instructions that performs a specific task.*

---

**Why is it called Procedure?**

*Because the program follows a procedure, meaning a sequence of steps.*

**Example:** *Making Tea*
- *Boil water*
- *Add Tea powder*
- *Add sugar*
- *Pour into cup*

*You must follow the steps in order.*

*Similarly, a procedural program executes instructions in sequence.*

**Example:** *Imagine an ATM. When you withdraw money, the ATM follows these steps.*
- *Insert Card*
- *Enter PIN*
- *Verify PIN*
- *Select Withdraw*
- *Enter amount*
- *Check Balance*
- *Dispense Cash*
- *Print receipt*

*Each step happens in order. This is procedural thinking.*

**Example:**
```python
def add(a,b):
  return a+b

result=add(10,20)
print(result)
```

*Execution order:*
- *Program starts*
- *add() function is called*
- *Addition is performed*
- *Result is returned*
- *Result is printed*

*The program follows a sequence.*

---

**Characteristics of Procedural Programming**

1. **Step-by-Step Execution:** *Instructions execute in order.*

**Example:**
```python                  
print("Step 1")              # Step 1
print("Step 2")              # Step 2
print("Step 3")              # Step 3
```

2. **Uses Functions(Procedures):** *Programs are divided into smaller functions.*

**Example:**
```python
def greet():                     # Welcome
  print("Welcome")

greet()
```

*Instead of writing the same code many times, we write it once inside a function.*

3. **Top-to-Bottom Flow:** *Execution normally starts at the top and moves downward.*

**Example:**
```python
a=10
b=20
print(a+b)                       # 30
```

4. **Reusability:** *Functions can be reused.*

**Example:** 
```python
def square(x):
  return x*x

print(square(5))               # 25
print(square(10))              # 100
print(square(20))              # 400
```

*One function is used multiple times.*

5. **Modularity:** *A large program is divided into smaller parts(functions).*

**Example:** 

*Instead of writing one huge problem:*
- *Login*
- *Payment*
- *Search*
- *Logout*

*We create separate functions:*
- *login()*
- *search()*
- *payment()*
- *logout()*

*This makes the program easier to understand and maintain.*

---

**Advantages of Procedural Programming**

- **Easy to learn:** *Suitable for beginners.*
- **Easy to read:** *Programs follow a clear sequence.*
- **Code Reusability:** *Functions can be called many times.*
- **Easier Debugging:** *Problems can often be found by checking individual functions.*
- **Better Organization:** *Programs are divided into smaller modules.*

**Disadvantages of Procedural Programming**

- **Difficult for very large projects:** *Managing thousands of functions becomes difficult.*
- **Data is less secure:** *Functions can access shared data more easily, making it harder to protect.*
- **Harder to maintain large applications:** *As programs grow, managing dependencies between functions becomes more complex.*

---

**Applications:**
*Procedural programming is commonly used in:*
- *Calculator programs*
- *Banking calculations*
- *Billing systems*
- *Automation scripts*
- *Mathematical programs*
- *Scientific calculations*

---

**Languages that support procedural programming**

**Examples:**
- *C*
- *Pascal*
- *BASIC*

*Python also supports procedural programming, even though it also supports Object-Oriented Programming and Functional Programming.*

---

**Procedural Programming vs Object-Oriented Programming**

| Procedural Programming          | Object-Oriented Programming           |
| ------------------------------- | ------------------------------------- |
| Focuses on functions            | Focuses on objects                    |
| Data and functions are separate | Data and methods are grouped together |
| Best for smaller programs       | Better for large applications         |
| Easier to learn                 | More concepts to learn                |

---

### **Object-Oriented Programming (OOP)**

**What is Object-Oriented Programming?**

- *Object-Oriented Programming (OOP) is a programming paradign in which a program is organized around objects instead of only functions.*
- *Objects contain both:*
  - *Data (Variables)*
  - *Behavior (Functions/Methods)*

---

**What is an Object?**

- *An Object is a real-world entity that has:*
  - *Properties (Data)*
  - *Behaviors (Actions)*

**Example:** 

*Car*

**Properties:**
- *Color*
- *Speed*
- *Brand*

**Behaviors:**
- *Start*
- *Stop*
- *Accelerate*
- *Brake*

*So, Car=Object*

---

**What is a Class?**

- *A Class is a blueprint or template used to create objects.*
- *Think about building houses. Architect creates one blueprint.*
- *From that blueprint:*
  - *House 1*
  - *House 2*
  - *House 3 are built*
- *The blueprint is Class*
- *The houses are Objects.*

---

**Why do we need OOP?**

*Imagine a college management system. Without OOP:*
- *student1_name*
- *student2_name*
- *student3_name*
- *student4_name*
- *teacher1_name*
- *teacher2_name*
- *course1*
- *course2*

*Everything becomes messy.*

*Using OOP:*
- *Student Object*
- *Teacher Object*
- *Course Object*
- *Library Object*

*Everything is organized.*

---

**Characteristics(Features) of OOP**

*There are four main pillars in OOP.*

1. **Encapsulation:** *Combining data and methods into one object.*

**Example:**
- *Bank Account*
- *Balance*
- *Deposit()*
- *Withdraw()*

2. **Inheritance:** *One class can inherit properties from another.*

**Example:** *Animal -> Dog -> German Shepherd*

*The child class gets features from the parent.*

3. **Polymorphism:** *One action can behave differently.*

**Example:** *Animal Sound()*
- *Dog -> Bark*
- *Cat -> Meow*

*Same method name but different behavior.*

4. **Abstraction:** *Showing only important details while hiding internal complexity.*

**Example:** *You drive a car.You use:*
- *Steering*
- *Brake*
- *Accelerator*

*You don't need to know how the engine works internally.*

---

**Advantages of OOP**

- **Code Reusability:** *Reuse existing classes.*
- **Better Organization:** *Large projects become easier to manage.*
- **Easier maintenance:** *Updating one class doesn't require changing the whole program.*
- **Better Security:** *Encapsulation protects data.*
- **Real-World Modeling:** *Objects represent real-world entities naturally.*

**Disadvantages of OOP**

- **Difficult for Beginners:** *Many new concepts.*
- **More memory usage:** *Objects require additional memory.*
- **More complex:** *Small programs don't always need OOP.*

---

**Applications**

*OOP is used in:*
- *Banking Systems*
- *Hospital Management Systems*
- *School Management Systems*
- *E-commerce Applications*
- *Mobile Apps*
- *Games*
- *Social Media Platforms*

---

### **Why Python?**

**What is Python?**

*Python is a high-level, interpreted, object-oriented, and general-purpose programming language known for its simple syntax, readability, and versatility. It is widely used in web development, automation, data analysis, artificial intelligence, machine learning, and many other fields.*

---

**Why was Python created?**

*In the late 1980s, many programming languages were powerful but difficult to learn.*

*For example:*

```c
#include<stdio.h>

int main()
{
    printf("Hello");
    return 0;
}
```

```python
print("Hello")
```

*Notice the difference. Python requires much less code. The goal was to create a language that is Easy to read, Easy to write, Easy to learn.*

---

**Who created Python?**

- *Python was created by **Guido van Rossum**.*
- *Development started in 1989.*
- *The first official version (Python 0.9.0) was released in 1991.*

---

**Why is it called Python?**

*It was actually named after the British comedy show **Monty Python's Flying Circus**.*

---

**Why is Python so popular?**

*There are many reasons.*

1. **Easy to Learn:** *Python looks similar to English. Even beginners can understand this.*

  **Example:** 
  ```python
  if age >= 18:
      print("Eligible")
  ```   

2. **Easy to Read:** *Python code is clean.*

  **Example:** 
  ```python
  total = price * quantity
  ```

3. **Easy to write:** *Less code, Less typing, Less chance of mistakes.*

  **Example:**
  ```c
  printf("Hello");
  ```

  ```python
  print("Hello")
  ```

4. **Huge Community:** *Millions of developers use Python.*
5. **Massive Library Support:** *Python has thousands of ready-made libraries.*

  **Example:** *NumPy, Pandas, Matplotlib, TensorFlow, Flask, Django, Requests. Instead of building everything from scartch you can use these libraries.*

6. **Cross Platform:** *The same python code run on Windows, Linux, macOS. Usually without modification.*
7. **Open Source:** *Python is free. Anyone can download and use it. No license fee.*
8. **Supports Multiple Programming Paradigms:** *Python Supports Procedural Programming, Object-oriented Programming, Functional Programming. That's one reason it's so flexible.*
9. **Used in many industries:** *Python is not limited to one field. It is used in Artificial Intelligence, Machine Learning, Data Science, Web Development, Automation, Cybersecurity, Cloud Computing, Game Development, Scripting, Scientific Computing.*

---

**Applications**

- **Data Analysis:** *Libraries like Pandas, NumPy.*
- **Artificial Intelligence:** *Libraries like TensorFlow, PyTorch*
- **Machine Learning:** *Libraries Scikit-learn, XGBoost.*
- **Web Development:** *Frameworks like Django, Flask, FastAPI.*
- **Automation:** *Examples are Rename files, Send emails, Read excel files, Generate reports.*
- **Cybersecurity:** *Used for Network scanning, Automation, Security testing.*

---

**Advantages of Python**
- *Easy to learn*
- *Easy to read*
- *Easy to write*
- *Huge community*
- *Large library support*
- *Open source*
- *Cross platform*
- *Supports multiple paradigms*
- *High productivity*

**Disadvantages of Python**
- **Slower than C/C++:** *Because python is interpreted.*
- **High memory usage:** *Uses more memory than some compiled languages.*
- **Not ideal for mobile app development:** *Languages like Kotlin(Android) and Swift(iOS) are more commonly used for native mobile apps.*

---

**Python vs Java**

| Python                       | Java                                     |
| ---------------------------- | ---------------------------------------- |
| Easy syntax                  | More verbose syntax                      |
| Faster development           | More boilerplate code                    |
| Interpreted                  | Compiled to bytecode and runs on the JVM |
| Popular in AI & Data Science | Popular in enterprise applications       |

---

**Python vs C++**

| Python              | C++                      |
| ------------------- | ------------------------ |
| Easy to learn       | More difficult to learn  |
| Slower execution    | Faster execution         |
| Less code           | More code                |
| Great for beginners | Greater hardware control |

---

## **Algorithm Fundamentals**

### **Algorithm**

**What is an Algorithm?**

*An Algorithm is a finite sequence of well-defined steps used to solve a specific problem or perform a particular task.*

---

**Why do we need an Algorithm?**

*An Algorithm acts like a blueprint before constructing a building.*

**Example:** *Login to Instagram*
1. *Open Instagram*
2. *Enter Username*
3. *Enter Password*
4. *Click Login*
5. *Verify Credentials*
6. *If correct -> Home Page*
7. *Otherwise -> Show error*

---

**Characteristics of a good algorithm**

*A good algorithm has five important characteristics.*
1. **Input:** *An Algorithm can take zero or more inputs.*
2. **Output:** *An Algorithm should produce at least one output.*
3. **Definiteness:** *Every step must be clear and unambiguous.*
4. **Finiteness:** *An algorithm must end after a finite number of steps.*
5. **Effectiveness:** *Each step should be simple and executable.*

---

**Why Algorithms are important?**

*Algorithms help us:*
- *Solve problems logically*
- *Reduce mistakes*
- *Write cleaner code*
- *Improve efficiency*
- *Make debugging easier*

---

**Advantages of Algorithms**

1. **Easy to understand:** *Logic is clear before coding.*
2. **Easy to debug:** *Mistakes can be found in the logic before writing code.*
3. **Language Independent:** *The same algorithm can be implemented as Python, Java, C++, JavaScript.*
4. **Better Problem Solving:** *Algorithms train you to think logically.*

**Disadvantages of Algorithms**

1. **Time Required:** *Designing a good algorithm takes planning.*
2. **Not suitable for very complex systems:** *Very large systems may require multiple algorithms working together.*

---

**Applications**

*Algorithms are used in:*
- *Google Search*
- *Instagram feed*
- *YouTube Recommendations*
- *GPS Navigation*
- *Banking Systems*
- *Online Shopping*
- *AI Systems*
- *Data Analysis*

*Every software application you use runs on algorithms.*

---

### **Characteristics of a good algorithm**

*A good algorithm should have 5 characteristics:*

1. **Input:** *An algorithm should accept zero or more inputs. Input means the data given to solve a problem.*

    **Example:** *ATM Machine*

    **Input:** *ATM Card, PIN, Amount. Without these inputs the ATM cannot continue.*

    *An algorithm may have zero inputs.*

    **Example:** *Display 'Welcome' no input is required. So, Zero or more inputs.*

2. **Output:** *Every algorithm should produce at least one output. Without an output, there is no result.*

    **Example:** *Calculator*

    **Input:** *15+25*

    **Output:** *40*

3. **Definiteness:** *Every step in the algorithm should be clear, precise and unambiguous. There should be only one meaning.*

    **Example:**
    - *Read Number A*
    - *Read Number B*
    - *Add A and B*
    - *Display the sum*

4. **Finiteness:** *An algorithm must terminate after a finite number of steps. It should not continue forever.*

    **Example:**
    - *Read two numbers*
    - *Add them*
    - *Display the answer*
    - *Stop*

5. **Effectiveness:** *Every step of an algorithm should be simple, practical, and executable. The computer should actually be able to perform it.*

    **Example:** *Compare 2 numbers. Computer can do this.*

---

### **Writing Algorithms**

**What is Writing an Algorithm?**

*Writing an algorithm means describing the logical steps required to solve a problem in a clear, finite, and well-defined sequence before implementing it in a programming language.*

---

**Rules for writing an Algorithm**

- **Rule-1:** *Start*

  *Every algorithm should begin with Start. This tells where execution begins.*

- **Rule-2:** *Input*

  *Reads the required inputs.*

  **Example:** *Read Number A. Read Number B.*

- **Rule-3:** *Processing*

  *Perform the required calculations.*

  **Example:** *Sum=A+B*

- **Rule-4:** *Output*

  *Display the result*

  **Example:** *Display Sum*

- **Rule-5:** *Stop*

  *Every algorithm should end with Stop.*

---

**General Structure of an Algorithm**

```txt
Start

↓

Input

↓

Process

↓

Output

↓

Stop
```

---

**Example:** *Addition of two numbers*

**Problem:** *Add two numbers.*

**Algorithm:**

- **Step-1:** *Start*
- **Step-2:** *Read number A*
- **Step-3:** *Read number B*
- **Step-4:** *Sum=A+B*
- **Step-5:** *Display Sum*
- **Step-6:** *Stop*

---

**Difference between Algorithm and Program**

| Algorithm            | Program                  |
| -------------------- | ------------------------ |
| Step-by-step logic   | Actual code              |
| Language independent | Language dependent       |
| Planning stage       | Implementation stage     |
| Easy to understand   | Executed by the computer |

---

### **Algorithm Design Basics**

**What is Algorithm Design?**

*Algorithm Design is the process of planning and organizing the steps required to solve a problem efficiently before writing the actual program.*

---

**The 4-Step Thinking Process**

**Step 1 - Understand the Problem:** *Read the question carefully. For example, find the largest of 2 numbers.*

**Step 2 - Identify the Input:** *What information do i need? For example, First Number Second Number.*

**Step 3 - Identify the Process:** *What should i do with the input? For example, Compare both numbers. Find the larger one.*

**Step 4 - Identify the Output:** *What should i display? For example, Largest number.*

---

## **Flowcharts**

### **Flowchart Basics**

**What is a Flowchart?**

*A Flowchart is a graphical representation of an algorithm that uses standard symbols to show the sequence of steps required to solve a problem.*

---

**Why do we use flowcharts?**

- *Instead of reading Start -> Read A -> Read B -> Add A and B -> Display Sum -> Stop.*
- *We can draw it as a diagram which is easier to understand.*
- **Example:** *Think about Google Maps. Instead of giving directions as a long paragraph, it shows you a visual route. A flowchart does the same thing it shows the logic visually.*

---

**Advantages**

- *Easy to understand*
- *Easy to communicate*
- *Helps find logical errors*
- *Makes programming easier*

**Disadvantages**

- *Time-consuming for very large problems*
- *Difficult to modify complex flowcharts*

---

**Difference between Algorithm vs Flowchart**

| Algorithm                 | Flowchart                      |
| ------------------------- | ------------------------------ |
| Written in text           | Drawn using symbols            |
| Step-by-step instructions | Visual representation of steps |
| Easier to write           | Easier to understand visually  |

---

### **Flowchart Symbols**

**What are Flowchart Symbols?**

- *Flowchart Symbols are standard shapes used to represent different operations in a flowchart.*
- *Think of them like Traffic Signs. Just as every traffic sign has a specific meaning, every flowchart symbol has a specific purpose.*

---

1. **Terminator (Start\Stop)**

    **Symbol:** *Oval shape*
    
    **Purpose:** *Used to represent Start, Stop(End). Every flowchart must begin with Start and must end with Stop.*

2. **Process Symbol**

    **Symbol:** *Rectangle*

    **Purpose:** *Represents Calculation, Assignment, Processing.*

    **Example:** *Sum=A+B, Area=Length × Breadth*

3. **Input/Output Symbol**

    **Symbol:** *Parallelogram*

    **Purpose:** *Used to Read input, Display output.*

    **Example for Input:** *Read A*

    **Example for Output:** *Display Sum*

4. **Decision Symbol**

    **Symbol:** *Diamond*

    **Purpose:** *Used for Yes/No, True/False, Conditions.*

    **Example:** 
    
    ```txt
    Is A > B?

    ↓

    Yes → Display A

    No → Display B
    ```

    *Whenever you use if, if-else you'll use the Decision Symbol.*

5. **Flow Line**

    **Symbol:**
    
    ```txt
    ↓

    or

    ─►
    ```

    **Purpose:** *Shows the direction of execution. It connects all symbols together.*

6. **Connector**

    **Symbol:** 

    ```txt
    ○
    ```

    **Purpose:** *Used to connect different parts of a flowchart. Useful when a flowchart becomes large. Instead of drawing a long arrow, we use connectors.*

---

| Symbol | Purpose        |
| ------ | -------------- |
| ⬭      | Start / Stop   |
| ▭      | Process        |
| ▱      | Input / Output |
| ◇      | Decision       |
| →      | Flow Line      |
| ○      | Connector      |

---

**Flowchart of Even or Odd**

```txt
              Start
                 │
                 ▼
          Read Number
                 │
                 ▼
        Number %2==0 ?
           ◇
        /       \
      Yes       No
       │         │
       ▼         ▼
 Print Even  Print Odd
       │         │
       └────┬────┘
            ▼
           Stop
```

---

### **Loops in Flowcharts**

**What is a Loop?**

*A Loop is a programming construct used to execute a block of instructions repeatedly until a given condition becomes false or a specified number of iterations is completed.*

---

**Why do we need Loops?**

*Without Loops:*

```python
print ('Hello')
print ('Hello')
print ('Hello')
print ('Hello')
print ('Hello')
```

*With Loops Repeat 5 times print('Hello') less work and cleaner logic.*

---

**Loop in a flowchart**

*A Loop is created using:*
- *Decision Symbol (Diamond) to check the condition.*
- *Flow Line (Arrow) to go back and repeat the process.*

*If the condition is True, repeat. If False, stop.*

---

**Advantages of Loops**

- *Reduces repeated work*
- *Makes algorithms shorter*
- *Easier to maintain*
- *Saves time*

**Disadvantages of Loops**

- *Wrong conditions can create infinite loops.*
- *Can become difficult to understand if overused.*

---

**What is an Infinite Loop?**

*An Infinite Loop is a loop that never stops because its condition never becomes false.*

---

## **Pseudocode**

**What is Pseudocode?**

*Pseudocode is a language-independent representation of an algorithm written in simple English-like statements to describe the program logic without using the syntax of a specific programming language.*

---

**Why do we need Pseudocode?**

*Imagine your team has:*
- *Python Developer*
- *Java Developer*
- *C++ Developer*

*Instead of writing logic in Python, you write it in pseudocode. Everyone understands it. Then each developer converts it into their own programming language.*

---

**Characteristics of Pseudocode**

*A good pseudocode should be:*
- *Simple*
- *Easy to read*
- *Language independent*
- *Focused on logic*
- *Easy to convert into code*

---

**Common Keywords**

*BEGIN, END, INPUT, OUTPUT, IF, ELSE, WHILE, FOR, PRINT.*

*These are not tied to any one programming language.*

---

**Example:** 

**Add two numbers**

```pseudocode
BEGIN
INPUT A 
INPUT B
SUM=A+B
PRINT SUM
END
```

**Even or Odd**

```pseudocode
BEGIN
INPUT N
IF N IS DIVISIBLE BY 2
PRINT "EVEN"
ELSE
PRINT "ODD"
END
```

**Largest Number**

```pseudocode
BEGIN
INPUT A
INPUT B
IF A>B 
PRINT "A IS LARGEST NUMBER"
ELSE 
PRINT "B IS LARGEST NUMBER"
END
```

---

**Algorithm vs Flowchart vs Pseudocode**

| Algorithm            | Flowchart            | Pseudocode                 |
| -------------------- | -------------------- | -------------------------- |
| Written steps        | Visual diagram       | English-like program logic |
| Text                 | Symbols              | Simple statements          |
| Easy to write        | Easy to visualize    | Easy to convert into code  |
| Language independent | Language independent | Language independent       |

---

**Advantages**

- *Easy to understand*
- *Language independent*
- *Easy to convert into code*
- *Improves logical thinking*
- *Helps before coding*

**Disadvantages**

- *No fixed standard*
- *Cannot be executed by a computer*
- *Different people may write it differently*

---

### **Converting Pseudocode to Python**

*Converting pseudocode to python is the process of translating English-like program logic into valid Python syntax.*

---

**Conversion Rules**

| Pseudocode      | Python                |
| --------------- | --------------------- |
| BEGIN           | (No keyword required) |
| END             | (No keyword required) |
| Read            | `input()`             |
| Print / Display | `print()`             |
| IF              | `if`                  |
| ELSE            | `else`                |
| WHILE           | `while`               |
| FOR             | `for`                 |
| Calculate       | Use Python operators  |

---

**Example:** *Add 2 numbers*

```pseudocode
BEGIN
INPUT A 
INPUT B
SUM=A+B
PRINT SUM
END
```

```python
a=int(input("Enter first number:"))
b=int(input("Enter second number:"))

sum=a+b

print(sum)
```

---

# **Python Fundamentals**

## **Introduction to Python**

### **What is Python?**

*Python is a high-level, interpreted, object-oriented, and general-purpose programming language known for its simple syntax, readability, and versatility. It is widely used in web development, automation, data analysis, artificial intelligence, machine learning and many other fields.*

---

### **History of Python**

**Who created Python?**

*Python was created by **Guido van Rossum**, a dutch programmer. He is known as the Father of Python.*

---

**Development Timeline**

- *1989 → Guido van Rossum started developing Python at CWI (Centrum Wiskunde & Informatica) in Amsterdam, Netherlands.*
- *February 1991 → The first public version, Python 0.9.0, was officially released.*
- *2000 → Python 2.0 was released.*
- *2008 → Python 3.0 was released.*
- *Present → Python 3.x is actively developed and widely used.*

---

**Why was Python Created?**

*Python was created to provide a programming language that is:*
- *Simple*
- *Readable*
- *Easy to learn*
- *Easy to maintain*
- *More productive for developers*

---

**Why is it called Python?**

*Python was named after the British comedy television show **Monty Python's Flying circus**.*

---

**Python Software Foundation (PSF)**

- *Python is managed and maintained by the Python Software Foundation (PSF).*
- *The PSF is a non-profit organization that supports the development, protection, and promotion of Python.*
- *Official website www.pythom.org*

---

### **Features of Python**

**What are Features?**

- *Features are the characteristics or qualities of a programming language that make it useful and explain why developers choose it.*
- *Python provides many useful features that make it one of the most popular programming languages.*

---

1. **Simple and Easy to Learn**

    *Python is one of the simplest programming languages because:*
    - *It has simple and readable syntax.*
    - *It requires fewer lines of code.*
    - *It has a rich standard library that provides many built-in modules and functions.*
    - **Example:**
      ```python
      print("Hello, World!")
      ```

      ```C
      #include <stdio.h>
      int main()
      {
      printf("Hello, World!");
      return 0;
      }
      ```
    - *Python code is shorter and easier to understand.*

2. **Free and Open Source**

    **Freeware:** *Python can be downloaded and used free of cost.*

    **Open Source:** *Python's source code is publicly available.*

    *Anyone can View the source code, modify it, improve it, distribute it.*

3. **Platform Independent (Cross-Platform)**

    - *A Python program written on one operating system can also run on other operating systems with the appropriate python installation.*
    - **Examples:** *Windows, Linux, macOS. This is called Platform Independence.*

4. **Dynamically Typed**

    - *In Python, you do not need to declare the data type of a variable.*
    - *Python automatically determines the data type based on the value assigned.*
    - **Example:**
      ```python
        age=10
        name="Saranya" 
      ```

5. **Interpreted Language**

    - *Python is generally known as an Interpreted programming language.*
    - *Python programs are executed using the Python Interpreter.*
 
6. **High-Level Language**

    - *Python is a high-level programming language.*
    - *It uses English-like syntax, making it easier for humans to read and write than low-level languages such as Machine Language or Assembly Language.*

7. **Robust**

    - *Python is a robust programming language because it provides mechanisms to handle runtime errors effectively.*
    - *This helps developers build reliable applications.*
 
8. **Supports Multiple Programming Paradigms**

    *Python supports multiple programming styles, including:*
    - *Procedural Programming*
    - *Object-Oriented Programming (OOP)*
    - *Functional Programming*

    *This makes Python flexible for different types of applications.*

9.  **Extensible**

    - *Python is an extensible programming language.*
    - *It can be extended using code written in other languages such as:*
      - *C*
      - *C++*
      - *Java* 
    - *This helps improve performances when needed.*

10. **Embeddedable**

    - *Python is an embeddable programming language.*
    - *Python code can be embedded inside applications written in other programming languages.*
    - *This allows other software to use Python's capabilities.*

11. **Rich Standard Library & Third-Party Library Support**

    - *Python provides a rich standard library with many built-in modules.*
    - **Examples:** *math, random, datetime, os*
    - *Python also has thousands of third-party libraries that can be installed when needed.*
    - **Examples:** *NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, TensorFlow.*
    - *These libraries reduce development time and make Python powerful for many domains.*

---

### **Applications of Python**

**What are Applications of Python?**

*Applications of Python are the different fields or domains where Python is used to solve real-world problems.*

1. **Web Development:** *Python is widely used to build Websites, Web Applications, REST APIs.*
  
    **Examples:**
    - *Instagram (uses python in parts of its backend)*
    - *Spotify (uses python for backend services and data analysis)*
    - *YouTube (uses python for various backend components)*

    **Popular Frameworks:** *Django, Flask, FastAPI*

2. **Data Analysis:** *Python is one of the most popular languages for analyzing data. It is used to Clean data, Analyze data, Generate reports, Find patterns.*

    **Libraries:** *Pandas, NumPy.*

    **Example:** *A company analyzes sales data to identify its best-selling products.*

3. **Data Science:** *Data Science involves extracting meaningful insights from data. Python helps in Data Collection, Data Cleaning, Data Visualization, Statistical Analysis.*

    **Libraries:** *Pandas, NumPy, SciPy*

4. **Artificial Intelligence (AI):** *Python is widely used to build intelligent systems that can perform tasks requiring human intelligence.*

    **Examples:** *Chatbots, Voice Assistants, Recommendation Systems*

    **Real-world Example:** *ChatGPT is an AI application*

5. **Machine Learning (ML):** *Machine Learning enables computers to learn from data without being explicitly programmed.*

    **Examples:** *Spam Detection, Movie Recommendations, Face Recognition*

    **Libraries:** *Scikit-learn, TensorFlow, PyTorch*

6. **Automation:** *Python is excellent for automating repetitive tasks.*

    **Examples:** *Renaming files, Sending emails, Reading Excel files, Web scraping.*

    **Real-world Examples:** *Automatically generating monthly reports instead of doing them manually.*

7. **Cybersecurity:** *Python is used for Security Testing, Network Analysis, Password Auditing, Ethical Hacking.*


8. **Desktop GUI Applications:** *Python can be used to create desktop software.*

    **Examples:** *Calculator, Text Editor, Inventory Management System*

    **Libraries:** *Tkinter, PyQT*

9.  **Game Development:** *Python can be used to develop simple games.*

    **Library:** *Pygame*

10. **Internet of Things (IoT):** *Python is used in Raspberry Pi, Smart Home Devices, Embedded Systems.*


11. **Scientific Computing:** *Scientists and researchers use python for Mathematical calculations, Simulations, Research.*

    **Libraries:** *NumPy, SciPy*

12. **Cloud Computing:** *Python is used in cloud services and automation.*

    **Examples:** *AWS Automation, Azure Automation, Google Cloud.*

---

### **Python Versions**

**What is a Version?**

*A Version is a numbered release of software used to identify different releases, updates, improvements, bug fixes, and new features.*

---

**Major Python Versions:** *Python has 3 major versions:*

1. **Python 1.x**

   - *First major version of Python*
   - *Released in 1994*
   - *Outdated and no longer used for modern development*

2. **Python 2.x**

   - *Released in 2000*
   - *Widely used for many years*
   - *Official support ended on January 1, 2020*
   - *Not recommended for new projects*
    
3. **Python 3.x**

   - *Released in 2008*
   - *Current major version*
   - *Actively maintained*
   - *Recommended for all new projects*
   - *Used in Web Development, Data Analysis, AI, Machine Learning, Automation, and many other fields.*

---

**What is Backward Compatibility?**

*Backward Compatibility means a newer version of software can run or support programs developed for an older version.*

**Python and Backward Compatibility**

- *Python 3 is not fully backward compatible with Python 2.*
- *Some programs written in Python 2 need modifications before they can run in Python 3.*

---

**Which Python Version should you learn?**

*Python 3.x because it is Current Version, Actively maintained, More secure, Better performance, Recommended for all new projects.*

---

**How to check Python Version?**

*Open Command Prompt or Terminal and type "python --version"*

---

### **Python Distributions**


**Python Distribution:** *A Python Distribution is a customized version of python created to serve a specific need. Because Python is open source, developers can modify it and create their own distributions.*

1. **CPython:**
   - *CPython is the official and most widely used implementation of Python.*
   - *It is developed using the C programming language.*
   - *When you download Python from python.org you are usually downloading CPython.* 
   - **Used for:** *General Python Development*
     
2. **Jython:** 
   - *Jython is Python implemented on the Java platform.*
   - *It allows Python programs to work with Java libraries.*
   - *It runs on the Java Virtual Machine (JVM)*
   - **Used for:** *Java applications*
    
3. **IronPython:** 
   - *IronPython is Python implemented for the .NET framework.*
   - *It allows Python programs to work with C#, .NET libraries.* 
   - **Used for:** *.NET applications*
     
4. **MicroPython:** 
    - *MicroPython is a lightweight implementation of Python designed for Microcontrollers, Embedded Systems, IoT devices.* 
  
   **Why was it created?**

   - *Normal Python requires more memory, more processing power.*
   - *Small devices like Sensors, Smart Watches, IoT Boards have limited resources. So, MicroPython was created.*
   
5. **Anaconda:** 
   - *Anaconda is a Python distribution specially designed for Data Analysis, Data Science, Machine Learning, Artificial Intelligence.*
   - *It comes with many pre-installed libraries such as NumPy, Pandas, Matplotlib, Scikit-learn, Jupyter Notebook.*
   - *This saves time because you don't have to install them separately.*

6. **Stackless Python:** 
   - *Stackless Python is a modified version of Python*
   - *It is designed for Concurrency, Parallel Tasks, High Performance Applications.*
  
--- 

### **Python Execution Environment**

**What is Python Execution Environment?**

*Python Execution Environment is the complete setup that executes Python programs. It includes the Python Interpreter, memory management, libraries, operating system support, and other components required to run Python code.*

---

**Why do we need a Python Execution Environment?**

*Without an execution environment:*
- *Python code cannot run*
- *The computer cannot understand Python syntax*
- *There is no way to execute Python programs*

*The execution environment acts as a bridge between your Python program and the computer.*

---

**Main Components of Python Execution Environment**

*The execution environment consists of several components. They include:*
- *Python Interpreter*
- *Compiler (Bytecode Compiler)*
- *Bytecode*
- *Python Virtual Machine (PVM)*
- *Memory Management*
- *Libraries*
- *Operating System Support*

---

**Advantages of Python Execution Environment**

- *Executes Python programs*
- *Manages memory automatically*
- *Supports Python libraries*
- *Provides a platform to run Python applications*

---

### **Python Compiler**

**What is the Python Compiler?**

*A Python Compiler is a component of the Python execution system that converts Python source code (.py) into Bytecode (.pyc) before execution.*

---

**What does the Python Compiler do?**

*The Python Compiler has three main jobs.*

1. **Reads the Python Source Code:** *It reads the .py file written by the programmer.*
2. **Checks for Syntax Errors:** *It checks whether the program follows Python's grammar rules.*
3. **Converts the Code into Bytecode:** *If there are no syntax errors, the compiler converts the source code into Bytecode. This Bytecode is not executed yet. It is simply prepared for the next stage.*

---

**Compiler Flow**

*Python Source Code (.py) → Python Compiler → Bytecode (.pyc)*

---

**Advantages of the Python Compiler**

- *Converts Python Source Code into Bytecode*
- *Detects syntax errors before execution*
- *Prepares the program for execution*
- *Improves efficiency because compiled Bytecode can be reused in some cases*

---

### **Python Interpreter**

**What is a Python Interpreter?**

*A Python Interpreter is a software program that executes the compiled Bytecode using the Python Virtual Machine (PVM) and produces the program's output.*

---

**Why does the Python Interpreter do?**

*The interpreter has three main jobs.*

1. **Reads the Bytecode:** *It takes the Bytecode created by the compiler.*
2. **Executes the Bytecode:** *It processes the Bytecode instruction by instruction.*
3. **Produces the Output:** *Display the output*

---

**Interpreter Flow**

*Bytecode (.pyc) → Python Interpreter (PVM) → Output*

---

**Advantages of the Python Interpreter**

- *Executes the program*
- *Makes Python programs portable across operating systems*
- *Reports runtime errors when they occur*
- *Supports interactive execution (Python Shell/REPL)*

**Disadvantages of the Python Interpreter**

- *Execution is generally slower than fully compiled languages because Bytecode is interpreted by the PVM.*
- *Runtime errors may only appear when the relevant code is executed.*

---

**Compiler vs Interpreter**

| Compiler                           | Interpreter             |
| ---------------------------------- | ----------------------- |
| Reads Python source code           | Reads Bytecode          |
| Converts source code into Bytecode | Executes Bytecode       |
| Produces `.pyc` files              | Produces program output |
| Works before execution             | Works during execution  |

---

### **Bytecode**

**What is Bytecode?**

- *Bytecode is an intermediate code generated by the Python compiler from Python source code before execution.*
- *It is not human-readable like Python source code and not directly understandable by the CPU like machine code.*
- *It is executed by the Python Virtual Machine (PVM).*

---

**Important Characteristics of Bytecode**

- *Generated by the Python Compiler*
- *Stored as .pyc files (often inside the __pycache__ folder)*
- *Executed by the Python Virtual Machine (PVM)*
- *Platform-independent*

---

**Advantages of Bytecode**

- *Speeds up execution by allowing Python to reuse compiled code in some situations*
- *Makes Python portable across platforms*
- *Separates compilation from execution*

**Disadvantages of Bytecode**

- *Bytecode is not machine code, so it still needs the PVM to executes it*
- *It cannot be run directly by the CPU*

---

### **Python Virtual Machine (PVM)**

**What is Python Virtual Machine (PVM)?**

*The Python Virtual Machine (PVM) is the runtime engine of Python that executes the Bytecode generated by the Python Compiler and produces the program's output.*

---

**What does the PVM do?**

*The PVM has three main jobs*

1. **Reads the Bytecode:** *The PVM takes the Bytecode generated by the compiler.*
2. **Executes the Bytecode:** *It processes the Bytecode instruction by instruction.*
3. **Produces the Output:** *Display the Output*

---

**Characteristics of Bytecode**

- *Executes Bytecode*
- *Acts as the runtime engine of Python*
- *Produces the program's output*
- *Makes Python portable because different operating systems have their own PVM implementation.*

---

**Advantages of PVM**

- *Execute python programs*
- *Makes Python platform-independent*
- *Handles bytecode execution efficiently*
- *Provides automatic memory management*

**Disadvantages of PVM**

- *Since Bytecode is interpreted by the PVM, Python is generally slower than languages like C or C++ that compile directly to machine code.*

---

**Complete Execution Process**

*You write Python Source Code (.py) → Compiler (Check Syntax + Convert) → Bytecode (.pyc) → Python Virtual Machine (Executes Bytecode) → Machine Instructions → Output*

---

### **Python Runtime Environment**

**What is Python Runtime Environment?**

*The Python Runtime Environment is the environment in which a Python program executes. It provides the Python Virtual Machine (PVM), memory management, standard libraries, built-in functions, and operating system support required to run Python program.*

---

**Why do we need a Runtime Environment?**

*Suppose you execute:*

```python
 a=10
 b=20
 print(a+b)
```

*While the program is running, Python needs:*
- *Memory to store a and b*
- *Built-in function print()*
- *The PVM to execute the Bytecode*
- *Operating System services to display the output*

*All these are provided by the Runtime Environment. Without it, the program cannot run sucessfully.*

---

**Components of Python Runtime Environment**

*The Runtime Environment consists of several components.*

1. **Python Virtual Machine (PVM):** *Executes the Bytecode*
2. **Memory Management:** *Stores Variables, Objects, Functions.*
3. **Built-in Functions:** *Functions already available in Python like `print()`, `len()`, `input()`, `type()`*
4. **Standard Libraries:** *Python provides many built-in modules like **math, random, datetime, os**.*
5. **Operating System Support:** *The Runtime Environment communicates with the operating system like Writing files, Reading files, Displaying output, Taking keyboard input.*

---

### **Interactive Mode vs Script Mode**

**What is Interactive Mode?**

*Interactive Mode is a way of executing Python code line by line, where each statement is executed immediately after it is entered.*

---

**Why is it called Interactive Mode?**

*Because the user and Python interact directly.*

*You type a statement → Python executes it immediately → Python displays the result.*

  **Example:**

  ```python
  >>> 5+3
  8

  >>> print("Hey")
  Hey
  ```

*You don't need to save the program.*

---

**Advantages of Interactive Mode**

- *Immediate Output*
- *Good for beginners*
- *Useful for testing small pieces of code*
- *No need to create a .py file*

**Disadvantages of Interactive Mode**

- *Code is not saved automatically*
- *Not suitable for large programs*
- *Difficult to manage long projects*

---

**What is Script Mode?**

*Script Mode is a way of writing Python programs in a .py file, saving them, and executing the entire program.*

---

**How does Script Mode work?**

**Example:** *Create a file named **hello.py** and Write*

```python
print("Hey")
print("Hi")
print("Haloooo")
```

*Save the file. Run the file.*

**Output:**
```txt
Hey
Hi
Haloooo
```

**Advantages of Script Mode**

- *Code is saved permanently*
- *Suitable for large applications*
- *Easy to edit and reuse*
- *Better for projects and software development*

**Disadvantages of Script Mode**

- *You need to save the file before running it*
- *Slightly slower for quick experiments compared to Interactive mode*

---

**Interactive Mode vs Script Mode**

| Interactive Mode                | Script Mode                           |
| ------------------------------- | ------------------------------------- |
| Executes one line at a time     | Executes the entire file              |
| No need to save code            | Code is saved in a `.py` file         |
| Immediate output                | Output after running the file         |
| Good for learning and testing   | Good for real applications            |
| Not suitable for large programs | Suitable for small and large programs |

---

### **Python Shell (REPL)**

**What is Python Shell?**

*Python Shell is an interactive environment where Python statements are entered and executed immediately. It provides a command-line interface to interact with the Python Interpreter.*

---

**Why is it called REPL?**

*REPL stands for*
- **R → Read:** *The Python Shell reads the statement you type.*
  
  **Example:** 
   ```python
   >>> 10+10
   ```
  *The Shell read 10+10*

- **E → Evaluate:** *Python evaluates (processes) the expression*

   *10+10 → 20*

- **P → Print:** *The result is displayed on the screen*
 
   *30*

- **L → Loop:** *Python waits for the next command*

   ```python
   >>>
   ```

---

**Are Interactive Mode and Python Shell the same?**

*Almost but*

**Interactive Mode:** *It is a way of working. It means executing code line by line.*

**Python Shell:** *It is the program/interface that provides Interactive Mode.*

*So*
- *Python Shell = Tool/Interface*
- *Interactive Mode = Method of execution*

---

### **Installing Python and IDLE**

**What is Python Installation?**

*Python Installation is the process of setting up the Python Interpreter and related tools on a computer so that Python programs can be written and executed.*

---

**Steps to Install Python (Windows)**

**Step-1:** *Open your Browser. Go to the official website https://www.python.org*

**Step-2:** *Click Downloads. Python automatically detects your operating system and suggests the latest stable version.*

**Step-3:** *Open the downloaded installer. You will see a setup window.*

**Step-4:** *Check the checkbox ☑ Add Python to PATH*

**Why is this important?**

*PATH is an environment variable. When Python is added to PATH, you can run Python from Command Prompt or Terminal.*

```txt
Python
```

or

```txt
python --version
```

*If you don't check this option, Windows won't recognize the Python command unless you manually configure the PATH later*

**Step-5:** *Click Install now. Python and IDLE will be installed*

**Step-6:** *Wait until installation finishes. You should see **Setup was successful**.*

**Step-7:** *Click Close. Installation is complete.*

---

**How to check whether Python is Installed?**

*Open Command Prompt. Type **python --version***

**Example output:** *Python 3.13.5 or on some systems python3 --version*

---

**What gets Installed?**

*When you install Python, you get*
- *Python Interpreter*
- *Python Standard Library*
- *IDLE*
- *pip (Python Package Installer)*

---

### **IDLE**

**What is IDLE?**

- *IDLE (Integrated Development and Learning Environment) is the default IDE that comes with Python and provides both the Python Shell and a Script Editor.*
- *It helps you Write Python code, Run Python programs, Use the Python Shell, Save Python files.*

---

**Two parts of IDLE**

1. **Python Shell:** *Used for Interactive Mode.*
2. **Script Editor:** *Create a new file*

---

**Features of IDLE**

- *Python Shell (Interactive Mode)*
- *Script Editor*
- *Syntax Highlighting*
- *Auto Indentation*
- *Error Messages*
- *Basic Debugging*

---

**Popular Python IDEs**

1. *IDLE*
2. *VS Code*
3. *PyCharm*
4. *Jupyter Notebook*

| IDE              | Best For                                  | 
| ---------------- | ----------------------------------------- | 
| IDLE             | Learning Python                           | 
| VS Code          | General Python & Professional Development | 
| PyCharm          | Large Python Projects                     |
| Jupyter Notebook | Data Science & ML                         | 

---

## **Python Program Structure**

### **Keywords**

#### **Keywords (Reserved Words)**

**What are Keywords?**

*Keywords are reserved words in Python with predefined meanings. They are part of Python's syntax and cannot be used as identifiers such as Variable Names, Function Names or Class Names.*

---

**Examples of Keywords**

*Some commonly used Python Keywords are*

```txt
if  else  elif  for  while  break  continue  pass  def
return  class  import  try  except  finally  raise  True
False  None  and  or  not  in  is  with  yield  lambda
global  nonlocal
```

---

**Characteristics of Keywords**

*Keywords have the following properties*

1. **Reserved by Python:** *They are reserved for specific purposes*

    **Example:** *```if``` always represents a conditional statement.*

2. **Have a Fixed Meaning:** *Their meaning cannot be changed.*

    **Example:** *```while``` will always represent a loop.*

3. **Cannot be Used as Identifiers:** *This means they cannot be used as Variable names, Function names, Class names, Module Names.*

    **Example:** ```class=10```, ```return=5```

4. **Case-Sensitive:** *Keywords must be written exactly as defined.*

    **Example:** *```if``` is a Keyword but ```If``` is not a keyword. Similarly, ```True``` is a Keyword ```true``` is not.*

---

#### **Keywords (Keyword Module)**

**What is a Module?**

- *A Module is a Python file that contains predefined functions, variables, or classes that can be used in your program.*
- *Python provides many built-in modules*
- **Examples:** 
  ```txt
  math  random  datetime
  os keyword
  ```

---

**What is the Keyword Module?**

*The Keyword Module is a built-in Python module used to access the list of Python Keywords and check whether a given word is a Keyword.*

---

**Importing the Module**

*Before using any module, we import it.*

```python
import keyword
```

*Here, import → Keyword, keyword → Module Name*

---

**keyword.kwlist**

*kwlist is a predefined list that contains all Python Keywords.*

**Syntax**

```python
import keyword
print(keyword.kwlist)
```

**Output:**

```python
['False', 'None', 'True', 'and', 'as', 'assert',
'async', 'await', 'break', 'class', 'continue',
'def', 'del', 'elif', 'else', 'except', 'finally',
'for', 'from', 'global', 'if', 'import', 'in',
'is', 'lambda', 'nonlocal', 'not', 'or', 'pass',
'raise', 'return', 'try', 'while', 'with', 'yield',
'match', 'case']
```

**keyword.iskeyword()**

- *The iskeyword() function checks whether a word is Python Keyword.*
- *It returns True → if it is a keyword, False → if it is not.*

**Syntax**

```python
keyword.iskeyword(word)
```

**Example:**

```python
import keyword
print(keyword.iskeyword("if"))      # True
```

---

### **Identifiers**

**What is an Identifier?**

*An identifier is a user-defined name used to identify program elements such as variables, functions, classes, modules, and objects.*

**Examples of Identifiers**

**Variable:** *Identifier age*

```python
age = 21              
```

**Function:** *Identifier greet*

```python
def greet():
  print("Hello")
```

**Class:** *Identifier Student*

```python
class Student:
  pass
```

**Module:** *Identifier math*

```python
import math
```

---

**Rules for Naming Identifiers**

**Rule-1:** *Must begin with a Letter or Underscore*

  **Examples:** 

  ```python
  age="Saranya"
  _age="Saranya"
  ```

**Rule-2:** *Can contain Letters, Digits and Underscores*

  **Examples:**

  ```python
  student1

  roll_no

  marks2026

  total_marks
  ```

**Rule-3:** *Cannot contain Spaces*

  **Examples:**

  ```python
  student name="Ram"                # Wrong
  student_name="Ram"                # Correct
  ```

**Rule-4:** *Cannot contain Special Characters*

  **Invalid**

  ```python
  salary@

  student#

  price$
  ```

  *Allowed Special Character ```_``` Only the underscore ``` _``` is allowed.*

**Rule-5:** *Cannot be a Keyword*

  ```python
  if=100
  ```

**Rule-6:** *Identifiers are Case-Sensitive*

  *These are all different Age, AGE, age. Python treats them as three different identifiers.*

---

**Naming Conventions**

- *Even though these names are valid a, x, abc, temp123. These are not descriptive.*
- *Instead, use meaningful names student_name, employee_salary, total_marks*

---

**Python Naming Styles**

**Snake Case:** *Python follows snake_case for Variables and Functions.*

  ```python
  student_name

  total_marks

  calculate_salary
  ```

**Pascal Case:** *Usually used for class names*

  ```python
  Student

  BankAccount

  EmployeeDetails
  ```

**UPPER_CASE:** *Usually used for constants (By convention)*

  ```python
  PI

  MAX_SIZE

  DEFAULT_TIMEOUT
  ```

---

**Keywords vs Identifiers**

| Keywords                       | Identifiers                                         |
| ------------------------------ | --------------------------------------------------- |
| Reserved by Python             | Created by programmer                               |
| Fixed meaning                  | User-defined names                                  |
| Cannot be changed              | Can be chosen freely (following rules)              |
| Examples: `if`, `for`, `while` | Examples: `age`, `student_name`, `calculate_salary` |

---

### **Variables**

*A Variable is an identifier that refers to a value in memory. It is used to store and manipulate data during program execution.*

---

**Creating a Variable**

*Creating a Variable in python is simple.*

**Syntax:**

```python
variable_name=value
```

---

**How does Variable Assignment Work?**

**Example:** *age=22*

*Python performs these steps*
1. *Creates the integer object 22*
2. *Creates the variable age*
3. *Associates (binds) age with the value 22*

---

**Using Variables**

```python
name="Saranya"
print(name)           # Saranya
```

---

**Changing a Variable (Reassignment)**

*Variables can be assigned a new value.*

**Example:**

```python
marks=98

marks=100

print(marks)            100
```

*The previous value is replaced by the new assignment.*

---

**Variables can store different types of data**

```python
name="Saranya"

age=10

height=6.2

is_employed=False
```

*Here, name → String, age → Integer, height → Float, is_employed → Boolean.*

---

#### **Variable Creation**

**What is Variable Creation?**

*Variable Creation is the process of creating a variable name and binding it to an object (value) in memory using the assignment operator (=).*

---

**Method-1:** *Single Variable Assignment*

**Syntax**

```python
variable=value
```

**Example:**

```python
name="Saranya"

age=10
```

**Method-2:** *Multiple Variable Assignment*

*You can assign values to multiple variables in one statement.*

**Syntax**

```python
variable1, variable2, variable3=value1, value2, value3
```

**Example:**

```python
name, age, city="Saranya", 10, "Elr"
```


**Number of Variables must match**

```python
a,b=10,20
```

**Method-3:** *Chained Assignment*

*Sometimes you want multiple variables to have the same value.*

**Syntax**

```python
a=b=c=value
```

**Example:**

```python
a=b=c=100
```

**Method-4:** *Sequence Unpacking*

*Python can unpack values from a list or tuple.*

**Example with list:**

```python
numbers=[10,20,30]

a,b,c=numbers

print(a)              # 10
print(b)              # 20
print(c)              # 30
```

**Example with Tuple:**

```python
student=("Saran",10)

name,age=student

print(name)           # Saran
print(age)            # 10
```

**Method-5:** *Extended Unpacking*

*Sometimes you don't know how many values remain. Use ```*```*

**Example:**

```python
a, *b=[10,20,30,40]

print(a)              # 10
print(b)              # [20,30,40]
```

```python
a,*b,c=[1,2,3,4,5]

print(a)              # 1
print(b)              # [2,3,4]
print(c)              # 5
```

**Method-6:** *Assigning Expressions*

*Variables can store the result of an expression.*

```python
x=10+20

print(x)              # 30
```

---

#### **Variable Swapping**

*Variable Swapping is the process of exchanging the values of two variables.*

**Syntax:** *Python provides two ways to swap variables*

**Method-1:** *Using a Temporary Variable*
  ```python
  temp=a
  a=b
  b=temp
  ```

**Method-2:** *Pythonic Way*
  ```python
  a=b=b,a
  ```

---

#### **Dynamic Typing**

*Dynamic Typing is a feature of Python in which the data type of a variable is determined automatically based on the value assigned to it.*

**Example:**
  ```python
  age=21

  print(type(age))              # <class 'int'>
  ```
  
---

### **Comments**

*Comments are non-executable statements used to explain the code, improve readability, and make programs easier to understand.*

**Example:**
  ```python
  # Store student age
  age=20

  print(age)              # 20
  ```

---

**Types of Comments in Python**

*Python supports 3 ways to write comments*
1. *Single-Line Comments*
2. *Multi-Line Comments*
3. *Docstrings*



#### **Single-Line Comment**

**Single-Line Comment:** *A Single-Line Comment is a comment that begins with the ```#``` symbol and continues until the end of the line.*

  ```python
  # This is Single-Line comment
  print("Hello")
  ```

#### **Multi-Line Comment**

**Multi-line Comment:** *A Multi-Line Comment is a comment that is used to write comments than span multiple lines to explain larger sections of code.*

  ```python
  # This is Multi-Line
  # Comment
  ```

*Python does not officially support multi-line comments. The recommended way is to use multiple ```#``` symbols. Triple quotes are primarily meant for docstrings, not comments.*

---

#### **Docstrings**

*A Docstring is a string literal used to document modules, functions, classes, and methods.*

**Syntax:** *A Docstring is written using triple double quotes ```(""" """)``` or triple single quotes ```(''' ''')```*

  ```python
  """This is Docstring!!!"""
  ```

---

**Accessing a Docstring**

*Python provides the ```__doc__``` attribute.*

**Example:**

```python
def greet():
  "Displays a welcome message."
  print("Hello")

print(greet.__doc__)                # Displays a welcome message.
```

---

**Comments vs Docstrings**

| Comments                 | Docstrings                                        |
| ------------------------ | ------------------------------------------------- |
| Explain code             | Document modules, functions, classes, and methods |
| Ignored during execution | Stored as documentation                           |
| Start with `#`           | Written using triple quotes                       |
| Cannot be accessed       | Can be accessed using `__doc__`                   |

---

### **Indentation**

*Indentation is the spaces or tabs added at the beginning of a line to define a block of code in Python.*

---

**Why do we need Indentation?**

- *Most programming languages use curly braces {} to define blocks of code. Python does not use {}.*
- *Without proper indentation, Python cannot understand which statements belong to the ```if``` block.*

---

**Syntax:** *After statements ending with a colon(:) the next line must be indented.*

```python
if (condition):
  statement
```

---

### **Case-Sensitivity**

*Python is Case-Sensitive programming language, which means it treats uppercase and lowercase letters as different.*

---

**Why do we need Case Sensitivity?**

*Case sensitivity allows programmers to create distinct identifiers.*

```python
name="Saranya"
Name="Python"

print(name)
print(Name)
```

---

# **Data Types**

## **Numeric Types**

### **Integer (int)**

*An integer(int) is a numerical data type used to represent whole numbers without a decimal point.*

**Syntax:** *Simply assign a whole number to a variable. Python automatically treats these values as integers.*

  ```python
  age = 20

  marks = 95

  temperature = -5

  count = 0
  ```

---

**How does it work?**

*Whenever Python sees a whole number without a decimal point, it automatically creates an object of type ```int```.*

**Example:**

  ```python
  age=20
  ```

*Here, ```20``` is an integer. Python automatically assigns the type ```int```.*

*We can verify it using*

  ```python
  print(type(age))             # <class 'int'>
  ``` 

---

#### **Number Systems**

*A Number System is a method of representing numbers using a specific set of digits and a base (radix).*

---

**Types of Number Systems**

*Python supports four commonly used number systems.*

| Number System | Base | Digits Used |
| ------------- | ---- | ----------- |
| Decimal       |   10 | 0–9         |
| Binary        |    2 | 0, 1        |
| Octal         |    8 | 0–7         |
| Hexadecimal   |   16 | 0–9, A–F    |

---

**Decimal Number System (Base 10):** *This is the number system we use every day. It uses 10 digits. ```0 1 2 3 4 5 6 7 8 9```.*

**Binary Number System (Base 2):** *Binary uses only 2 digits. ```0 1```. Binary is the language understood by computers.*

**Octal Number System (Base 8):** *Octal uses 8 digits. ```0 1 2 3 4 5 6 7```.*

**Hexadecimal Number System (Base 16):** *Hexa deciaml uses ```0 1 2 3 4 5 6 7 8 9 A B C D E F```*

```txt
A=10 B=11 C=12 D=13 E=14 F=15
```

---

##### **bin()**

*```bin()``` is a built-in python function that converts an integer into its binary representation.*

---

**Why do we need bin()?**

*Computers understand only binary numbers (0 and 1). Instead of converting decimal numbers to binary manually, Python provides the ```bin()``` function.*

**Example:**

  ```txt
  Decimal 10

  Binary 1010
  ```

---

**Syntax:**

  ```python
  bin(integer)
  ```

- *integer → The decimal integer you want to convert.*
- *Returns → A string representing the binary number.*

---

**How does it work?**

- *Suppose you write ```bin(10)```. Python converts decimal 10 into binary.*
- *Result ```0b1010```*
- *Notice the prefix 0b. It indicates that the number is in binary format.*
- *```0b``` → indicates binary format*
- *```1010``` → Actual binary number*

---

##### **oct()**

*```oct()``` is a built-in python function that converts an integer into its octal representation.*

---

**Why do we need oct()?**

*In some areas such as Operating Systems, Computer Architecture, Embedded Systems numbers are sometimes represented in octal(base 8) instead of deciaml. Instead of converting manually, Python provides the ```oct()``` function.*

**Example:**

  ```txt
  Decimal 10

  Octal 12
  ```

---

**Syntax:**

  ```python
  oct(integer)
  ```

- *integer → The integer to convert*
- *Returns → A string representing the octal number*

---

**How does it work?**

- *Suppose you write ```oct(10)```. Python converts the integer 10 into octal.*
- *Result ```0o12```*
- *Notice the prefix 0o*
- *It indicates that the number is in octal format.*

---

##### **hex()**

*```hex()``` is a built-in python function that converts an integer into its hexadeciaml representation.*

---

**Why do we need hex()?**

*Hexadecimal numbers are widely used in Memory addresses, Web colors (HTML/CSS), Computer Architecture, Debugging, Networking. Instead of manually converting numbers to hexadecimal, Python provides the hex() function.*

**Example:**

  ```txt
  Decimal 26

  Hexadecimal 1A
  ```

---

**Syntax:**

  ```python
  hex(integer)
  ```

- *integer → The integer to convert*
- *Returns → A string representing the hexadecimal number*

---

**How does it work?**

- *Suppose you write ```hex(26)```. Python converts the integer 26 into hexadecimal.*
- *Result ```0x1a```*
- *Notice the prefix 0x*
- *It indicates that the number is in hexadecimal format*
- *Also notice ```A → a B → b C → c D → d E → e F → f```*
- *Python returns hexadecimal letters in lowercase by default*

---

*Web developers use hexadecimal values to represent colors.*

**Examples**

```txt
#FFFFFF → White

#000000 → Black

#FF0000 → Red

#00FF00 → Green

#0000FF → Blue
```

*Although these color codes start with ```#```, they are based on hexadecimal numbers.*

---

### **float**

*A float is a built-in numeric data type used to represent numbers that contain a decimal point.*

**Syntax:** *Assign a decimal number to a variable. Python automatically treats these values as float.*

  ```python
  cgpa = 9.15

  price = 9.99

  temperature = 36.5
  ```

---

**How does it work?**

*Whenever Python sees a number with a decimal point ```(.)```, it automatically identifies it as a ```float```.*

**Example:**

  ```python
  cgpa = 9.15

  print(type(cgpa))             # <class 'float'>
  ```

---

#### **Scientific Notation**

*Scientific Notation is a way of representing very large or very small numbers using powers of 10.*

---

**Why do we need Scientific Notation?**

*Imagine writing ```10000000000000000``` or ```0.00000000000045```. These numbers are difficult to read and easy to type incorrectly. Scientific Notation makes them simpler.*

**Example:**

  ```txt
  1000000000000 becomes 1e12 and 0.00000000045 becomes 4.5e-10
  ```

---

**Syntax:**

  ```python
  number = coefficienteexponent
  ```

*General form ```coefficient e exponent``` where e means × 10 raised to the power of the exponent can be positive or negative.*

---

**Examples:**
  ```
  x = 2e3

  y = 5e-2
  ```

---

**How does it work?**

*Python interprets ```2e3``` as ```2 × 10³``` which equals ```2000.0```. Similarly, ```5e-2``` means ```5 × 10⁻²``` which equals ```0.05```.*

---

**Example:**
```python
b = 4e-20

print(b)                    # 4e-20
print(f"{b:e}")             # 4.000000e-20
print(f"{b:f}")             # 0.000000 This prints exactly 6 digits after the decimal (default for f)
print(f"|{b:20f}|")         # |            0.000000| minimum width 20 
print(f"|{b:10.20f}|")      # |0.00000000000000000004|
print(f"|{b:.20f}|")        # |0.00000000000000000004|
f"{b:20f}"                  # '            0.000000'                 
```

---

#### **Precision Values**

*Precision issues occur because floating-point numbers cannot always be represented exactly in binary, leading to small rounding errors during calculations.*

---

**Why do we need to know about Precision Issues?**

- *```print(0.1 + 0.2)``` Output ```0.3``` but python actually prints ```0.30000000000000004```*
- *It is not a bug. It happens because of how computers store floating-point numbers.*

---

**Why does this happen?**

*Computers store numbers in binary. Some decimal numbers such as ```0.1 0.2 0.3``` cannot be represented exactly in binary. Instead, Python stores the closet possible binary approximation. When these approximations are added together, a tiny error appears.*

---

**How does it work?**

- ```print(0.1 + 0.2)``` Output ```0.30000000000000004```
- *Internally, Python stores values approximately ```0.1 ≈ Approximation 0.2 ≈ Approximation``` Adding the approximations produces ```0.30000000000000004```*
- *This tiny difference is called a floating-point precision error.*

---

**Examples:**

```python
print(0.1 + 0.2)            # 0.30000000000000004
```

```python
result = 0.1 + 0.2

print(result == 0.3)        # False
```

```python
result = 0.2 + 0.2

print(result == 0.4)        # True
```

---

**How can we handle precision issues?**

*Use ```round()```*

  ```python
  print(round(0.1 + 0.2, 2))          # 0.3
  ```

---

### **bool**

*```bool``` is a built-in python data type that represents one of two truth values ```True``` or ```False```.*

---

**Why do we need Boolean Values?**

*Programs frequently need to make decisions. Python uses Boolean values to represent these two possible states.*

```txt
Is the user logged in?
        ↓
      True / False

Is age >= 18?
        ↓
      True / False

Is payment successful?
        ↓
      True / False
```

---

**Syntax:** *You can directly assign a Boolean Value*

  ```python
  is_student = True

  print(type(is_student))
  ```

---

#### **Boolean Values**

*Python has only two Boolean Values*
- *```True```: Represents a true condition*
- *```False```: Represents a false condition*

---

**Boolean Values from Comparisons**

*Comparisons produce Boolean values.*

  ```python
  age = 20

  print(age >= 18)
  ```

---

**```bool()``` function**

*Python provides the built-in ```bool()``` function to convert a value into a Boolean value.*

**Syntax:**
  ```python
  bool(value)
  ```

**Example:**
  ```python
  print(bool(1))            # True

  print(bool(0))            # False
  ```

---

#### **Truthy and Falsy Values**

*Truthy Values are values that python treats as ```True``` in a boolean context. Falsy Values are values that Python treats as ```False```.*

---

**Common Falsy Values**

```python
False
None
0
0.0
""
[]
()
{}
set()
```

---

### **complex**

- *A Complex number in python is a numeric data type that contains a real part and an imaginary part.*
- *A complex number has the form ```a + bj``` where ```a → real part``` ```b → imaginary part``` ```j → imaginary unit```*
- *Python uses j, not i, for the imaginary part*

---

**Creating a Complex Number**

**Syntax:**
  ```python
  real + imaginaryj
  ```

**Example:**
  ```python
  a = 4 + 6j

  print(type(a))
  ```

---

**Negative Imaginary Part**

```python
z = 5 - 3j

print(z)              # (5-3j)
```

---

**Real part and Imaginary Part**

*Python provides ```.real``` and ```.imag``` to access the two parts.*

**Example:**
```python
z = 5 + 3j

print(z.real)          # 5.0
print(z.iamg)          # 3.0
```

*Notice that the real and imaginary parts are returned as ```floats```.*

---

**Creating complex numbers using ```complex()```**

*Python also provides the ```complex()``` function.*

**Syntax:**
```python
complex(real, imaginary)
```

**Example:**
```python
z = complex(5, 5)

print(z)            # (5+5j)
```

---

**Complex Number Operations**

*Python supports arithmetic operations on complex numbers.*

**Addition**
```python
a = 8 + 7j
b = 5 + 3j

print(a + b)          # (13+10j)
```

**Multiplication**
```python
a = 8 + 7j
b = 5 + 3j

print(a * b)          # (19+59j)
```

---

## **Strings**

*A string is an immutable sequence of Unicode characters enclosed in quotes.*

---

### **Creating a String**

*Python allows strings to be created using*

**Single quotes:**
```python
name = 'Saranya'

print(type(name))
```

**Double quotes**
```python
name = "Saranya"
```

---

**Triple Quotes**

*Python also supports triple quotes. Triple quotes are particularly useful for multi-line strings.*

```python
msg = """Hello, Saranya!!"""
```

```python
msg = """Hello
Welcome
Let's learn"""

print(msg)               # Hello
                         # Welcome
                         # Let's learn
```

---

**Strings can contain Numbers**

```python
value = "12345"

print(type(value))        # <class 'str'>
```

---

**Strings can contain Special Characters**

```python
text = " Hai $@&*^%()"

print(text, type(text))     # Hai $@&*^%() <class 'str'>
```

---

### **Indexing**

- *String indexing is the process of accessing an individual character from a string using its position (index).*
- *Python uses zero-based indexing*
- *That means the first character has index ```0```*

---

**Syntax:**
```python
string[index]
```

**Example:**
```python
name = "Saranya"

print(name[0])          # S

print(name[1])          # a

print(name[5])          # y
```

---

**How Indexing works?**

*Consider ```name = "Python"```. Python assigns an index to every character*

```txt
Character:  P   y   t   h   o   n
Index:      0   1   2   3   4   5
```

*So*

```txt
name[0]  → 'P'
name[1]  → 'y'
name[2]  → 't'
name[3]  → 'h'
name[4]  → 'o'
name[5]  → 'n'
```

---

**Indexing a String with Spaces**

*Spaces are also characters*

```python
name = "Saranya Sammeta"
```

*Indexes*

```txt
Character: S  a  r  a  n  y  a     S  a  m   m   e   t   a
Index:     0  1  2  3  4  5  6  7  8  9  10  11  12  13  14  
```

```python
name[7]             # ' '
```

---

**Using an Expression as an Index**

*The index doesn't have to be written directly*

```python
name = "Saranya"

index = 3 + 1

print(name[index])            # n
```

---

**Index must be an Integer**

```python
name = "Saranya"

print(name[2])            # r

print(name[2.0])          # TypeError

print(name["2"])          # TypeError
```

---

**Index Out of Range**

```python
name = "Saranya"

print(name[10])       # IndexError: string index out of range
```

---

### **String Slicing**

- *String slicing is the process of extracting a portion of a string using a range of indexes.*
- *Instead of accessing just one character with indexing ```text[2]```*
- *We can extract multiple characters using slicing ```text[1:4]```*

---

**Syntax:**
```python
string[start:stop]
```

*The ```start``` index is included, but the ```stop``` index is excluded.*

**Example:**
```python
name = "Saranya"

print(name[2:5])          # ran
```

*Indexes*

```txt
Character:  S   a   r   a   n   y   a
Index:      0   1   2   3   4   5   6
```

---

**Omitting ```start```**

*You can leave the starting index empty*

```python
name = "Saranya"

print(name[:5])         # Saran
```

---

**Omitting ```stop```**

*You can also leave the ending index empty*

```python
name = "Saranya"

print(name[0:])         # Saranya
```

---

**Omitting Both**

```python
name = "Saranya"

print(name[:])          # Saranya
```

---

**Slicing with a string of one character**

```python
name = "Saranya"

print(name[2:3])        # r
```

---

**Out-of-Range Slicing**

```python
name = "Saranya"

print(name[0:19])       # Saranya
```

*It does not cause an error. Python simply stops at the end of the string.*

---

**Empty Slices**

```python
name = "Saranya"

print(name[3:3])            #
```

*Because the start and stop positions are the same, and the stop position is excluded.*

---

### **Negative Indexing**

- *Negative indexing allows us to access elements of a string starting from the end using negative index value.*
- *Python uses ```-1 → last character``` ```-2 → second-last character``` ```-3 → third-last character```*

---

**How Negative Indexing works?**

```python
text = "Python"
```

*Positive Indexes:*

```txt
Character:  P    y    t    h    o    n
Positive:   0    1    2    3    4    5
```

*Negative Indexes:*

```txt
Character:  P    y    t    h    o    n
Negative:  -6   -5   -4   -3   -2   -1
```

---

**Negative Indexing with Slicing**

*Negative indexes can also be used with slicing.*

```python
name = "Saranya"

print(name[-3:])        # nya

print(name[-4:-1])      # any
```

---

### **Step Slicing**

- *Step slicing allows us to specify how many positions python should move while extracting elements from a sequence.*
- *Step slicing ```string[start:stop:step]```*
- *The third value ```step``` controls the movement between characters*

---

**Syntax:**
```python
string[start:stop:step]
```

*There are three parts*

| Part    | Meaning                       |
| ------- | ----------------------------- |
| `start` | Where slicing begins          |
| `stop`  | Where slicing stops, excluded |
| `step`  | How many positions to move    |

---

**How does ```step``` work?**

```python
text = "Python"

print(text[0:6:2])        # Pto
```

*Indexes*

```txt
Character:  P   y   t   h   o   n
Index:      0   1   2   3   4   5
```

*Now ```text[0:6:2]``` Python starts at ```0``` and moves by ```2```*

---

**Using Start and Stop**

```python
text = "Python"

print(text(1:6:2))          # yhn
```

---

**Step of ```1```**

*A step of ```1``` means move one position at a time.*

```python
text = "Python"

print(text[0:6:1])          # Python
```

---

**Step of ```2```**

```python
text = "Python"

print(text[::2])              # Pto
```

---

**Step of ```3```**

```python
text = "abcdefghi"

print(text[::3])                # adg
```

---

**Negative Step**

*A negative step means python moves backward*

```python
text = "Python"

print(text[::-1])               # nohtyP
```

---

### **String Immutability**

*String immutability means that once a string object is created, its individual characters cannot be changed.*

**Example:**
```python
text = "Python"

text[0] = 'J'               # TypeError: 'str' object does not support item assignment
```

---

**How can we modify a string?**

*We create a new string*

```python
name = "Python"

name = 'J' + name[1:]

print(name)                 # Jython
```

*Python did not not modify ```Python```. It created a new string ```Jython``` and then assigned it to name.*

---

### **String Interning**

*String interning is a memory optimization technique where Python reuses the same string object for certain identical strings instead of creating separate objects.*

**Example:**
```python
a = "Python"
b = "Python"

print(a is b)             # True

print(id(a))              # 1632410799632
print(id(b))              # 1632410799632
```

---

**is vs ==**

*String interning is closely related to the difference between ```is``` and ```==```.*

**is:** *For object identity*

**==:** *For value equality*

---

**Explicit Interning**

*Python provides the ```sys.intern()``` function.*

```python
import sys

a = sys.intern("Hello World")
b = sys.intern("Hello World")

print(a is b)                 # True
```

---

### **Escape Characters**

*Escape Characters are special characters sequences beginning with a ```backslash (\)``` that are used to represent characters or formatting that are difficult or impossible to write directly inside a string.*

*For example:*

```python
print("Hello\nWorld")             # Hello
                                  # World
```

---

**The Backslash ```\```**

*Escape sequences generally begin with ```\```.*

```txt
\n
\t
\"
\'
\\
```

*The backslash tells python that the following character has a special meaning.*

---

**Important Escape Characters**

| Escape sequence | Meaning         |
| --------------- | --------------- |
| `\n`            | New line        |
| `\t`            | Tab             |
| `\\`            | Backslash       |
| `\'`            | Single quote    |
| `\"`            | Double quote    |
| `\r`            | Carriage return |
| `\b`            | Backspace       |
| `\f`            | Form feed       |
| `\v`            | Vertical tab    |
| `\a`            | Alert/bell      |

---

**```\n``` - New Line**

*```\n``` tells python to move to the next line.*

```python
print("Hello\nWorld")             # Hello
                                  # World
```

**```\t``` - Tab**

*```\t``` inserts a tab space. Useful for formatting output.*

```python
print("Hello\tWorld")             # Hello	World
```

**```\"``` - Double Quote**

*Treat this quotation mark as part of the string.*

```python
print("Hello \"World\"")          # Hello "World"
```

**```\'``` - Single Quote**

```python
print("I\'m Saranya")             # I'm Saranya
```

**```\\``` - Backslash**

```python
print("C:\\windows\\downloads\\smart")      # C:\windows\downloads\smart
```

**```\r``` - Carriage return**

*```\r``` moves the cursor back to the beginning of the current line.*

```python
print("Hello\rWorld")           # World
```

**```\b``` - Backspace**

```python
print("1\bHello")               # Hello
```

---

### **Raw Strings**

*A raw string is a string in which backslashes are generally treated as literal characters rather than starting ordinary escape sequences.*

*Raw strings are created by putting ```r``` before the string.*

```python
path = r"C:\Users\Saranya\Documents"
```

---

**Syntax:**
```python
r"string"

r'string'
```

**Example:**
```python
text = r"Hello\nWorld"

print(text)                     # Hello\nWorld
```

---

**Normal String vs Raw String**

**Normal String**

```python
print("Hello\nWorld")             # Hello
                                  # World
```

**Raw String**

```python
print(r"Hello\nWorld")             # Hello\nWorld
```

---

**Raw Strings and Regular Expressions**

*Raw Strings are especially useful with regular expressions.*

**Example:**

```python
pattern = r"\d+\.\d+"

print(pattern)                  # \d+\.\d+
```

---

**Important Limitation**

*A raw string cannot end with a single backslash.*

```python
text = r"C:\Users\"

print(text)                     # SyntaxError: unterminated string literal (detected at line 1); perhaps you escaped the end quote?
```

*You can use instead*

```python
text = r"C:\\Users\\"

print(text)                     # C:\\Users\\
```

*For normal everyday paths another option is to use ```pathlib```.*

---

### **Unicode**

*Unicode is a universal character-encoding standard that assigns a unique code point to characters from different writing systems, symbols, and emojis.*

**Example:**

```python
name = "Saranya"

text = "నమస్కారం"

unic = "你好"

emoji = "😀"
```

---

**Python 3 and Unicode**

*In Python 3, strings (str) are unicode text.*

```python
text = "నమస్కారం"

print(type(text))               # <class 'str'>
```

---

**Unicode Code Points**

- *Every unicode character has a unique code point.*
- *A code point is usually written like ```U+XXXX````*
- *For example ```A → U+0041```*
- *The U+ means this number represents a Unicode code point.*

---

**Unicode is much larger than English**

*Unicode contains characters from many writing systems.*

**Examples:**

```python
print("Hello")
print("నమస్కారం")
print("नमस्ते")
print("你好")
print("こんにちは")
print("مرحبا")
print("😀")
```

---

**Unicode vs ASCII**

**ASCII:** *ASCII is a much smaller character-encoding standard primarily designed for basic english characters and control characters.*

**Unicode:** *Unicode is a much broader standard designed to represent characters from many languages and symbol sets.*

---

**Unicode Escape Sequences**

*Python allows unicode characters to be represented using escape sequence.*

```python
text = "\u0041"

print(text)               # A

print("\u03A9")           # Ω
```

*The ```\u``` form is used for Unicode code points represented using for hexadecimal digits.*

---

**Unicode Code points beyond ```FFFF```**

*Unicode also contains code points that require more than four hexadecimal digits.*

- *Python supports ```\UXXXXXXXX``` with 8 hexadecimal digits.*
- *For example, an emoji can be represented using a unicode escape*
```python
print("\U0001F600")             # 😀
```

---

### **ASCII**

*ASCII (American Standard Code for Information Interchange) is a character-encoding standard that assigns numerical values from 0 to 127 to a set of basic English letters, digits, punctuation marks and control characters.*

**Example:**
```txt
A → 65
B → 66
C → 67

a → 97
b → 98
c → 99
```

---

**ASCII Range**

- *The original ASCII standard contains 128 characters.*
- *Their numeric values range from ```0 to 127```.*

```txt
ASCII = 128 characters
Range = 0–127
```

---

**What does ASCII contain?**

*ASCII includes*

**Uppercase letters**

```txt
A → 65
B → 66
...
Z → 90
```

**Lowercase letters**

```txt
a → 97
b → 98
...
z → 122
```

**Digits**

```txt
0 → 48
1 → 49
...
9 → 57
```

**Punctuation and Symbols**

```txt
! → 33
" → 34
# → 35
```

*It also includes control characters such as newline and tab.*

---

**Is ASCII part of Unicode?**

*Yes. The first 128 unicode code points correspond to the original ASCII characters.*

```txt
ASCII A → 65
Unicode U+0041 → A
```

---

### **ord()**

*```ord()``` is a built-in python function that returns the Unicode code point of a single character.*

**Syntax:**
```python
ord(character)
```

**Example:**
```python
print(ord('A'))               # 65
```

---

**Process a string and want to convert each character into its Unicode code point**

```python
text = "ABC"

for char in text:
  print(ord(char))            # 65
                              # 66
                              # 67
```

---

**Numerical difference between characters**

```python
print(ord("B") - ord("A"))      # 1
print(ord("5") - ord("8"))      # -3
```

---

**Character Range Checking**

```python
char = "S"

if 65 <= ord(char) <=90:
  print("Uppercase ASCII letter")       # Uppercase ASCII letter
```

---

### **chr()**

*```chr()``` is a built-in python function that takes a Unicode code point and returns the corresponding character.*

**Syntax:**
```python
chr(number)
```

**Example:**
```python
print(chr(65))          # A
```

---

**```ord() vs chr()```**

*These two functions are opposite*

```txt
ord() → Character → Unicode number

chr() → Unicode number → Character
```

---

**Generating the Alphabet**

```python
for code in range(65, 91):
  print(chr(code), end =" ")            # A B C D E F G H I J K L M N O P Q R S T U V W X Y Z 
```

---

**```ord()``` and ```char()``` together**

```python
character = "A"

code = ord(character)

print(code)                   # 65
print(chr(code))              # A
```

---

**Character conversion**

**Example:**
```python
char = "b"

code = ord(char)

new_char = chr(code + 1)

print(new_char)             # c
```

---

## **Formatting**

### **f-string**

- *An f-string is a string formatting mechanism in Python that allows expressions and variables to be directly embedded inside a string using ```{}```*
- *It was introduced in Python 3.6*

**Syntax:**
```python
f"some text {expression}"
```

**Example:**
```python
name = "Saranya"
age = 10

print(f"My name is {name} and I'm {age} years old.")      # My name is Saranya and I'm 10 years old.
```

---

**Expressions inside f-strings**

```python
a = 30
b = 20

print(f"Addition : {a + b}")            # Addition : 50
print(f"Subtraction : {a - b}")         # Subtraction : 10
print(f"Multiplication : {a * b}")      # Multiplication : 600
```

---

**Function called inside f-strings**

```python
name = "Saranya"

print(f"Uppercase: {name.upper()}")         # Uppercase: SARANYA
```

---

**Conditional Expression**

```python
age = 20

print(f"Status: {'Adult' if age >= 18 else 'Minor'}")       # Status: Adult
```

---

**Number Formatting**

*f-strings are especially useful for formatting numbers.*

```python
price = 1234.5678

print(f"{price: .2f}")              #  1234.57
```

---

**Decimal Places**

```python
pi = 3.14159265

print(f"{pi: .2f}")               # 3.14
print(f"{pi: .3f}")               # 3.142
print(f"{pi: .4f}")               # 3.1416
```

---

**Percentage Formatting**

```python
score = 0.8567

print(f"{score: .2%}")            #  85.67%
```

---

**Comma Formatting**

```python
salary = 23000000

print(f"{salary: ,}")             #  23,000,000
```

---

**Width and Alignment**

```python
name = "Python"

print(f"{name:>10}")              #     Python
print(f"{name:<10}")              # Python
print(f"{name:^10}")              #  Python 
```

---

**f-string with Dictionaries**

```python
student = {
  "name" : "Saranya",
  "age" : 10
}


print(f"Name: {student['name']}")         # Name: Saranya    
print(f"Age: {student['age']}")           # Age: 10
```

---

**f-string with Object Attributes**

```python
print(f"Student:{student.name}")
```

---

**Escaping Curly Braces**

*Suppose you want to print actual ```{``` and ```}```*

```python
print(f"{{}}")            # {}
```

---

### **format()**

*```format()``` is a string formatting method that inserts values into placeholders ```{}``` inside a string.*

**Syntax:**
```python
"string {}". format(value)
```

**Example:**
```python
name = 'Saranya'
age = 10

print("My name is {} and I'm {}". format(name, age))          # My name is Saranya and I'm 10
```

---

**Positional Arguments**

```python
name = "Saranya"
age = 10

print("My name is {0} and I'm {1}". format(name, age))         # My name is Saranya and I'm 10
```

```txt
0 → first argument
1 → second argument
```

---

**Reusing an Argument**

```python
name = "Saranya"

print("My name is {0}. {0} loves chocolate.".format(name))          # My name is Saranya. Saranya loves chocolate.
```

---

**Changing the Order**

```python
first = "Python"
second = "SQL"

print("{0} and {1}". format(first, second))         # Python and SQL
```

---

**Keyword Arguments**

```python
print("Name: {name}, Age: {age}".format(name = "Saranya", age = 20))          # Name: Saranya, Age: 20
```

---

**Expressions with format()**

```python
a = 10
b = 20

print("Sum = {}". format(a+b))          # Sum = 30
```

---

**Number Formatting**

```python
price = 1234.5678

print("{:.2f}".format(price))             # 1234.578
```

---

**Percentage Formatting**

```python
percentage = 0.5366

print("{:.2%}".format(percentage))          # 53.66%
```

---

**Comma Formatting**

```python
salary = 1000000

print("{:,}".format(salary))            # 1,000,000
```

---

**Alignment**

*Right Alignment*

```python
name = "Python"

print("{:>10}".format(name))              #     Python
```

*Left Alignment*

```python
name = "Python"

print("{:<10}".format(name))              # Python    
```

*Center Alignment*

```python
name = "Python"

print("{:^10}".format(name))              #   Python  
```

---

**Fill Characters**

```python
name = "Python"

print("{:*^10}".format(name))             # **Python**
```

```txt
* → fill character
^ → center
10 → width
```

---

**```format()``` with Dictionaries**

```python
student = {"name": "Saranya", "age": 10, "course": "Python"}

print("Name : {name}, Age : {age}, Course : {course}".format(**student))                      # Name : Saranya, Age : 10, Course : Python
```

---

**```format()``` vs ```f-string```**

*```f-string``` variables/expressions are written directly inside the string*

```python
name = "Saranya"

print(f"Hello {name}")              # Hello Saranya
```

*```format()``` values are supplied after the string*

```python
name = "Saranya"

print("My name is {}".format(name))         # My name is Saranya
```

---

### **%**

*```%``` string formatting is an older string-formatting technique in Python that uses % placeholders to insert values into a string.*

**Syntax:**
```python
"format string" % values
```

**Example:**
```python
name = "Python"

print("I'm learning %s" % name)         # I'm learning Python
```

---

**Common % format specifiers**

| Specifier | Meaning               |
| --------- | --------------------- |
| `%s`      | String                |
| `%d`      | Integer               |
| `%f`      | Floating-point number |
| `%c`      | Character             |
| `%x`      | Hexadecimal integer   |
| `%o`      | Octal integer         |
| `%%`      | Literal `%`           |

---

**```%s``` - String**

```python
name = "Python"

print("I'm learning %s" % name)         # I'm learning Python
```

---

**```%d``` - Integer**

```python
age = 10

print("I'm %d years old." % age)          # I'm 10 years old.
```

---

**```%f``` - float**

```python
price = 99.5

print("Price: %f" % price)                # Price: 99.500000
```

*By default, ```%f``` displays six digits after the decimal point*

---

**Controlling Decimal Places**

```python
price = 99.5678

print("%.2f" % price)               # 99.57
```

---

**Multiple Values**

```python
name = "Saranya"
age = 10

print("Name: %s, Age: %d" % (name, age))          # Name: Saranya, Age: 10
```

---

**Multiple Integers**

```python
a = 10
b = 20

print("%d + %d = %d" % (a, b, a + b))               # 10 + 20 = 30
```

---

**```%c``` - character**

- *```%c``` can format a single character*
- *It can also accept an integer representing a Unicode code point*
- *This connects directly with the ```ord()``` ```chr()```*

```python
print("%c" % "A")                   # A
```

```python
print("%c" % 67)                     # C
```

---

**```%x``` - Hexadecimal**

```python
number = 255

print("%x" % number)                  # ff
```

*For uppercase hexadecimal*

```python
number = 255

print("%X" % number)                  # FF
```

---

**```%o``` - Octal**

```python
number = 10

print("%o" % number)                  # 12
```

---

**```%%``` - Literal Percentage**

```python
score = 95

print("Score: %d%%" % score)          # Score: 95%
```

---

**```%``` vs ```format()``` vs ```f-string```**

*```%```*

```python
name = "Saranya"

print("My name is %s" % name)               # My name is Saranya
```

*```format()```*

```python
name = "Saranya"

print("My name is {}". format(name))              # My name is Saranya
```

*```f-string```*

```python
name = "Saranya"

print(f"My name is {name}")                   # My name is Saranya
```

---

## **String Methods**

### **Case Methods**

*Case methods are string methods used to change or check the capitalization of characters in a string.*

**Important case-related methods**

```txt
upper()
lower()
captialize()
title()
swapcase()
casefold()
```

*These methods do not modify the original string, because strings are immutable*

---

**```upper()```**

*Converts all alphabetic characters to uppercase.*

**Syntax:**
```python
string.upper()
```

**Example:**
```python
name = "Saranya"

print(name.upper())             # SARANYA
```

---

**```lower()```**

*Converts all alphabetic characters to lowercase.*

**Syntax:**
```python
string.lower()
```

**Example:**
```python
name = "SARANYA"

print(name.lower())               # saranya
```

---

**```capitalize()```**

*```capitalize()``` makes the first character uppercase and remaining characters lowercase.*

**Example:**
```python
text = "hello WORLD"

print(text.capitalize())            # Hello world
```

---

**```title()```**

*```title()``` converts the first character of each word to uppercase and the remaining characters of those words to lowercase.*

**Example:**
```python
text = "hello world!!!"

print(text.title())                 # Hello World!!!
```

---

**```swapcase()```**

*```swapcase()``` reverses the case of each alphabetic character.*

**Example:**
```python
name = "SaRanya"

print(name.swapcase())                # sArANYA
```

---

**```casefold()```**

- *```casefold()``` is used for case-insensitive comparisons*
- *It is similar to lower() but more aggressive and designed for Unicode-aware case-insensitive matching.*

**Example:**
```python
name = "Saranya"

print(name.casefold())                # saranya
```

---

**Methods return a new string**

*Python strings are immutable*

```python
name = "Saranya"

name.upper()

print(name, id(name))                 # Saranya 2222358599872

print(name.upper(), id(name.upper()))       # SARANYA 2222358736656
```

---

**Methods don't change numbers**

- *Case methods primarily affect alphabetic characters.*
- *Numbers and punctuation remain unchanged*

```python
text = "python123#$"

print(text.upper())                 # PYTHON123#$
```

---

### **Search Methods**

*Search Methods help us find characters or substrings inside a string.*

**Important search methods**

```txt
find()
rfind()
index()
rindex()
count()
startswith()
endswith()
```

---

**```find()```**

*```find()``` searches for a substring and returns its first position (index).*

**Synatx:**
```python
string.find(substring)
```

**Example:**
```python
text = "My name is Saranya"

print(text.find("Saranya"))               # 11
```

**Searching for a Character**

```python
text = "Python"

print(text.find("h"))                     # 3
```

---

**```find()``` when the substring doesn't exist**

```python
text = "Python"

print(text.find("Saranya"))               # -1
```

*```find()``` returns -1 when the substring is not found.*

---

**```find()``` with start and end positions**

**Syntax:**
```python
string.find(substring, start, end)
```

**Example:**
```python
text = "Python Python"

print(text.find("Python", 1))           # 7
```

*The first ```"Python"``` starts at 0, but searching starts from index 1 so Python finds the second occurrence.*

---

**```rfind()```**

*```rfind()``` searches from the right side and returns the position of the last occurrence.*

```python
text = "Python Python"

print(text.rfind("Python"))               # 7
```

```python
fruit = "banana"

print(fruit.rfind("a"))                   # 5
```

---

**```find()``` vs ```rfind()```**

```python
fruit = "banana"

print(fruit.find("a"))                    # 1
print(fruit.rfind("a"))                   # 5
```

---

**```index()```**

*```index()``` is similar to ```find()```*

```python
text = "Python"

print(text.index("o"))                    # 4
```

---

**```find()``` vs ```index()```**

*Suppose the substring doesn't exist*

**```find()```**

```python
text = "Python"

print(text.find("s"))                     # -1
print(text.index("s"))                    # ValueError: substring not found
```

---

**```rindex()```**

*```rindex()``` is the right-to-left version of index()*

```python
text = "banana"

print(text.rindex("a"))                     # 5
```

---

**```count()```**

*```count()``` tells you how many times a substring occurs.*

**Syntax:**
```python
string.count(substring)
```

**Example:**
```python
text = "banana"

print(text.count("a"))                        # 3
```

---

**```count()``` with a substring**

```python
text = "Python Python"

print(text.count("Python"))                   # 2
print(text.count(" "))                        # 1
print(text.count(""))                         # 14
print(text.count("a",2))                      # 2
```

---

**```count()``` returns zero**

*If a substring doesn't exist*

```python
text = "banana"

print(text.count("s"))                        # 0
``` 

---

**```startswith()```**

- *```startswith()``` checks whether a string begins with a particular substring.*
- *It returns a Boolean ```True False```*

**Example:**
```python
text = "banana"

print(text.startswith("b"))                   # True
print(text.startswith("s"))                   # False
print(text.startswith("ban"))                 # True
```

---

**```endswith()```**

- *```endswith()``` checks whether a string ends with a particular substring.*

**Example:**
```python
text = "banana"

print(text.endswith("a"))                     # True
print(text.endswith("A"))                     # False
```

---

**Case Sensitivity**

*Search methods are generally case-sensitive*

**Example:**
```python
text = "Python"

print(text.find("python"))                    # -1
```

*Because Python and python are different strings. If you want a case-insensitive search, normalize the strings.*

*If you want a case-insensitive search, normalize the strings*

```python
text = "Python"

print(text.casefold().find("python"))           # 0
```

---

**Searching with Start and End**

*Several search methods support optional ```start``` and ```end```arguments*

**Example:**
```python
text = "banana"

print(text.find("a",2))                         # 3
print(text.count("a",2))                        # 2
```

---

**```startswith()``` with Multiple Options**

```python
filename = "report.csv"

print(filename.startswith(("report","sales")))          # True
```

*This means does the string start with either "report" or "sales"?*

---

### **Validation Methods**

*String Validation Methods are built-in string methods that check whether the characters in a string satisfy a particular condition and return a Boolean value.*

*The important methods are*

```txt
isalpha()
isdigit()
isdecimal()
isnumeric()
isalnum()
isspace()
islower()
isupper()
istitle()
isidentifier()
isascii()
isprintable()
```

---

**```isalpha()```**

*Checks whether all characters are alphabetic.*

```python
text = "Python"

print(text.isalpha())                     # True
```

```python
text = "Python123"

print(text.isalpha())                     # False
```

*Because the string contains digits*

```python
"".isalpha()                              # False
```

---

**```isdigit()```**

*Checks whether all characters are digits.*

```python
text = "12345"

print(text.isdigit())                      # True
```

```python
text = "12345Saran"

print(text.isdigit())                      # False
```

```python
"-25".isdigit()                            # False
```

---

**```isdecimal()```**

*Checks whether all characters are decimal characters*

```python
print("1234".isdecimal())                   # True
```

- *For basic decimal digits ```isdigit() ≈ isdecimal()``` but they are not exactly the same.*
- *Unicode contains some digit-like characters that isdigit() accepts but isdecimal() does not.*

---

**```isnumeric()```**

*```isnumeric()``` is broader than ```isdigit()```. It checks whether all characters are numeric characters.*

```python
print("123".isnumeric())                    # True
```

```txt
isdecimal()
    ↓
isdigit()
    ↓
isnumeric()
```

*Every decimal character is a digit, and every digit is numeric, but the reverse is not always true.*

---

**```isalnum()```**

*```isalnum()``` means Alphabetic or Numeric.*

```python
text = "12345Saran"

print(text.isalnum())                         # True
```

```python
text = "12345 Saran"

print(text.isalnum())                         # False
```

```python
"Python@124".isalnum()                        # False
```

---

**```isspace()```**

*Checks whether all characters are whitespace characters.*

```python
text = " "

print(text.isspace())                          # True
```

*It can recognize whitespace such as spaces, tabs, and newlines.*

```python
print("\t".isspace())                         # True
print("\n".isspace())                         # True
```

```python
text = ""

print(text.isspace())                         # False
```

---

**```islower()```**

*Checks whether the string contains cased characters and all of those cased characters are lowercase.*

```python
text = "Python"

print(text.islower())                         # False
```

```python
text = "python"

print(text.islower())                         # True
```

**Numbers don't have a case**

```python
print("python123".islower())                  # True
print("Python123".islower())                  # False
```

---

**```isupper()```**

*Checks whether the string contains cased characters and all of them are uppercase.*

```python
text = "Python"

print(text.isupper())                         # False
```

```python
text = "PYTHON"

print(text.isupper())                         # True
```

**Numbers don't affect the case check**

```python
print("PYTHON123".isupper())                    # True
print("Python123".isupper())                    # False
```

---

**```istitle()```**

*Checks whether the string follows title-case rules.*

```python
text = "Python Programming"

print(text.istitle())                           # True
```

```python
text = "python Programming"

print(text.istitle())                           # False
```

---

**```isidentifier()```**

*Checks whether a string is a valid Python Identifier.*

```python
print("name".isidentifier())                    # True
print("student_name".isidentifier())            # True
print("123name".isidentifier())                 # False
```

---

**Important**

*```isidentifier()``` does not check Keywords.*

```python
print("if".isidentifier())                      # True
print("class".isidentifier())                   # True
```

---

**```isascii()```**

*Checks whether all characters are ASCII characters.*

```python
print("Python".isascii())                       # True
print("Pyth%n".isascii())                       # True
print("Python123".isascii())                    # True
```

```python
print("నమస్కారం".isascii())                    # False
print("😀".isascii())                           # False
```

*Because those characters are outside ASCII.*

---

**```isprintable()```**

*Checks whether all characters are printable.*

```python
print("Hello".isprintable())                    # True
print("Hello\nWorld".isprintable())             # False
```

---

**Empty Strings**

*Most validation methods return False for an empty string.*

```python
print("".isalpha())                             # False
print("".isdigit())                             # False
print("".isalnum())                             # False
print("".isspace())                             # False
print("".islower())                             # False
```

---

### **Replace Methods**

*```replace()``` is a string method used to replace occurrences of one substring with another substring.*

**Syntax:**
```python
string.replace(old, new)
```

**Example:**
```python
text = "I like Java"

result = text.replace("Java", "Python")

print(result)                                   # I like Python
```

---

**Strings are Immutable**

```python
text = "Python"

text.replace("P", "J")

print(text)                                    # Python
```

*Because strings are immutable. replace() does not modify the original string. It creates and returns a new string.*

```python
text = "Python"

text = text.replace("P", "J")

print(text)                                   # Jython
```

---

**Basic Replacement**

```python
text = "Python"

print(text.replace("P","J"))                  # Jython
```

---

**Replacing a Character**

```python
text = "banana"

print(text.replace("a","o"))                    # bonono
```

---

**Replacing Multiple Occurrences**

```python
text = "Python Python SQL"

print(text.replace("Python", "Java"))             # Java Java SQL
```

---

**The ```count``` parameter**

*```replace()``` has an optional third argument. The ```count``` specifies the maximum number of replacements.*

**Syntax:**
```python
string.replace(old, new, count)
```

**Example:**
```python
text = "Python Python Python"

print(text.replace("Python", "SQL", 1))                 # SQL Python Python
```

---

**Replacing the first two occurrences**

```python
text = "Python Python Python"

print(text.replace("Python", "SQL", 2))                 # SQL SQL Python
```

---

**```count = 0```**

```python
text = "Python Python Python"

print(text.replace("Python", "SQL", 0))                 # Python Python Python
```

---

**Replacing with an Empty String**

```python
text = "Python Programming"

print(text.replace("Python", ""))                       # Programming
```

---

**Removing Spaces**

```python
text = "P y t h o n"

print(text.replace(" ", ""))                            # Python
```

---

**Replacing Multiple Different Characters**

```python
text = "Hello, World!"

text = text.replace(",","")
text = text.replace("!","")

print(text)                                   # Hello World
```

---

**Chaining replace()**

```python
text = "Hello, World!"

result = text.replace(",","").replace("!","")

print(result)                               # Hello World
```

---

**Case Sensitivity**

*```replace()``` is case-sensitive.*

```python
text = "Python python Python"

print(text.replace("python", "SQL"))                  # Python SQL Python
```

---

**Replacing a substring with a longer string**

```python
text = "I like Python"

print(text.replace("Python", "Python Programming"))           # I like Python Programming
```

---

**```translate()``` and ```maketrans()```**

*For replacing individual characters according to a mapping, Python provides ```translate()``` and ```maketrans()```*

**Example:**
```python
text = "hello"

text = str.maketrans("helo", "HELO")

print(text.transalte(table))                          # HELLO
```

```txt
maketrans()
    ↓
creates translation table

translate()
    ↓
applies translation table
```

---

### **Split**

*```split()``` is a string method used to divide a string into multiple parts and return them as a list.*

**Syntax:**
```python
string.split(separator, maxsplit)
```

*Both separator and maxsplit are optional.*

---

```python
text = "Python SQL Excel"

print(text.split())                         # ['Python', 'SQL', 'Excel']

print(type(text))                           # <class 'str'>
```

---

**Splitting Using a specific Separator**

```python
text = "Python, SQL, Excel"

print(text.split(","))                      # ['Python', ' SQL', ' Excel']
```

---

**What is a Separator/Delimiter?**

*A delimiter is a character or substring used to separate pieces of data.*

```txt
,   → comma
-   → hyphen
:   → colon
|   → pipe
```

```python
data = "apple-orange-banana"

print(data.split("-"))                        # ['apple', 'orange', 'banana']
```

---

**Splitting on ```-```**

```python
date = "29-08-2026"

print(date.split("-"))                        # ['29', '08', '2026']
```

---

**Splitting on ```,```**

```python
data = "Python,SQL,Power BI,Excel"

print(data.split(","))                        # ['Python', 'SQL', 'Power BI', 'Excel']
```

---

**```maxsplit()```**

*It specifies the maximum number of splits.*

**Syntax:**
```python
string.split(separator, maxsplit)
```

**Example:**
```python
text = "Python SQL Excel PowerBI"

print(text.split(" ", 2))                     # ['Python', 'SQL', 'Excel PowerBI']
```

---

**```maxsplit=0```**

```python
text = "Python SQL Excel PowerBI"

print(text.split(" ", 0))                     # ['Python SQL Excel PowerBI']
```

---

**Splitting a sentence**

```python
sentence = "Python is easy to learn"

print(sentence.split())                        # ['Python', 'is', 'easy', 'to', 'learn']
```

---

**Splitting User Input**

```python
skills = input("Enter skills:").split()

print(skills)                                 # ['Python,', 'SQL,', 'Excel,', 'PowerBI']
```

---

**Multiple Inputs Using ```split()```**

```python
a, b = input().split()

print(a, type(a))                             # 10 <class 'str'>
print(b)                                      # 20
```

```python
a, b = map(int, input().split())

print(a, type(a))                             # 10 <class 'int'>
print(b)                                      # 20
```

---

**```split()``` + ```map()```**

```python
numbers = list(map(int, input().split()))

print(numbers)                                # [10, 20, 30, 40]
```

---

**Splitting with Multiple Spaces**

*Default ```split()``` behaves differently from explicitly specifying ```" "```.*

```python
text = "Python   SQL"

print(text.split())                           # ['Python', 'SQL']
```

```python
text = "Python   SQL"

print(text.split(" "))                        # ['Python', '', '', 'SQL']
```

*Because when you explicitly specify ```" "``` each individual space is treated as a separator.*

---

**```split()``` vs ```split(" ")```**

```python

print("Python   SQL".split())                 # ['Python', 'SQL']

print("Python   SQL".split(" "))              # ['Python', '', '', 'SQL']
```

*When you simply want to separate whitespace-delimited words, prefer ```split()``` without an argument.*

---

**Splitting on Newline**

```python
text = "Python\nSQL\nExcel"

print(text.split("\n"))                       # ['Python', 'SQL', 'Excel']
```

---

**Splitting on Multiple Characters**

```python
text = "Python:::SQL::Excel"

print(text.split(":"))                        # ['Python', '', '', 'SQL', '', 'Excel']
```

*So the separator can be One character or multiple characters.*

---

**What happens with an Empty String?**

```python
text = ""

print(text.split())                           # []
```

*An empty string produces an empty list when using default whitespace splitting.*

---

**What happens when the Separator isn't found?**

```python
text = "Python SQL"

print(text.split(","))                        # ['Python SQL']
```

*No comma exists, so the original string becomes one list element.*

---

**Consecutive Separators**

```python
text = "A,,B"

print(text.split(","))                        # ['A', '', 'B']
```

---

**```split()``` returns a list**

```python
text = "Python SQL Excel"

result = text.split()

print(result, type(result))                     # ['Python', 'SQL', 'Excel'] <class 'list'>
```

---

**```split()``` does not modify the original string**

```python
text = "Python SQL"

text.split()

print(text)                                     # Python SQL
```

---

**```split()``` vs ```rsplit()```**

*There is related method called ```rsplit()```.*
- *```split()``` splits from left*
- *```rsplit()``` splits from right*

```python
text = "A-B-C-D"

print(text.split("-",1))                        # ['A', 'B', 'C-D']

print(text.rsplit("-",2))                       # ['A-B', 'C', 'D']
```

---

**```split()``` vs ```partition()```**

*Another related method is ```partition()``` but it behaves differently.*

```python
text = "Python-SQL"

print(text.split("-"))                            # ['Python', 'SQL']

print(text.partition("-"))                        # ('Python', '-', 'SQL')
```

```txt
split()
→ returns list

partition()
→ returns 3-part tuple:
   before separator
   separator
   after separator
```

---

### **Join**

*```join()``` is a string method used to combine elements of an iterable into a single string, using the string on which ```join()``` is called as the separator.*

**Syntax:**
```python
separator.join(iterable)
```

**Example:**
```python
words = ["Python", "SQL", "Excel"]

result = " ".join(words)

print(result, type(result))                                 # Python SQL Excel <class 'str'>
```

---

**Using Different Separators**

**Space:**

```python
print(" ".join(["Python", "SQL"]))                    # Python SQL
```

**Comma:**

```python
print(",".join(["Python", "SQL"]))                     # Python,SQL
```

**Comma + Space:**

```python
print(", ".join(["Python", "SQL"]))                     # print(", ".join(["Python", "SQL"]))
```

**Hyphen:**

```python
print("-".join(["Python", "SQL"]))                      # Python-SQL
```

**Empty String:**

```python
print("".join(["P","y","t","h","o","n"]))               # Python
```

---

**```join()``` works on strings too**

*A string itself is iterable.*

```python
text = "Python"

print("-".join(text))                                 # P-y-t-h-o-n
```

---

**```join()``` with a Tuple**

*```join()``` doesn't require specifically a list. It accepts an iterable of strings.*

```python
words = ("Python", "SQL", "Excel")

print(" | ".join(words))                              # Python | SQL | Excel
```

```txt
list       → works
tuple      → works
string     → works
other iterable → can work
```

---

**All Elements must be Strings**

```python
numbers = ["10", "20", "30", "40"]

print("-".join(numbers))                              # 10-20-30-40
```

*But this does not work*

```python
number = [10, 20, 30]

print("-".join(numbers))                        # TypeError
```

*Because ```join()``` expects the iterable's elements to be strings.*

---

**Joining numbers correctly**

```python
numbers = [10, 20 ,30]

result = "-".join(map(str, numbers))

print(result)                               # 10-20-30
```

---

**```split()``` and ```join()``` together**

```python
text = "Python is easy"

print(text.split())                       # ['Python', 'is', 'easy']
print("-".join(text.split()))             # Python-is-easy
```

---

**Empty List**

```python
word = []

print(" ".join(word))                     # 
" ".join(word)                            # ''
```

---

**One Element**

```python
words = ["Python"]

print("-".join(words))                    # Python
```

*There is no separator because there is only one element. The separator goes between elements.*

---

**Two Elements**

```python
words = ["Python", "SQL"]

print(" + ".join(words))                  # Python + SQL
```

---

**Three Elements**

```python
words = ["Python", "SQL", "Excel"]

print(" | ".join(words))                  # Python | SQL | Excel
```

**General rule:**

```txt
n elements
→ n - 1 separators
```

```txt
3 elements → 2 separators
5 elements → 4 separators
```

---

**Separator can be more than One Character**

*It doesn't have to be a single character.*

```python
words = ["Python", "SQL", "Excel"]

print(" ----->| ".join(words))                  # Python ----->| SQL ----->| Excel
```

*The separator can be*

```txt
", "
" - "
" | "
" ---> "
```

*or any other string.*

---

**```join()``` does not modify the original iterable**

```python
words = ["Python", "SQL"]

result = " - ".join(words)

print(words)                            # ['Python', 'SQL']
print(result)                           # Python - SQL
```

---

**```join()``` returns a string**

```python
words = ["Python", "SQL"]

result = " - ".join(words)

print(result, type(result))                 # Python - SQL <class 'str'>
```

---

**```split()``` vs ```join()```**

**```split()```**

```python
text = "Python SQL Excel"

print(text.split())                         # ['Python', 'SQL', 'Excel']
```

*String → List*

**```join()```**

```python
text = ["Python", "SQL", "Excel"]

print(" - ".join(text))                     # Python - SQL - Excel
```

*List → String*

---

```python
numbers = [1, 2, 3]

print("-".join(numbers))                    # TypeError: sequence item 0: expected str instance, int found

print("-".join(map(str, numbers)))          # 1-2-3
```

---

**```join()``` with Mixed Types**

```python
data = ["Python", 10, "SQL"]

print(",".join(map(str,data)))            # Python,10,SQL

",".join(data)                            # TypeError: sequence item 1: expected str instance, int found
```

*Because 10 is an integer*

---

**Nested Lists**

```python
data = [["Python", "SQL"], ["Excel", "Power BI"]]

print("-".join(map(str, data)))           # ['Python', 'SQL']-['Excel', 'Power BI']
"-".join(data)                            # TypeError: sequence item 0: expected str instance, list found
```

---

### **Alignment**

*String alignment methods are used to position a string within a specified width by adding padding characters.*

*Python provides*

```txt
ljust()   → left-align
rjust()   → right-align
center()  → center-align
zfill()   → pad with zeros
```

---

#### **```ljust()```**

*```ljust()``` means left justify. It places the string on the left side and adds spaces on the right.*

**Syntax:**

```python
string.ljust(width)
```

**Example:**

```python
text = "Python"

print(text.ljust(20))                         # Python 
```

*The total width is 10, so Python adds ```10 - 6 = 4``` spaces.*

---

**Visualizing ```ljust()```**

```txt
Width = 10

|Python    |
|← 6 chars →←4 spaces→|
```

---

**Custom Fill Character**

*You can specify a character to use for padding.*

**Syntax:**

```python
string.ljust(width, fillchar)
```

**Example:**

```python
text = "Python"

print(text.ljust(10, "-"))                    # Python----
```

---

#### **```rjust```**

*```rjust()``` means right justify. It places the string on the right side and adds padding on the left.*

```python
text = "Python"

print(text.rjust(30))                         #                         Python
```

*There are 24 spaces before ```Python```.*

---

**Visualizing ```rjust()```**

```txt
Width = 30

|    Python|
|←24 spaces→←6 chars→|
```

---

**Custom Fill Character with ```rjust()```**

```python
text = "Python"

print(text.rjust(10, "-"))                # ----Python
```

---

#### **```center()```**

*```center()``` places the string in the middle of the specified width.*

**Syntax:**

```python
string.center(width)
```

**Example:**

```python
text = "Python"

print(text.center(10))              #   Python  
```

*The string is centered within a width of 10.*

---

**Custom Fill Character with ```center()```**

```python
text = "Python"

print(text.center(10, "-"))               # --Python--
```

*The ```-``` characters fill the remaining space.*

---

**What if width is smaller?**

```python
text = "Python"

print(text.ljust(3))                    # Python
```

*The string already has length 6. Since the requested width is smaller than the string length, Python does not truncate the string.*

---

**What if width equals string length?**

```python
text = "Python"

print(text.ljust(6))                      # Python
print(text.rjust(6))                      # Python
print(text.center(6))                     # Python
```

*No padding is needed. The string remains ```Python```.*

---

**```center()``` with Odd Padding**

```python
text = "Python"

print(text.center(11, "-"))                 # ---Python--
```

*Python has length 6. Required padding ```11 - 6 = 5``` There are 5 padding characters. Python distributes them as evenly as possible.*

---

#### **```zfill()```**

*```zfill()``` means zero fill. It pads a string with zeros on the left until it reaches the specified width.*

**Syntax:**

```python
string.zfill(width)
```

**Example:**

```python
text = "Sara"

print(text.zfill(5))                    # 0Sara
```

```txt
Original length = 4
Requested width = 5
Zeros needed = 1
```

---

**```zfill()``` is a String Method**

```python
number = "56"

result = number.zfill(4)

print(type(number))                       # <class 'str'>
print(type(result))                       # <class 'str'>
```

---

**```zfill()``` with Numbers**

```python
number = 34

print(number.zfill(7))                # AttributeError: 'int' object has no attribute 'zfill'
```

*Convert it*

```python
number = 34

print(str(number).zfill(7))             # 0000034
```

---

**```zfill() and Negative Numbers**

```python
number = "-78"

print(number.zfill(5))                  # -0078
```

*Notice the zeros are placed after the sign. Not ```00-42``` but ```-0042```. Python treats ```+``` and ```-``` as signs when using ```zfill()```.*

*Same as for Positive Numbers.*

---

**Fill Character must be One Character**

```python
"Python".ljust(10, "-")                 # 'Python----'
```

*But the fill character must be exactly one character.*

*For example*

```python
"Python".rjust(10, "--")                      # TypeError: The fill character must be exactly one character long
```

---

**```Alignment``` vs ```format()```**

```python
print("{:<10}".format("Python"))            # Python 
print("{:>10}".format("Python"))            #     Python
print("{:^10}".format("Python"))            #   Python 
```

```txt
String methods
    ↓
ljust()
rjust()
center()

String formatting
    ↓
format()
f-string
```

---

**Alignment with f-strings**

```python
name = "Python"

print(f"{name:>10}")                  #     Python
print(f"{name:<10}")                  # Python   
print(f"{name:^10}")                  #   Python 
```

---

| Method     | Purpose            |
| ---------- | ------------------ |
| `ljust()`  | Left-align         |
| `rjust()`  | Right-align        |
| `center()` | Center-align       |
| `zfill()`  | Zero-pad from left |

---

```python
employee_id = "125"

result = "EMP" + employee_id.zfill(5)

print(result)
```

---

## **Lists**

*A ```List``` is an ordered, mutable collection in Python that can store multiple values, including values of different data types.*

**Example:**

```python
numbers = [10, 20, 30, 40]
```

*Here ```numbers``` is a list containing four elements.*

---

**Why do we need Lists?**

*Suppose you want to store several student marks.*

**Without a list:**

```python
mark1 = 85
mark2 = 90
mark3 = 78
mark4 = 92
```

*This becomes difficult to manage.*

**With a list:**

```python
marks = [85, 90, 78, 92]
```

*Now all the marks are stored together.*

---

**Creating a list**

```python
list_name = [element1, element2, element3]
```

**Example:**

```python
numbers = [10, 20, 30, 40]
```

```python
names = ["Saranya", "Sai", "Adnan", "Tej"]
```

---

**Empty List**

*You can create a list with no elements.*

```python
list = []

print(list, type(list))                   # [] <class 'list'>
```

*This is called an empty list. Empty lists are commonly used when you plan to add elements later.*

---

**Lists can store different data types**

*Python lists can contain different types of values.*

```python
data = [10, "Python", 3.14, True]
```

*Here*

```txt
10       → int
"Python" → str
3.14     → float
True     → bool
```

*All of them can exist inside the same list.*

---

**List can store duplicate values**

*List allow duplicates*

```python 
numbers = [10, 20, 10, 30, 20]
```

*The list contains ```10 20 10 30 20```*

*Unlike a set, a list does not automatically remove duplicates.*

---

**List is Ordered**

*Lists maintain the order in which elements are inserted.*

```python
skills = ["Python", "SQL", "Excel"]
```

*The order is ```Python SQL Excel```. Python doesn't automatically rearrange them. So a list is an Ordered collection.*

---

**Creating a list using ```list()```**

*Create a list using the built-in ```list()``` constructor.*

```python
numbers = list()
```

*This creates ```[]```*

*You can also convert an iterable into a list.*

```python
text = "Python"

letters = list(text)

print(letters)                  # ['P', 'y', 't', 'h', 'o', 'n']
```

---




























































































