# 22 June 2019 Javascript Notes   
## Chapter 2 Basic Javascript Instructions  
- Statement  
  * A scipt is a series of instructions, computer follows one-by-one. Each step (or instruction) is known as a **statement**  
    - Statements should end with a semicolon  
  * Javascript is **CASE SENSITIVE**  
  * Statements= Instructions, each one should start on a new line  
    - This makes code easier to read and follow  
  * Semicolon tells Javascript interpreter when a step is over, meaning it should move to the next step  
  * Statements can be organized into code blocks  
    - Some are surrounded by curly braces; these are known as **code blocks**  
      * Curly brace is not followed by a semicolon  
- Comments  
  * Write comments to explain what your code does 
  * Make code easier to read and understand  
  * **Multi-line** comments start with /* and ending with characters */  
    - Anything between those characters is not read by JavaScript  
    - Often used to describe how script works  
    - Prevent a section of script from running when tested  
  * **Single-line** comments are anything that follows two forward slashes // 
    - Used for short description of what code is doing
  * Help you if you come back to your code after several days or months  
  * Help those new to your code  

### Variable  
- **Variables** "Named-Storage" for data  
- Before you use a variable, you must announce that you want to use it  
  * Creating a variable and giving it a name  
  * Programmers say that you **delcare** the variable  

Variable Keyword | Variable Name
------ | -------
var | quantity;   

- Once created, you can tell it what info you want stored  
- Programmers say that you **assign a value** to a variable 

i.e. quantity = 3;
quantity-> variable name  
= -> assignment operator  
3; -> variable value  

## How to Use Objects and Methods  

document.write('Good afternoon!');
document -> object  
. -> member operator  
write() -> method