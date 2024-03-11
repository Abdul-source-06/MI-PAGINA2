### 1- Summarize the 5 generations of programming languages. Write one sentence to explain each one of them. Add at least one example in each generation.

- First-generation languages consist of machine code written in binary.
Example: The binary code
- Second-generation languages are assembly languages that use symbolic names.
Example: Assembly language
- Third-generation languages are high-level programming languages that use English-like syntax.
Example: C
- Fourth-generation languages are designed for specific applications and are often used for database management.
Example: SQL
- Fifth-generation languages are designed to make programming more intuitive and are often associated with artificial intelligence.
Example: Haskell 
### 2- Choose 2 programming languages and make a comparison table. Include: year of publication, generation, author(s), owner, main features, common use cases, paradigms / types of programming supported, code examples, and other information that you find interesting.

| TABLE                       | Python                        | Java                          |
|---------------------------------|-------------------------------|-------------------------------|
| **Year of Publication**         | 1991                          | 1995                          |
| **Generation**                  | High-level, scripting         | High-level, object-oriented   |
| **Author(s)**                   | Guido van Rossum              | James Gosling                 |
| **Owner**                       | Python Software Foundation    | Oracle Corporation (formerly Sun Microsystems) |
| **Main Features**               | Readability, simplicity, extensive standard library | Platform independence, strong typing, extensive libraries |
| **Common Use Cases**            | Web development, data analysis, artificial intelligence, scientific computing | Web applications, mobile apps, enterprise applications, Android development |
| **Paradigms/Types of Programming Supported** | Multi-paradigm: procedural, object-oriented, functional, scripting | Object-oriented, imperative, functional |
             

### 3- Explain and compare *machine language* and *assembly language*. Include a code example of each.
- Machine language is the lowest-level programming language that a computer can understand directly. Example: 10110000 01100001
- Assembly language is a low-level human-readable language that is a symbolic representation of machine language. Example: mov al, 61


| Comparison                      | Machine Language              | Assembly Language             |
|---------------------------------|------------------------------|------------------------------|
| **Representation**              | Binary code, consisting of 0s and 1s | Mnemonics (human-readable symbols) representing machine code instructions |
| **Level of Abstraction**        | Lowest level of programming; direct hardware instructions | Low-level programming, providing a bridge between machine language and high-level languages |
| **Readability**                 | Not human-readable, extremely complex | Human-readable, easier to understand than machine language |
| **Programming Difficulty**      | Extremely difficult and error-prone | Less difficult than machine language, but still challenging |
| **Portability**                 | Non-portable; specific to a particular CPU or architecture | Somewhat portable, but still tied to a specific architecture |
| **Examples**   |      00000000 01001001 11000000 |  Add 1 to the value in register AL INC AL; Halt the CPU HLT|


### 4-  Find information and explain declarative programming and imperative programming. What are the differences? Why are these the 2 main categories of programming paradigms? Find code examples written in each fashion.

- Declarative Programming: Declarative programming focuses on describing what you want to achieve without specifying the exact steps or operations to achieve it. Example: SQL.
- Imperative Programming: Imperative programming provides explicit instructions and control flow to achieve a task. Examples: C, C++, Java, and Python.
     - Differences: 



 | Characteristic                 | Declarative Programming                                       | Imperative Programming                                       |
|----------------------------------------------------|--------------------------------------------------------------|--------------------------------------------------------------|
| **Abstraction Level**                               | Abstracts implementation details, focusing on outcomes.    | Provides detailed, step-by-step instructions.               |
| **Control Flow**                                    | Order of execution is often determined by the system.     | Explicitly controls flow with loops and conditionals.       |
| **Readability**                                     | Often more readable, closer to natural language.          | Can be harder to read due to lower-level nature.            |
| **Flexibility**                                     | Abstracts away details for simplicity.                    | Offers fine-grained control, more flexibility.              |
| **Domain**                                          | Used in scenarios where "what" is more important.         | Common in systems programming, application development.     |

- Declarative programming simplifies the task by stating what you want,  while imperative programming provides step-by-step instructions to achieve the same result. The choice between these paradigms depends on the problem domain and the level of control and abstraction required.

### 5- Make a comparison table between *Procedural Programming*, *Functional Programming* and *Object-oriented Programming*. For each of them consider if it's Declarative or Imperative. Find one code example of each kind. Find one programming language that favors each paradigm.

| Paradigm                  | Declarative/Imperative | Main Characteristics                               | Example Code                                  |   |
|---------------------------|------------------------|---------------------------------------------------|-----------------------------------------------|------------------------|
| **Procedural Programming** | Imperative             | - Focuses on procedures (functions) to perform tasks.<br>- Uses a top-down approach with clear step-by-step instructions.<br>- State is often shared and mutable. | 

### **Example:** 

#include <stdio.h>

void greet() {

    printf("Hello, World!\n");
}

int main() {
    
    greet();
    return 0;
}

### **Functional Programming example:**

add :: Int -> Int -> Int

add a b = a + b

main :: IO ()

main = do

  let x = 5
      y = 3

  let result = add x y

  putStrLn $ "The result is " ++ show result


### **Object-oriented Programming example:**

class Person {

  private String name;

  public Person(String name) {

     this.name = name;

  }

  public void greet() {

    System.out.println("Hello, my name is " + name);
  }

}

public class Main {

  public static void main(String[] args) {

    Person person = new Person("Alice");
    person.greet();
  }

}

