# Chapter 5: Data Types in JavaScript

## Introduction (English)

Welcome to **Chapter 5: Data Types in JavaScript**. In this chapter, we will explore different data types in JavaScript and understand how they work.

By the end of this chapter, you will:
- Understand what **data types** are.
- Learn the difference between **primitive** and **non-primitive** data types.
- Know how to use different data types effectively.

---

## What are Data Types?
Data types define the type of value stored in a variable. JavaScript has two main categories of data types:

1. **Primitive Data Types** (Stored directly in memory)
2. **Non-Primitive (Reference) Data Types** (Stored by reference)

### 1. Primitive Data Types
Primitive data types include:
- `String` (Text values)
- `Number` (Numeric values)
- `Boolean` (True/False values)
- `Null` (Empty value)
- `Undefined` (Variable declared but not assigned)
- `Symbol` (Unique identifiers, ES6+)
- `BigInt` (Large numbers, ES11+)

#### Example 1: Primitive Data Types
```javascript
let name = "John"; // String
let age = 25; // Number
let isStudent = true; // Boolean
let emptyValue = null; // Null
let notAssigned; // Undefined
let uniqueId = Symbol("id"); // Symbol
let bigNumber = 123456789012345678901234567890n; // BigInt
```

---

### 2. Non-Primitive (Reference) Data Types
These include:
- `Object` (Collection of key-value pairs)
- `Array` (List of values)
- `Function` (Reusable block of code)

#### Example 2: Non-Primitive Data Types
```javascript
let person = { name: "John", age: 25 }; // Object
let numbers = [1, 2, 3, 4, 5]; // Array
let greet = function() { console.log("Hello, World!"); }; // Function
```

---

## Difference Between Primitive and Non-Primitive Data Types
| Feature | Primitive | Non-Primitive |
|---------|----------|--------------|
| Stored in memory | Directly | By reference |
| Mutability | Immutable | Mutable |
| Example | `String`, `Number` | `Object`, `Array` |

---

## Best Practices for Using Data Types
1. **Use `const` for constants** and `let` for variables that change.
2. **Prefer `null` over `undefined`** when explicitly assigning an empty value.
3. **Use objects for complex data** instead of multiple separate variables.
4. **Use arrays for collections of values**.
5. **Check data type using `typeof`**.

#### Example 3: Checking Data Type
```javascript
console.log(typeof "Hello"); // String
console.log(typeof 100); // Number
console.log(typeof true); // Boolean
console.log(typeof {}); // Object
console.log(typeof []); // Object (Array is a type of object)
console.log(typeof function(){}); // Function
```

---

## Assignments
1. Declare a variable of each primitive data type and log its value.
2. Create an object with at least three properties.
3. Write a function and store it in a variable.
4. Declare an array and access its elements using indexes.
5. Use `typeof` to check the data type of different variables.

---

## Summary
- JavaScript has **primitive** and **non-primitive** data types.
- Primitive types include `String`, `Number`, `Boolean`, `Null`, `Undefined`, `Symbol`, and `BigInt`.
- Non-primitive types include `Object`, `Array`, and `Function`.
- **Primitive values are stored directly**, while **non-primitive values are stored by reference**.

This chapter is presented by **Muhammad Raza** (SMRIT - Smart Modern Revolutionary IT Training). 🚀

---

## ڈیٹا ٹائپس (Urdu)

### ڈیٹا ٹائپس کیا ہیں؟
ڈیٹا ٹائپس وہ اقسام ہوتی ہیں جو کسی بھی ویری ایبل میں محفوظ ہونے والی ویلیو کی نوعیت کو ظاہر کرتی ہیں۔

### 1. بنیادی (Primitive) ڈیٹا ٹائپس
یہ وہ ڈیٹا ٹائپس ہیں جو براہ راست میموری میں محفوظ ہوتی ہیں:
- **String** (متنی اقدار)
- **Number** (عددی اقدار)
- **Boolean** (True/False)
- **Null** (خالی ویلیو)
- **Undefined** (متغیر متعین لیکن غیر مختص شدہ)
- **Symbol** (منفرد شناخت کار)
- **BigInt** (بہت بڑی عددی ویلیو)

#### مثال:
```javascript
let naam = "Ali"; // String
let umar = 30; // Number
let talib = false; // Boolean
let khaali = null; // Null
let mutaiyan; // Undefined
let pehchan = Symbol("id"); // Symbol
let baraAdad = 987654321012345678901234567890n; // BigInt
```

---

### 2. غیر بنیادی (Non-Primitive) ڈیٹا ٹائپس
یہ ریفرنس کے ذریعے محفوظ ہوتے ہیں:
- **Object** (کلیدی جوڑوں کی کلیکشن)
- **Array** (ویلیوز کی فہرست)
- **Function** (قابل استعمال کوڈ بلاک)

#### مثال:
```javascript
let shakhs = { naam: "Ali", umar: 30 }; // Object
let adad = [1, 2, 3, 4, 5]; // Array
let salam = function() { console.log("سلام دنیا!"); }; // Function
```

---

## بہترین طریقے
1. **`const` مستقل اقدار کے لیے استعمال کریں**، `let` قابل تبدیلی متغیرات کے لیے۔
2. **`null` کو `undefined` پر ترجیح دیں** جب کوئی خالی قدر متعین کرنی ہو۔
3. **معقد ڈیٹا کے لیے objects استعمال کریں**۔
4. **مجموعی ڈیٹا کے لیے arrays استعمال کریں**۔
5. **`typeof` کا استعمال کرکے ڈیٹا کی قسم چیک کریں**۔

#### مثال:
```javascript
console.log(typeof "سلام"); // String
console.log(typeof 50); // Number
console.log(typeof true); // Boolean
console.log(typeof {}); // Object
console.log(typeof []); // Object (Array بھی ایک object کی قسم ہے)
console.log(typeof function(){}); // Function
```

---

## اسائنمنٹس
1. ہر بنیادی ڈیٹا ٹائپ کے لیے ایک متغیر بنائیں اور اس کی ویلیو پرنٹ کریں۔
2. تین پراپرٹیز کے ساتھ ایک object بنائیں۔
3. ایک function لکھیں اور اسے ایک ویری ایبل میں محفوظ کریں۔
4. ایک array بنائیں اور اس کے عناصر تک رسائی حاصل کریں۔
5. مختلف متغیرات کی قسم `typeof` سے چیک کریں۔

---

## خلاصہ
- جاوا اسکرپٹ میں **بنیادی اور غیر بنیادی** ڈیٹا ٹائپس موجود ہیں۔
- بنیادی ٹائپس میں `String`, `Number`, `Boolean`, `Null`, `Undefined`, `Symbol`, اور `BigInt` شامل ہیں۔
- غیر بنیادی ٹائپس میں `Object`, `Array`, اور `Function` شامل ہیں۔
- **بنیادی اقدار براہ راست محفوظ ہوتی ہیں** جبکہ **غیر بنیادی اقدار ریفرنس کے ذریعے محفوظ ہوتی ہیں**۔

یہ باب **محمد رضا** (SMRIT - Smart Modern Revolutionary IT Training) کی جانب سے پیش کیا گیا ہے۔ 🚀

