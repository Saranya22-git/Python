Hey everybody!!!

**PYTHON**

### **Table of Contents**
- [**Table of Contents**](#table-of-contents)
- [**Programming Fundamentals**](#programming-fundamentals)
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
  - [**Flowcharts**](#flowcharts)
    - [**Flowchart Basics**](#flowchart-basics)
    - [**Flowchart Symbols**](#flowchart-symbols)
    - [**Loops in Flowcharts**](#loops-in-flowcharts)
  - [**Pseudocode**](#pseudocode)
- [**Python Fundamentals**](#python-fundamentals)
  - [**Introduction to Python**](#introduction-to-python)
    - [**What is Python?**](#what-is-python)
    - [**History of Python**](#history-of-python)
    - [**Features of Python**](#features-of-python)
    - [**Applications of Python**](#applications-of-python)
    - [**Python Versions**](#python-versions)
    - [**Python Distributions**](#python-distributions)
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
    - [**Immutable Objects**](#immutable-objects)
    - [**Mutable Objects**](#mutable-objects)
  - [**Garbage Collection**](#garbage-collection)
  - [**is vs ==**](#is-vs-)
- [**Data Types in Python**](#data-types-in-python)
  - [**Fundamental Category data type**](#fundamental-category-data-type)
    - [**int**](#int)
      - [**Integer Immutability**](#integer-immutability)
      - [**Cached Integer**](#cached-integer)
      - [**Integer Caching**](#integer-caching-1)
      - [**Object Referencing**](#object-referencing)
      - [**Reference Assignment**](#reference-assignment-1)
      - [**Separate Object Creation**](#separate-object-creation)
      - [**Integer Caching OR Small Integer Caching and also related to Object Interning**](#integer-caching-or-small-integer-caching-and-also-related-to-object-interning)
      - [**Object Referencing OR Reference Assignment**](#object-referencing-or-reference-assignment)
      - [**No Integer Caching OR Separate Object Creation**](#no-integer-caching-or-separate-object-creation)
      - [**is vs ==**](#is-vs--1)
      - [**Garbage Collection Relation**](#garbage-collection-relation)
      - [**Type Casting to int**](#type-casting-to-int)
    - [**float**](#float)
      - [**Float Immutability**](#float-immutability)
      - [**Possible Float Object Reuse OR Interpreter Optimization**](#possible-float-object-reuse-or-interpreter-optimization)
      - [**Reference Assignment**](#reference-assignment-2)
      - [**Scientific Notation**](#scientific-notation)
      - [**Float precision issue**](#float-precision-issue)
      - [**is vs ==**](#is-vs--2)
      - [**Type casting to float**](#type-casting-to-float)
    - [**bool**](#bool)
      - [**Boolean Immutability**](#boolean-immutability)
      - [**Object Referencing OR Shared Object Referencing OR Singleton Boolean Objects OR Object Reuse**](#object-referencing-or-shared-object-referencing-or-singleton-boolean-objects-or-object-reuse)
      - [**Reference Assignment**](#reference-assignment-3)
      - [**bool-int relationship OR bool() type casting OR Shared object referencing**](#bool-int-relationship-or-bool-type-casting-or-shared-object-referencing)
      - [**Arithmetic operations on bool values return int results**](#arithmetic-operations-on-bool-values-return-int-results)
      - [**is vs ==**](#is-vs--3)
      - [**Type Casting to bool**](#type-casting-to-bool)
      - [**Truthy Values**](#truthy-values)
      - [**Falsy Values**](#falsy-values)
    - [**complex**](#complex)
      - [**Complex datatype representation**](#complex-datatype-representation)
      - [**Complex Immutability**](#complex-immutability)
      - [**Separate Object Creation OR Object Referencing**](#separate-object-creation-or-object-referencing)
      - [**Reference Assignment**](#reference-assignment-4)
      - [**Real and Imaginary parts**](#real-and-imaginary-parts)
      - [**Two-Argument complex()**](#two-argument-complex)
      - [**is vs ==**](#is-vs--4)
      - [**No ordering comparison**](#no-ordering-comparison)
      - [**Type Casting to complex**](#type-casting-to-complex)
      - [**Complex values do not support direct int/float conversion**](#complex-values-do-not-support-direct-intfloat-conversion)
      - [**Complex literals do not support spaces inside string conversion**](#complex-literals-do-not-support-spaces-inside-string-conversion)
  - [**Sequence Category data type**](#sequence-category-data-type)
    - [**str**](#str)
      - [**Types of str**](#types-of-str)
      - [**Immutability type**](#immutability-type)
      - [**Operations on str data**](#operations-on-str-data)
      - [**Concatenation**](#concatenation)
      - [**With Space**](#with-space)
      - [**String Repetition**](#string-repetition)
      - [**Membership Operators**](#membership-operators)
      - [**Escape Characters**](#escape-characters)
      - [**String memory behavior**](#string-memory-behavior)
      - [**String References**](#string-references)
      - [**String formatting**](#string-formatting)
      - [**Unicode \& ASCII Basics**](#unicode--ascii-basics)
      - [**is vs ==**](#is-vs--5)
      - [**Strings cannot be modified using indexing**](#strings-cannot-be-modified-using-indexing)
      - [**String Methods**](#string-methods)
    - [**List Category data type**](#list-category-data-type)
    - [**Set Category data type**](#set-category-data-type)
    - [**Dict Category data type**](#dict-category-data-type)
    - [**None Category data type**](#none-category-data-type)


---

### **Programming Fundamentals**

#### **Introduction to Programming**

##### **Programming**

**What is Programming?**

- *Programming is the process of giving instructions to a computer to perform a specific task.*
- *A computer is a machine. It cannot think, decide, or understand of human language on its own.*
- *It only follows instructions.*
- *Those instructions are called a program and the process of writing those instructions is called Programming.*

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
- **Mobile Apps:**
    
     **Example:** *WhatsApp, Instagram, Telegram.*  
- **Data Science:** *Used for Data Analysis, Machine Learning, AI.*
- **Automation:**
    
     **Example:** *Instead of manually renaming 1000 files, write a program. Computer does it automatically.* 
- **Game Development:**
    
     **Example:** *Minecraft, PUBG: Battlegrounds.* 
- **Cybersecurity:** *Programming is used to detect attacks, create security tools, analyze malware.*

---

**Characteristics of Programming**

*Good programming should be:*

- **Correct:** *Produces correct output.*
- **Efficient:** *Uses less time and memory.*
- **Readable:** *Easy for humans to understand.*
- **Maintainable:** *Easy to modify later.*
- **Reusable:** *Can be used again.*

---

##### **Program**

**What is a Program?**

- *A program is a collection of instructions written to perform a specific task.*
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

**Characteristics of a Program**

- **Set of instructions:** *A program contains multiple instructions.*
     
     **Example:**
    ```python
     a=10
     b=10
     print(a+b)
    ```
- **Performs a specific task:** 
    
    **Examples:**
     - *Calculator program*
     - *Attendance program*
     - *Banking program*
     - *Payroll program* 
- **Written in a Programming Language:**
    
    **Examples:**
     - *Python*
     - *C*
     - *Java*
     - *C++*
     - *JavaScript* 
- **Executed by Computer:** *Computer reads instructions one by one and executes them.*
   
---

**Types of Programs**

- **System Programs:** *Used to manage the computer.*

   **Example:** 
    - *Operating Systems*
    - *Device Drivers* 
- **Application Programs:** *Used by users.*
     
   **Examples:**
    - *Calculator*
    - *Browser*
    - *Music Player*

---

**Real-life examples of Programs**

- **ATM Software**
   - *Checks Balance*
   - *Withdraw Money*
   - *Deposit Money*
- **Instagram**
   - *Upload Photos*
   - *Like Posts*
   - *Send Messages* 
- **YouTube**
   - *Play Videos*
   - *Search Videos*
   - *Subscribe Channels* 

---

##### **Coding**

**What is Coding**

- *Coding is the process of converting logic, algorithms, or solutions into a programming language that a computer can understand and execute.*
  
**Example:** *Imagine your teacher asks **Find the sum of two numbers**.*

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

**Why Coding is important?**

*Coding helps us:*
- *Create software*
- *Build websites*
- *Develop apps*
- *Automate tasks*
- *Analyze data*
- *Build AI systems*

---

##### **Software vs Hardware**

**Hardware:** *Hardware refers to the physical components of a computer that you can see and touch.*

**Examples of Hardware:**

**Input devices**
- *Keyboard*
- *Mouse*
- *Webcam*
- *Scanner*

**Output devices**
- *Monitor*
- *Printer*
- *Speakers*

**Processing Devices**
- *CPU*
- *GPU*

**Storage Devices**
- *Hard Disk (HDD)*
- *SSD*
- *Pen Drive*
- *Memory Card*

**Software:** *Software is a collection of programs and instructions that tell hardware what to do.*

**Examples of Software:**
  - *Windows*
  - *Android*
  - *Instagram*
  - *YouTube*
  - *WhatsApp*
  - *Microsoft Excel*
  - *Google Chrome*

*Without software, hardware is useless.*
*Without hardware, software cannot run.*

---

**Relationship between Hardware and Software**

*Harware and Software work together.*

**Example:** *You click Instagram.*

**Hardware:**
- *Finger touches screen*
- *CPU processes action*
- *RAM stores data*

**Software:**
- *Instagram app opens*
- *Displays feed*
- *Loads messages*

*Both are required.*

---

**Difference between Hardware and Software**

| Hardware                | Software                          |
| ----------------------- | --------------------------------- |
| Physical components     | Programs and instructions         |
| Can be touched          | Cannot be touched                 |
| Manufactured            | Developed                         |
| Can wear out physically | Does not wear out physically      |
| Examples: CPU, Keyboard | Examples: Windows, Python, Chrome |

---

##### **Compiler**

**Problem:** *Computers understand only 0 and 1. This is called Machine Learning and Machine Code.*

**Example:** 

10110011
01010101
11100010

- *Humans cannot easily write programs in this form. So we use languages like Python, Java, C, C++. These are easier for humans.*
- *But the computer still understands only 0s and 1s. So we need a translator.*
- *That translator is called a **Compiler.***

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

*These languages mainly use compilers.*

---

**Advantages of Compiler**

- **Faster Execution:** *Code is already translated. So execution is fast.*
- **Error Checking:** *Compiler checks many errors before execution.*
- **Optimized Code:** *Compiler can improve performance.*

**Disadvantages of Compiler**

- **Compilation Time:** *Large programs take time to compile.*
- **Recompile Needed:** *Every change requires recompilation.*

---

##### **Interpreter**

**Interpreter:** *An Interpreter is a software program that translates and executes source code one line at a time.*

**Example:** *Imagine a translator helping two people talk.*

**Compiler Style:**
- *Person A speaks everything. Translator converts everything. Then Person B hears everything.*


**Interpreter Style:**
- *Person A speaks one sentence. Translator translates it. Person B hears it. Then next sentence. Then next sentence. This is how an interpreter works.*

---

**How Interpreter works:**

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

**Advantages of Interpreter**

- **Easy Debugging:** *Errors are reported immediately.*
- **No compilation setup:** *Program runs directly.*
- **Faster Development:** *Easy to test small changes.*
  
**Disadvantages of Interpreter:**

- **Slower Execution:** *Because translation happens during execution.*
- **Stops at first error:** *If an error occurs, execution stops.*

---

##### **High-Level Languages**

**High-Level Language:** *A High-Level Language(HLL) is a programming language that is easy for humans to read, write and understand. It uses english-like words and symbols instead of binary (0s and 1s).*

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
- *C#*
- *Ruby*
- *PHP*
- *JavaScript*
- *Swift*
- *Kotlin*

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

##### **Low-Level Language**

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

##### **Machine Language**

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

##### **Assembly Language**

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

##### **Procedural Programming**

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

##### **Object-Oriented Programming (OOP)**

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
- **Real-Worl Modeling:** *Objects represent real-world entities naturally.*

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

##### **Why Python?**

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

#### **Algorithm Fundamentals**

##### **Algorithm**

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

##### **Characteristics of a good algorithm**

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

##### **Writing Algorithms**

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

Start

↓

Input

↓

Process

↓

Output

↓

Stop

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

#### **Flowcharts**

##### **Flowchart Basics**

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

##### **Flowchart Symbols**

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

    Is A > B?

    ↓

    Yes → Display A

    No → Display B

    *Whenever you use if, if-else you'll use the Decision Symbol.*

5. **Flow Line**

    **Symbol:**

    ↓

    or

    ─►

    **Purpose:** *Shows the direction of execution. It connects all symbols together.*

6. **Connector**

    **Symbol:** 

    ○

    **Purpose:** *Used to connect different parts of a flowchart. Useful when a flowchart becomes large. Instead of drawing a long arrow, we use connectors.*

---

| Symbol         | Shape         | Purpose                  |
| -------------- | ------------- | ------------------------ |
| Terminator     | Oval          | Start / Stop             |
| Process        | Rectangle     | Calculation / Processing |
| Input / Output | Parallelogram | Read or Display Data     |
| Decision       | Diamond       | Yes / No, True / False   |
| Flow Line      | Arrow         | Direction of Flow        |
| Connector      | Circle        | Connect Different Parts  |

---

##### **Loops in Flowcharts**

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

#### **Pseudocode**

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

### **Python Fundamentals**

#### **Introduction to Python**

##### **What is Python?**

*Python is a high-level, interpreted, object-oriented, and general-purpose programming language known for its simple syntax, readability, and versatility. It is widely used in web development, automation, data analysis, artificial intelligence, machine learning and many other fields.*

---

##### **History of Python**

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

##### **Features of Python**

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

##### **Applications of Python**

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

##### **Python Versions**

**What is a Version?**

*A Version is a numbered release of software used to identify different releases, updates, improvements, bug fixes, and new features.*

---

**Major Python Versions:** *Python has 3 major versions:*

1. **Python 1.x**

   - *First major version of Python*
   - *Released in 1994*
   - *Outdated and no longer used for modern development*

2. **Python 2.x**
3. **Python 3.x**

***Version** is a numerical value(integer values) they are using for identification purpose.*
*Python Programming Language contains **3 types of versions**. They are*
1. **Python 1.x(outdated)** - *Here 1 is called major version. Here x represents 0 1 2 3 4 5 6 7 etc..., called Minor Version.*
2. **Python 2.x(outdated)** - *Python 2.x does not support Backward Compatability.*
   
   ***Backward Compatability** means New Versions of Software can still work with stuff made for older versions.*
3. **Python 3.x** - Here 3 is called Major Version. Here x represents 0 1 2 3 4 5 6 7 8 9 (7, 8, 9 are secured) 10 11(10,11 are bug fix) 12(Future release)

---

##### **Python Distributions**


**Distribution:** *A distribution is a customized version of python created to serve a specific need. Because Python is open source, developers can modify it and create their own distributions.*

  - **CPython:**
    - *CPython is the standard and most widely used implementation of Python.*
    - *When you download Python from python.org you are usually downloading CPython.* 
     
  - **Jython:** 
    - *Jython is Python implemented on the Java platform.*
    - *Allows Python code to work with Java libraries.*
    
  - **IronPython:** 
    - *IronPython is Python implemented for the .NET framework.*
    - *Allows Python to work with C#, .NET Libraries.* 
     
  - **MicroPython:** 
    - *MicroPython is a lightweight implementation of Python designed for Microcontrollers, Embedded Systems, IoT devices.* 
  
    **Why was it created?**

     - *Normal Python requires more memory, more processing power.*
     - *Small devices don't have enough resources. Example: Sensors, Smart Watches, IoT Boards. Need a smaller Python. So MicroPython was created.*
   
  - **Anaconda:** *Very important for data science. Includes NumPy, Pandas, Jupyter Notebook.*
   
  - **Stackless Python:** 
    - *Stackless Python is a modified version of Python designed for Concurrency, Parallel Tasks, High Performance Applications.*
  

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

##### **Immutable Objects** 

- *Objects whose values cannot be changed after creation.*

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

##### **Mutable Objects** 

- *Objects whose values can be modified after creation.*

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

###### **Integer Immutability**

*Once created, integer objects cannot be changed.*

```python
a=10
print(a,id(a))            # 10 140716343600536

a=a+1
print(a,id(a))            # 11 140716343600568
```
*IDs change because new integer object created.*

---

###### **Cached Integer** 

- *The actual cached number itself.*

**Example:** 34

###### **Integer Caching** 

- *Python reuses small integers(-5 to 256).*

**Example:** a=34
             b=34
 
###### **Object Referencing** 

- *Whenever a variable points to an object.*

**Example:** a=10
             Memory a->10

###### **Reference Assignment** 

- *When one variable gets reference from another variable.*

**Example:** a=12345
             b=a
       
###### **Separate Object Creation**

**Example:** a=12345
             b=12345

--- 

###### **Integer Caching OR Small Integer Caching and also related to Object Interning**

```python
a=34
b=34
print(a,id(a))       # 34 140733555255448
print(b,id(b))       # 34 140733555255448
```

- *Both variables point to SAME object.*
- *This concept is called Integer Caching OR Small Integer Caching and also related to Object Interning.*

---

###### **Object Referencing OR Reference Assignment**

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

###### **No Integer Caching OR Separate Object Creation** 

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

###### **is vs ==**

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

###### **Garbage Collection Relation**

```python
a=10
a=100
print(a)        # 100
```

- *Old reference removed.*
- *If no references exist, the garbage collector cleans memory.*

---

###### **Type Casting to int**

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

###### **Float Immutability**

- *IDs change because float objects are immutable and a new object is created after modification.*

```python
a=12.5
print(a,id(a))          # 12.5 2707329680496

a=a+1
print(a,id(a))          # 13.5 2707329680208
```

---

###### **Possible Float Object Reuse OR Interpreter Optimization**

- *Python does not officially cache float values like integers.*
- *Same float IDs may occur due to interpreter optimization or object reuse behavior.*

```python
a=10.98
b=10.98

print(id(a))          # 1959594296688
print(id(b))          # 1959600251888
```

---

###### **Reference Assignment**

```python
a=2.34
b=a
print(a,type(a),id(a))          # 2.34 <class 'float'> 2870877520720
print(b,type(b),id(b))          # 2.34 <class 'float'> 2870877520720
```

---

###### **Scientific Notation**

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

###### **Float precision issue**

- *Float values are internally stored in binary format.*
- *Some decimal values cannot be represented exactly in binary.*
- *Therefore small precision errors may occur.*

```python
print(0.1+0.2)              # 0.30000000000000004
```

---

###### **is vs ==**

```python
a=12.34
b=12.34

print(a==b)                 # True
print(a is b)               # False
```

---

###### **Type casting to float**

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

###### **Boolean Immutability**

```python
a=True
print(a,id(a))          # True 140728191798016

a=False
print(a,id(a))          # False 140728191798048
```

---

###### **Object Referencing OR Shared Object Referencing OR Singleton Boolean Objects OR Object Reuse**

```python
a=True
b=True

print(a,id(a))            # True 140728191798016
print(b,id(b))            # True 140728191798016
```

---

###### **Reference Assignment**

```python
a=True
b=a

print(a,id(a))            # True 140728191798016
print(b,id(b))            # True 140728191798016
```

---

###### **bool-int relationship OR bool() type casting OR Shared object referencing**

```python
a=True
b=bool(1)

print(a,id(a))            # True 140728191798016
print(b,id(b))            # True 140728191798016
```

---

###### **Arithmetic operations on bool values return int results**

```python
a=True+False
b=bool(1+0)

print(a,id(a))             # 1 140728192705656
print(b,id(b))             # True 140728191798016
```

---

###### **is vs ==**

```python
a=True
b=1

print(a==b)           # True
print(a is b)         # False
```

---

###### **Type Casting to bool**

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

###### **Truthy Values**

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

###### **Falsy Values**

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

###### **Complex datatype representation**

```python
a=2+5j
print(a,type(a))                  # (2+5j) <class 'complex'>
```

---

###### **Complex Immutability**

```python
a=2+5j
print(a,id(a),type(a))              # (2+5j) 2023119824368 <class 'complex'>

a=a+1
print(a,id(a),type(a))              # (3+5j) 2023119824976 <class 'complex'>
```

###### **Separate Object Creation OR Object Referencing**

```python
a=3+3j
b=3+3j

print(a,id(a))                # (3+3j) 2023119820784
print(b,id(b))                # (3+3j) 2023119824944              
```

---

###### **Reference Assignment**

```python
a=3+3j
b=a

print(a,id(a))                # (3+3j) 2023119824976
print(b,id(b))                # (3+3j) 2023119824976
```

---

###### **Real and Imaginary parts**

```python
a=2+3j

print(a.real)             # 2.0
print(a.imag)             # 3.0
```

---

###### **Two-Argument complex()**

```python
complex(real, imaginary)

print(complex(2,9))         # (2+9j)
```

---

###### **is vs ==**

```python
a=2+3j
b=2+3j


print(a==b)           # True
print(a is b)         # False
```

---

###### **No ordering comparison**

```python
(2+3j) >= (2+3j)
```

- *Complex numbers cannot use: < > >= <=*
  
---

###### **Type Casting to complex**

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

###### **Complex values do not support direct int/float conversion**

```python
int(2+3j)                   # TypeError
float(2+7j)                 # TypeError 
```

---

###### **Complex literals do not support spaces inside string conversion**

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

###### **Types of str**

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

###### **Immutability type**

  ```python
   name="Python"

   print(name,id(name))             # Python 2902389817632

   name="Python"+'123'

   print(name,id(name))             # Python123 2902490339312
   ```

---

###### **Operations on str data**

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

---

###### **Concatenation**

*Joining strings.*

  ```python
   a="Hello"
   b="Python"

   print(a+b)           # HelloPython
  ```

---

###### **With Space**

  ```python
    a="Hello"
    b="Python"

    print(a+" "+b)      # Hello Python
    print(a+""+b)       # HelloPython
  ```

---

###### **String Repetition**

   ```python
    print("Python"*3)    # PythonPythonPython
  ```

---

###### **Membership Operators**

   ```python
   a="Python"

   print("P" in a)        # True
   print('z' in a)        # False
   print('p' in a)        # False
   ```

---

###### **Escape Characters**

*Used to insert special characters.*

  **Common Escape Characters**

      | Escape | Meaning      |
      | ------ | ------------ |
      | `\n`   | new line     |
      | `\t`   | tab          |
      | `\'`   | single quote |
      | `\"`   | double quote |

   **Example:**

   ```python
   print("Hello\nPython")         /* Hello
                                    Python */
   print("Hello\tPython")         # Hello Python
                      
   ```

---

###### **String memory behavior**

  - *Same IDs due to string object reuse/interning.*
  - *Python sometimes reuses string objects for optimization.*
   
   ```python
    a="sony"
    b="sony"

    print(id(a))              # 2081418619248
    print(id(a))              # 2081418619248
   ```

---

###### **String References**

 ```python
  a="sony"
  b=a

  print(id(a))                # 2081418619248
  print(id(b))                # 2081418619248
```

###### **String formatting**

 ```python
   name="Saranya"

  print(f"My name is {name}")
  print("My name is {}".format(name))
  print("My name is %s"%(name))
 ```

- *This is called f-string formatting.*

---

###### **Unicode & ASCII Basics**

**ASCII:** 
- *American Standard Code for Information Interchange.*
- *Every character has numeric code.*
- **Example:**
  ```python
   print(ord("A"))            # 65
  ``` 

**Unicode:**
- **Example:**
  ```python
   print(ord("🫠"))           # 129760
  ``` 

---

###### **is vs ==**

 ```python
  a="Python"
  b="Python"

  print(a==b)                   # True
  print(a is b)                 # True
 ```

---

###### **Strings cannot be modified using indexing**

  ```python
    a="Saranya"

    a[0]="J"                # TypeError: 'str' object does not support item assignment
  ```
 
 - *Because str is immutable.*

 **Correct way:** 
   ```python

    a="Saranya" 

    a="J"+a[1:]
    print(a)                # Jaranya              
   ```

###### **String Methods**

**upper()**
**lower()**
**replace()**
**split()**



##### **List Category data type**
##### **Set Category data type**
##### **Dict Category data type**
##### **None Category data type**


