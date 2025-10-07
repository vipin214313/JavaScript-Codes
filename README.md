#### JavaScript-Codes  #####
Here I am Uploading JavaScript Practicles codes

javaScript is a programming language it is used for creating dynamic content on website . it is lightweight , cross-platform, single threaded programming language.

it is created by breanden eiach in 1995. he is a engineers of netscape .firstly it name is LiveScript but later he Changed to JavaScript.

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
🔹 Non-Primitive (Reference) Data Types:
Non-primitive data types, also known as reference types, are objects and derived data types. They can store collections of values or more complex entities.
1-object
2-array
3-function
