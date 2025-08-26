https://grok.com/chat/f98cf84d-3690-4efc-ac45-10a738a74c63

# JavaScript Overview: Categories and References

## Basics & Syntax
Variables (var, let, const), Data Types (string, number, boolean, object, null, undefined, symbol, bigint), Operators (arithmetic: +, -, , /, %; assignment: =, +=, -=; comparison: ==, ===, !=, >, <; logical: &&, ||, !; bitwise: &, |, ^, ~, <<, >>), Statements (expressions, declarations), Syntax Rules (case sensitivity, semicolons), Comments (// single-line, / multi-line */), Strict Mode ('use strict'), Hoisting, this Keyword, Typeof Operator, Type Conversion (String(), Number(), Boolean()), Reserved Words (e.g., break, case, class).

## Control Flow
If/Else Statements, Switch Statements, Loops (for, for...in, for...of, while, do...while), Break and Continue, Labels for Loops.

## Functions
Function Declarations, Function Expressions, Arrow Functions (=>), Parameters and Arguments (default parameters, rest parameters ...args), Return Statement, Function Scope, Closures, IIFE (Immediately Invoked Function Expressions), Callback Functions, Higher-Order Functions.

## Objects
Object Literals ({key: value}), Constructors (new Object()), Properties (access via dot notation or brackets), Methods (functions as properties), Prototypes (proto, Object.prototype), Inheritance (Object.create()), Object Methods (Object.assign(), Object.keys(), Object.values(), Object.entries(), Object.freeze(), Object.seal(), Object.is()).

## Classes
Class Declarations (class MyClass {}), Constructors (constructor()), Methods (instance and static), Inheritance (extends, super()), Getters/Setters (get/set).

## Arrays
Array Creation (new Array(), []), Array Methods (push(), pop(), shift(), unshift(), splice(), slice(), concat(), join(), indexOf(), lastIndexOf(), includes(), find(), findIndex(), filter(), map(), reduce(), reduceRight(), every(), some(), sort(), reverse(), forEach(), flat(), flatMap()), Array Properties (length), Array Iteration (for...of, entries(), keys(), values()).

## Strings
String Creation ('' or ""), String Methods (charAt(), charCodeAt(), concat(), endsWith(), includes(), indexOf(), lastIndexOf(), match(), replace(), search(), slice(), split(), startsWith(), substring(), toLowerCase(), toUpperCase(), trim(), padStart(), padEnd(), repeat()), Template Literals (backticks ${expression}), String Properties (length).

## Numbers & Math
Number Methods (toFixed(), toExponential(), toPrecision(), toString(), valueOf(), parseInt(), parseFloat(), isNaN(), isFinite()), Number Properties (MAX_VALUE, MIN_VALUE, POSITIVE_INFINITY), BigInt (creation with n suffix, methods like toString()), Math Object Methods (abs(), ceil(), floor(), round(), max(), min(), pow(), sqrt(), random(), sin(), cos(), tan(), log(), exp(), PI, E).

## Booleans
Boolean Creation (true/false, Boolean()), Comparisons (== vs ===), Logical Operators.

## Dates
Date Creation (new Date()), Date Methods (getDate(), getDay(), getFullYear(), getHours(), getMinutes(), getSeconds(), getMilliseconds(), getTime(), getUTCDate() and similar UTC variants, setDate(), setFullYear(), etc.), Date Formats (toString(), toUTCString(), toISOString(), toJSON()), Parsing (Date.parse()).

## Collections
Sets (new Set(), add(), delete(), has(), clear(), size, forEach(), values()), Maps (new Map(), set(), get(), has(), delete(), clear(), size, forEach(), keys(), values(), entries()).

## Error Handling
Try/Catch/Finally, Throw Statement, Error Types (Error, SyntaxError, ReferenceError, TypeError, RangeError, EvalError, URIError).

## Asynchronous Programming
Callbacks, Promises (new Promise(), then(), catch(), finally(), Promise.all(), Promise.race(), Promise.resolve(), Promise.reject()), Async/Await (async function, await), Timers (setTimeout(), setInterval(), clearTimeout(), clearInterval()).

## Modules
Export (export default, export named), Import (import default, import {named}), Dynamic Imports (import()).

## JSON
JSON Methods (JSON.stringify(), JSON.parse()).

## Regular Expressions (RegExp)
RegExp Creation (/pattern/flags, new RegExp()), Methods (exec(), test(), match(), matchAll(), replace(), search(), split()), Flags (g, i, m, s, u, y), Patterns (metacharacters like \d, \w, ., *, +, ?, [], [^], (),

## DOM Manipulation
Document Methods (getElementById(), getElementsByClassName(), getElementsByTagName(), querySelector(), querySelectorAll(), createElement(), appendChild(), removeChild(), replaceChild(), innerHTML, textContent, style), Node Properties (nodeType, nodeName, parentNode, childNodes, firstChild, lastChild).

## Events
Event Handlers (addEventListener(), removeEventListener()), Event Types (click, dblclick, mouseover, keydown, load, submit, change), Event Object (target, type, preventDefault(), stopPropagation()).

## Browser APIs
Window Object (alert(), confirm(), prompt(), open(), close(), history, location, navigator), Storage (localStorage.setItem(), getItem(), removeItem(), clear(); sessionStorage), Fetch API (fetch(), then() for responses), Canvas, Web Workers, Geolocation.

## Advanced Topics
Iterables and Iterators (Symbol.iterator, next()), Generators (function*, yield), Symbols (Symbol(), Symbol.for()), Proxy (new Proxy(), get, set traps), Reflect API, WeakMap, WeakSet, Bitwise Operations, Performance (timing with console.time()), Debugging (console.log(), console.error(), debugger), Best Practices (avoid globals, use strict, modular code), Common Mistakes (== vs ===, hoisting issues, async pitfalls).

