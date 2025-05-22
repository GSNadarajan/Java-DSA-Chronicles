# DSA Journey - Day 1

## Types of Programming Languages

Programming languages can be categorized into three main paradigms:

### 1. Procedural
- Specifies a series of well-structured steps and procedures to compose a program
- Contains a systematic order of statements, functions, and commands to complete a task
- Examples: C, Fortran

### 2. Functional
- Programs are written only in pure functions (never modify variables, only create new ones as output)
- Used in situations where we perform lots of different operations on the same set of data, like ML
- Utilizes first-class functions (functions that can be assigned to variables, passed as arguments, returned from other functions)
- Examples: Haskell, Scala, Clojure

### 3. Object-Oriented
- Revolves around objects where code and data are combined
- Code + Data = Object
- Developed to make it easier to develop, debug, reuse, and maintain software
- Examples: Java, C++, Python

## Static vs Dynamic Languages

### Static Languages
- Perform type checking at compile time
- Errors will show at compile time
- Must declare datatype before you use it
- More control over code execution
- Examples: Java, C, C++

### Dynamic Languages
- Perform type checking at runtime
- Errors might not show until program is run
- No need to declare datatype of variables
- Saves time in writing code but might give errors at runtime
- Examples: JavaScript, Python, Ruby

## Memory Management: Stack vs Heap

### Stack
- Stores primitive data types and references
- Variables declared inside functions are allocated on stack
- Memory allocation and deallocation is automatic
- Fast access

### Heap
- Stores objects in memory
- Reference variables (like 'a') on stack point to objects in heap
- Example: When `a = 10` is written in an object-oriented language, 'a' is a reference in stack that points to an integer object with value 10 in the heap

## Learning Progress
Started following Kunal Kushwaha's DSA course on YouTube. Day 1 covered programming language fundamentals and memory concepts.

## Next Steps
- Continue with basic Java/programming concepts
- Learn about time and space complexity
- Explore basic data structures