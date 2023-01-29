##  JavaScript Practice
### __Basic JavaScript:__
---

#### Q:1 জাভাস্ক্রিপ্ট কি জিনিস এইটা কি জানো?

<p>JavaScript is a high-level, often just-in-time compiled language that conforms to the ECMAScript standard.It has dynamic typing, prototype-based object-orientation, and first-class functions. It is multi-paradigm, supporting event-driven, functional, and imperative programming styles. It has application programming interfaces (APIs) for working with text, dates, regular expressions, standard data structures, and the Document Object Model (DOM). </p>

#### Q:2 জাভাস্ক্রিপ্ট কিভাবে কাজ করে সেটা কি জানো?
<p>JS is a single threaded and single concurrent programming language which means it can handle one task at a time or, in other words, a piece of code at a time. It’s an interpreted programming language, and like most scripting languages, it uses dynamic typing, where type safety is verified at the runtime. JS is considered a lightweight programming language and one of the many reasons is that it does not have any variable types, unlike other languages. It has a very small memory footprint and is easily implemented. This is important especially for porting.</p>

#### Q:3 ভেরিয়েবল কি জিনিস?
<p>Js variables are containers for storing data. In another defination A JavaScript variable is simply a name of storage location.</p>

#### Q:4 ভেরিয়েবল কিভাবে ডিক্লেয়ার করে? 

##### __We need 5 things to declare a variables:__ 

``` js
var courseName = "Web Development";
let age = 95;
const name = "Mohon Saha";

```

 1. Keyword
 2. Variable name
 3. Assignment operator(=)
 4. Value
 5. Semicolon

<p>

 - Variables can be defined using let keyword. Variables defined without let or var keyword become global variables.
 - Variables should be initialized before accessing it. Unassigned variable has value undefined.
 - JavaScript is a loosely-typed language, so a variable can store any type value.
 - Variables can have local or global scope. Local variables cannot be accessed out of the function where they are declared, whereas the global variables can be accessed from anywhere.</p>

 #### Q:5 ভেরিয়েবল এর মান কিভাবে চেইঞ্জ করে বা আপডেট করে।

 ```js
var x = 95;
x = 900;
console.log(x);
// new value of x is 900 
 ```


 #### Q:6 কি কি ধরণের ভেরিয়েবল হয়।

 - String
 - Number
 - Booleans
 - Arrays
 - Objects
 - Undefined

 #### Q:7 জাভাস্ক্রিপ এ primitive and non primitive data types কি কি ? উদাহরণ হিসেবে বলো। 

<p> The Primitive Data types in JavaScript: 

  -  Number
  - String
  - Boolean
  -  Undefined
  -  Null
  -  Symbol

The Non-Primitive data type :
  - Object
  - Array
  - Function

  ![alt](preview.jpg)
 </p>

 #### Q:8 ভেরিয়েবল এর নাম কিভাবে কিভাবে ডিক্লেয়ার করতে হয়। কোন কোন জিনিস নাম এ লেখা যাবে না। অর্থাৎ Variable এর naming convention সম্পর্কে বলো।

 1. Variable name can not be any keywork.
 2. variable name has to be in one word. No space is suitable.
 3. Variable name can not have any quotation.
 4. Varuable name can not starts with a number but it can ends with a numkber.

 ```js
var const = 99;  // It's Wrong
var my name = "Mohon Saha"; // It's Wrong
var "jharkar vai" = "Ki ase jibone";  // It's Wrong
var 99club = 989; // It's Wrong

 ```

 <p> How we can use long name: </p>
 
 - Use Underscore
 - Use camelcase

 ```js
 let myName = "Mohon Saha"  // Currect
 const jhankar_vai = "Ki ase jibone"  // Currect
 var club95 = 98; // Currect

 ```

 

