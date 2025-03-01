# Chapter 4: Variables in JavaScript

## Introduction (English)

Welcome to **Chapter 4: Variables in JavaScript**. In this chapter, we will explore variables, their types, and how to use them efficiently in JavaScript.

By the end of this chapter, you will:
- Understand what **variables** are.
- Learn the difference between `var`, `let`, and `const`.
- Know how to declare and initialize variables.
- Follow best practices for using variables.

---

## What are Variables?
A **variable** is a container that holds data. It allows us to store, update, and retrieve values in our programs.

### How to Declare a Variable
JavaScript provides three ways to declare variables:
1. `var` (Old way, not recommended)
2. `let` (Preferred for variables that can change)
3. `const` (Preferred for values that do not change)

#### Example 1: Declaring Variables
```javascript
var name = "John"; // Using var (not recommended)
let age = 25; // Using let
const country = "USA"; // Using const
```

---

## Difference Between `var`, `let`, and `const`
| Feature | `var` | `let` | `const` |
|---------|------|------|-------|
| Re-declaration | Allowed | Not allowed | Not allowed |
| Re-assignment | Allowed | Allowed | Not allowed |
| Scope | Function | Block | Block |
| Hoisting | Yes | No | No |

### Example 2: Block Scope with `let` and `const`
```javascript
if (true) {
    let x = 10;
    const y = 20;
}
console.log(x); // Error: x is not defined
console.log(y); // Error: y is not defined
```

### Example 3: Hoisting with `var`
```javascript
console.log(myVar); // Undefined
var myVar = "Hello";
```

---

## Best Practices for Using Variables
1. **Use `const` by default**, and use `let` only if the value needs to change.
2. **Avoid `var`** because it has function scope and can cause unexpected issues.
3. **Use meaningful names** for variables to improve code readability.
4. **Follow camelCase naming convention**, e.g., `userName`, `totalAmount`.
5. **Initialize variables properly** to avoid `undefined` values.

---

## Assignments
1. Declare three variables using `var`, `let`, and `const` and log them to the console.
2. Write a program where a variable declared with `let` is updated later.
3. Try to reassign a `const` variable and note the error.
4. Create a function that demonstrates block scope with `let` and `const`.
5. Explain hoisting by writing a program that uses `var` before declaration.

---

## Summary
- Variables store data and help in managing values dynamically.
- JavaScript provides `var`, `let`, and `const` for variable declaration.
- `let` and `const` are block-scoped, whereas `var` is function-scoped.
- Always prefer `const` for constants and `let` for changeable values.

This chapter is presented by **Muhammad Raza** (SMRIT - Smart Modern Revolutionary IT Training). 🚀

---

## متغیرات (Urdu)

### متغیرات کیا ہیں؟
متغیرات **(variables)** ایسے کنٹینرز ہوتے ہیں جو ڈیٹا ذخیرہ کرنے کے لیے استعمال کیے جاتے ہیں۔

### متغیرات کے اعلان کے طریقے
جاوا اسکرپٹ میں تین طریقے ہیں:
1. `var` (پرانا طریقہ، تجویز نہیں کیا جاتا)
2. `let` (تبدیل ہونے والے متغیرات کے لیے بہترین)
3. `const` (مستقل متغیرات کے لیے)

#### مثال: متغیرات کا اعلان
```javascript
var name = "Ali"; // var کا استعمال (تجویز نہیں کیا جاتا)
let age = 30; // let کا استعمال
const country = "Pakistan"; // const کا استعمال
```

---

## `var`, `let` اور `const` میں فرق
| خصوصیت | `var` | `let` | `const` |
|---------|------|------|-------|
| دوبارہ اعلان | ممکن | ممکن نہیں | ممکن نہیں |
| دوبارہ تفویض | ممکن | ممکن | ممکن نہیں |
| دائرہ کار | فنکشن | بلاک | بلاک |
| ہوائسٹنگ | ہاں | نہیں | نہیں |

### مثال: `let` اور `const` کا بلاک اسکوپ
```javascript
if (true) {
    let x = 10;
    const y = 20;
}
console.log(x); // غلطی: x متعین نہیں ہوا
console.log(y); // غلطی: y متعین نہیں ہوا
```

### مثال: `var` کے ساتھ ہوائسٹنگ
```javascript
console.log(myVar); // غیر متعین
var myVar = "Hello";
```

---

## بہترین طریقے
1. **ڈیفالٹ طور پر `const` استعمال کریں**، `let` صرف تب استعمال کریں جب ویلیو تبدیل کرنی ہو۔
2. **`var` سے پرہیز کریں** کیونکہ یہ فنکشن اسکوپ رکھتا ہے۔
3. **مناسب اور وضاحتی نام** استعمال کریں تاکہ کوڈ پڑھنے میں آسانی ہو۔
4. **camelCase کا استعمال کریں** جیسے `userName`, `totalAmount`۔
5. **متغیرات کو فوری متعین کریں** تاکہ `undefined` کی غلطیوں سے بچا جا سکے۔

---

## اسائنمنٹس
1. `var`, `let`, اور `const` سے متغیرات بنا کر کنسول میں پرنٹ کریں۔
2. `let` سے ایک متغیر بنا کر بعد میں اسے اپڈیٹ کریں۔
3. `const` والے متغیر کو ری-اسائن کر کے ایرر دیکھیں۔
4. `let` اور `const` کے بلاک اسکوپ کو ایک فنکشن کے ذریعے سمجھائیں۔
5. `var` کے ساتھ ہوائسٹنگ کا ایک پروگرام لکھ کر فرق واضح کریں۔

---

## خلاصہ
- متغیرات **ڈیٹا کو ذخیرہ اور مینیج** کرنے کے لیے استعمال ہوتے ہیں۔
- `var`, `let`, اور `const` کا مختلف دائرہ کار ہوتا ہے۔
- `let` اور `const` بلاک اسکوپ رکھتے ہیں، جبکہ `var` فنکشن اسکوپ رکھتا ہے۔
- بہتر کوڈنگ کے لیے `const` کو ترجیح دیں۔

یہ باب **محمد رضا** (SMRIT - Smart Modern Revolutionary IT Training) کی جانب سے پیش کیا گیا ہے۔ 🚀

