#### JavaScript practice projects and exercises #####

javaScript is a programming language it is used for creating dynamic content on website . it is lightweight , cross-platform, single threaded programming language.

it was Created by Brendan Eich in 1995. he is a engineers of netscape .firstly it name is LiveScript but later he Changed to JavaScript.

why JavaScript Learn:
1-Easy to learn
2-versitile 
3-clent-side 
4-server-side
5-game development 
6-heigh demand in industry

how to add javascript:
1-inline style
2-internal(within head or body tag)  <script></script>
3-externals js   <script src="">

Display property:
1-innerHtml Property
2-console.log
3-document.write
4-alert()
5-prompt()

creating examples :here creating the clock and date examples and simple login fom user alert and add itoms 
comment in js:
1-single line comment //
2-multiline comment /*... */

variables:a variables is a conatiners that stores data values.it is act as a symbol for memory location.

📌 Types of JavaScript Variables:
    1. Local Variable
    2-Global Variable

🟨 1. JavaScript Local Variable
A local variable is declared inside a function or block {} and it is accessible only within that function or block only.

✅ Explanation:
    • var function ke andar declare kiya → sirf function ke andar accessible.
    • Function ke bahar access karoge → error.
✅ Explanation:
    • var block scope ko ignore karta hai, par function scope follow karta hai.
    • Block ke bahar bhi function ke andar accessible hai.
✅ Explanation:
    • let sirf block ke andar accessible hai.
    • Block ke bahar access karoge → error.
            ○ Agar let ya const function ke andar ke kisi block {} me declare kiya gaya hai,
    to wo sirf us block ke andar hi accessible hota hai.Block ke bahar (chahe function ke andar hi kyu na ho) access karoge → ❌ Error milega.  
✅ Explanation:
    • const bhi block-scoped hai, bilkul let ki tarah.
    • Value constant hai, aur block ke bahar access nahi hoti.
✅ Explanation:
    • Agar var,let ,const  function ke bahar declare ho → global variable ban jaata hai.
    • Block ke andar ya bahar, dono jagah accessible hai.
    • Farq ye hai:
        • var → window object me add hota hai ✅
let aur const → window object me nahi hote ❌

🟩 2. JavaScript Global Variable
A global variable Declared outside any function  or Block  and it  is accessible everywhere in your program: inside functions, outside functions, and in all blocks.  

Notes:
🔹 Global Variables:Agar koi variable (var, let, const) function ke bahar declare hota hai, to wo global scope me hota hai aur kahin se bhi access kiya ja sakta hai (function ke andar aur block ke andar dono jagah se).

🔹 Detailed Points
1️⃣ var
    • Agar var function ke bahar likha hai → global ban jaata hai.
    • Ye function aur block dono ke andar accessible hota hai.
    • window object (browser) ke sath attach hota hai.
var a = 10;
console.log(window.a); // ✅ 10

2️⃣ let
    • Agar let function ke bahar likha hai → global scope me hota hai,
par window object pe attach nahi hota.
    • Ye bhi function aur block ke andar accessible hota hai.
3️⃣ const
    • const bhi agar function ke bahar likha hai → global variable ban jaata hai.
    • Function aur block ke andar accessible hota hai.
    • Lekin window object pe attach nahi hota.
✅ Key Points
    1. var → global + attached to window object
    2. let & const → global but NOT attached to window object
    3. All three (var, let, const) → function aur block ke andar accessible hote hain,
agar unhe function ke bahar (global level par) declare kiya gaya ho.
🧠 Final Conclusion (Simple Line)
    ✅ Agar var, let, const ko function/block ke bahar declare karte ho →
    ye sabhi function aur block ke andar accessible hote hain.
    🔸 बस फर्क ये है:
    var window object pe attach hota hai,
let aur const window object pe attach nahi hote. 

Data types:
JavaScript is a dynamic type language → You don’t need to declare the type of variable (JS decides automatically).  

Primitive Data Types
The predefined data types provided by JavaScript language are known as primitive data types. Primitive data types are also known as in-built data types.
1-number
2-string
3-Boolean
4-null
5-undefined
6-Symbol
7-BigInt

# JavaScript Data Types & Real-World Examples

