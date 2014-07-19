##CHAPTER 1 Introduction to JavaScript
1. The __overwhelming__ majority of modern websites use JavaScript, and all modern web browsers—on desktops, game consoles, tablets, and smart phones—include JavaScript interpreters, making JavaScript the most __ubiquitous__ programming language in history.
2. today’s web browsers all include web developer tools that are __indispensable__ for debugging, experimenting, and learning.
3. x = "hello world"; // Strings of text in __quotation marks__.
4. Objects are enclosed in __curly braces__.
5. The syntax illustrated above for listing array elements within __square braces__ or mapping object property names to property values inside curly braces is known as an initializer expression
6. Operator/addition/substraction/multiplication/division/equality/inequality
7. "tw" is __alphabetically greater than__ "th"
8. The other __broad__ category of statement is control structures, such as conditionals and loops.
9. Chapter 9 is really the __climax__ of Part I, and the chapters that follow wrap up some loose ends and bring our exploration of the core language to a close.
##CHAPTER 2 Lexical Structure
1. The Unicode standard defines the preferred encoding for all characters and specifies a normalization procedure to convert text to a __canonical form__ suitable for comparisons.
2. Like many programming languages, JavaScript uses the __semicolon__ (;) to separate statements (see Chapter 5) from each other.
3. If you use a nonboolean value where a boolean is expected, JavaScript will convert __accordingly__.
4. Technically, however, - is the __unary negation operator__ (see Chap- ter 4) and is not part of the numeric literal syntax.
5. These include + for addition, - for subtraction, * for multiplica- tion, / for division, and % for modulo (remainder after division)
6. Although it is tempting to read all three operators “equals,” it may help to reduce confusion if you read “gets or is assigned” for =, “is equal to” for ==, and “is strictly equal to” for ===.
##CHAPTER 3 Types, Values, and Variables
1. JavaScript is a __lexically scoped__ language: the scope of a variable can be thought of as the set of source code lines for which the variable is defined.
##CHAPTER 5 Statements
1. Expressions with __side effects__, such as assignments and function invocations, can stand alone as statements, and when used this way they are known as expression state- ments.
2. Some (but not all) implementations enumerate array properties in numeric order rather than creation order, but they revert to creation order if the array is given other non-numeric properties as well or if the array is __sparse__ (i.e., if some array indexes are missing).
##CHAPTER 6 Objects
1. The ability to create a new object with an arbitrary prototype (put another way: the ability to create an __“heir”__ for any object) is a powerful one
2. This historical quirk of JavaScript is rectified in the strict mode of ECMAScript 5.
3. Other reasons to use accessor properties include __sanity checking__ of property writes and re- turning different values on each property read:
4. their writability is determined by the __presence or absence__ of a setter.
##CHAPTER 7 Arrays
1. JavaScript arrays may be __sparse__: the elements need not have contiguous indexes and there may be gaps.
2. Arrays that are sufficiently __sparse__ are typically implemented in a slower, more memory efficient way than __dense__ arrays are, and looking up elements in such an array will take about as much time as regular object property lookup.
3. The every() and some() methods are array __predicates__: they apply a predicate function you specify to the elements of the array, and then return true or false.
##CHAPTER 8 Functions
1. Some JavaScript implementations __relax this rule__.
2. And when a method can accept any number of arguments, you can use an __ellipsis__.
3. The name of a function is really __immaterial__;
4. it can sort any type of data into any __conceivable order__.
5. The following version of the counter() function is a __variation__ on code that appeared in §6.6, but it uses closures for private state rather than relying on a regular object property:
6. Like most modern programming languages, JavaScript uses __lexical scoping__. This means that functions are executed using the variable scope that was in effect when they were defined, not the variable scope that is in effect when they are invoked.
7. This combination of a function object and a scope (a set of variable bindings) in which the function’s variables are resolved is called a __closure__ in the computer science literature.
8. This kind of __dynamic alteration__ of existing methods is sometimes called “__monkey-patching__.”
9. The typeof operator is not __interoperable__ for callable RegExps. 
10. They are intended as a __mind-expanding exploration__ of the power of JavaScript’s functions, not as a prescription for good programming style
##CHAPTER 9 Classes and Modules
1. There are some __syntactic similarities__, and you can __emulate many features__ of “classical” classes in JavaScript, but it is best to understand up front that JavaScript’s classes and prototype-based inheritance mechanism are substantially different from the classes and class-based inheritance mechanism of Java and similar languages.
2. None of these techniques is __entirely satisfactory__, however, and the section concludes with a discussion of duck-typing, a programming philosophy that focuses on what an object can do (what methods it has) rather than what its class is.
3. One possible __workaround__ is to use the name of the constructor function as the class identifier rather than the function itself. 
4. Less frivolously, we might redesign our Range class so that instead of using the < and ++ operators, it uses the compareTo() and succ() (successor) methods of its endpoint objects.
5. Inconsistent notions of equality can be a __pernicious__ source of bugs, and it is best to make your equals() and compareTo() methods consistent.
6. We might want to create a Complex object initialized with a __radius__ and an __angle__ (polar coordinates) instead of __real and imaginary__ components, for example, or we might want to create a Set whose members are the elements of an array rather than the arguments passed to the constructor.
7. The universe of all possible modules is split __neatly__ into two kinds, those modules that are part of a specific application, and those modules that aren't.