This document contains explanations and practical examples of JavaScript data types, along with real-life project scenarios to practice and understand their usage.

---

## 🔹 1. Primitive Data Types

Primitive data types are immutable and directly store values.

| Type      | Example                                 | Description                    |
|----------|-----------------------------------------|--------------------------------|
| String   | `let name = "Alice";`                   | Text values                    |
| Number   | `let age = 30;`                         | Numeric values                 |
| Boolean  | `let isMember = true;`                  | True / False                   |
| Undefined | `let address;`                          | Declared but not assigned      |
| Null     | `let contact = null;`                   | Empty value                     |
| Symbol   | `let userSymbol = Symbol("id");`       | Unique identifier               |
| BigInt   | `let bigNumber = 12345678901234567890n;` | Very large integers             |

**Example:**
```javascript
let name = "Alice";               // String
let age = 30;                     // Number
let isMember = true;              // Boolean
let address;                      // Undefined
let contact = null;               // Null
let userSymbol = Symbol("id");    // Symbol
let bigNumber = 1234567890123456789012345678901234567890n;  // BigInt

console.log(name, age, isMember, address, contact, userSymbol, bigNumber);

🔹 Non-Primitive (Reference) Data Types:
Non-primitive data types, also known as reference types, are objects and derived data types. They can store collections of values or more complex entities.
1-object
2-array
3-function

Variables:
"A JavaScript variable is a container that stores data values. It acts as a symbolic name for a memory location. Variables are used to hold data that can be accessed or manipulated in the program."  
4. Types of Variables in JavaScript
In modern JavaScript, we mainly have three types of variable declarations:
Type	Scope / Usage	Can be Reassigned?	Example
var	Function-scoped, can be redeclared	Yes	var age = 25;
let	Block-scoped, cannot be redeclared	Yes	let score = 50;
const	Block-scoped, cannot be redeclared	No (constant)	const pi = 3.14;

Templat Literals Key Features
    1. Backticks (`) Instead of Quotes (' or "):
        ○ Template literals are enclosed in backticks (`) instead of single (') or double (") quotes.
        
        let name = "Vipin";
console.log(`Hello, ${name}!`); // Output: Hello, Vipin!

🔹 Proper Definition of Closure
"A closure is the combination of a function bundled together (enclosed) with references to its surrounding state (the lexical environment)". In other words, a closure gives a function access to its outer scope. In JavaScript, closures are created every time a function is created, at function creation time.

Operators:JavaScript operators are symbols or keywords that perform operations on operands (values, variables, or expressions). Operators can be classified into:
    1. Arithmetic
    2. Assignment
    3. Comparison
    4. Logical
    5. Bitwise
    6. Ternary
    7. Comma
    8. Unary
    9. Relational
    10. BigInt
String

conditional statement:
JavaScript conditional statements execute code based on true/false conditions.  
Conditional Statement	Description
if	Executes a block if the condition is true
else	Executes a block if the preceding if is false
else if	Tests multiple alternative conditions
switch	Executes a block based on expression value
Ternary ?:	Short-hand single-line if-else
Nested if-else	Multiple hierarchical conditions
🟦 JavaScript Loops 
Loops in JavaScript are used to repeat a block of code as long as a condition is true. They are essential for handling repetitive tasks efficiently.

🎯 Why Loops Are Used
    • To reduce code repetition
    • To perform repeated tasks automatically
    • To iterate over arrays or objects
 
🧠 Types of Loops in JavaScript
Type	Description
for	Runs a block of code a specific number of times
while	Runs while a condition is true
do...while	Runs at least once, then checks condition
for...in	Loops through object properties
for...of	Loops through iterable values (arrays, strings, etc.)

Object:- Object is a collection of property(state/data) and method(behaviours),where propert define the object state and method describe the object behaviour.
in object data are stored key values pair.

how many types to creat object
1-object litrel:simple inside curly bracess{} in the form of key value pair.
2-new object keywors:-slightly more verbose but usefull for creating step by step object.
3-constructors object:it is creating create multipule similar objects efficiently.each object is set each and own property and method and you can changed it laters.
4-object.create():it is inbuild object wich are used to create a new object and set the property se manuals.




