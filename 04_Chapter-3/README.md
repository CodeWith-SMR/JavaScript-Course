# Chapter 3: The Modern Mode - "use strict"

## Introduction (English)

Welcome to **Chapter 3: The Modern Mode - "use strict"**. In this chapter, we will learn about JavaScript's **strict mode**, why it is important, and how it helps us write safer and cleaner code.

By the end of this chapter, you will:
- Understand what **"use strict"** is.
- Learn how to enable strict mode.
- Identify the errors that strict mode prevents.
- Write safer JavaScript code with strict mode.

---

## What is "use strict"?
JavaScript **strict mode** is a way to enforce stricter parsing and error handling in your code. It helps avoid common coding mistakes and makes debugging easier.

### How to Enable Strict Mode
Strict mode is enabled by adding **"use strict"** at the beginning of a script.

#### Example 1: Enabling Strict Mode in a Script
```javascript
"use strict";

let name = "John";
alert(name);
```

#### Example 2: Strict Mode Preventing Errors
```javascript
"use strict";

let age = 25;
alert(age);
```

---

## Benefits of Strict Mode
Strict mode helps in:
1. **Preventing accidental global variables**
   ```javascript
   "use strict";
   let x = 10;
   alert(x);
   ```

2. **Catching silent errors**
   ```javascript
   "use strict";
   let y = "Hello";
   alert(y);
   ```

---

## Assignments
1. Enable **strict mode** in a JavaScript program and test it using `alert`.
2. Write a program where strict mode **prevents accidental global variables** and display values using `alert`.
3. Create a script that shows the **difference between strict mode and non-strict mode** using `alert`.
4. Write a JavaScript script using `let` and `alert` to demonstrate strict mode errors.
5. Use strict mode and `alert` to show how it prevents undeclared variables.

---

## Summary
- **Strict mode** helps catch errors and enforce better coding practices.
- It prevents **accidental global variables** and **catches silent errors**.
- It makes debugging easier and improves JavaScript performance.

This chapter is presented by **Muhammad Raza** (SMRIT - Smart Modern Revolutionary IT Training). 🚀

---

## تعارف (Urdu)

خوش آمدید **باب 3: جدید موڈ - "use strict"**۔ اس باب میں ہم سیکھیں گے کہ **strict mode** کیا ہے، یہ کیوں ضروری ہے، اور یہ کوڈنگ کو کیسے بہتر بناتا ہے۔

### "use strict" کیا ہے؟
جاوا اسکرپٹ کا **strict mode** کوڈ کو زیادہ محفوظ اور غلطیوں سے پاک بنانے میں مدد کرتا ہے۔

### Strict Mode کو فعال کرنے کا طریقہ
اسے فعال کرنے کے لیے اسکرپٹ کے آغاز میں **"use strict"** لکھا جاتا ہے۔

#### مثال 1: اسکرپٹ میں Strict Mode
```javascript
"use strict";

let name = "Ali";
alert(name);
```

#### مثال 2: Strict Mode کی روک تھام
```javascript
"use strict";

let age = 30;
alert(age);
```

---

## Strict Mode کے فوائد
1. **غلطی سے گلوبل ویری ایبل بننے سے بچاؤ**
   ```javascript
   "use strict";
   let x = 10;
   alert(x);
   ```

2. **چھپی ہوئی غلطیوں کو پکڑتا ہے**
   ```javascript
   "use strict";
   let y = "Hello";
   alert(y);
   ```

---

## اسائنمنٹس
1. **strict mode** کو جاوا اسکرپٹ میں فعال کریں اور `alert` کے ذریعے ٹیسٹ کریں۔
2. ایسا پروگرام لکھیں جہاں strict mode **غلطی سے گلوبل ویری ایبل بننے سے روکے** اور `alert` کا استعمال کریں۔
3. ایک ایسا اسکرپٹ لکھیں جو **strict mode اور non-strict mode کے فرق کو ظاہر کرے** اور `alert` استعمال کرے۔
4. ایک ایسا جاوا اسکرپٹ اسکرپٹ لکھیں جہاں `let` اور `alert` کا استعمال کرتے ہوئے strict mode کی غلطیوں کو دکھایا جائے۔
5. `use strict` کا استعمال کرتے ہوئے `alert` کے ذریعے ثابت کریں کہ یہ غیر اعلان شدہ ویری ایبلز کو کیسے روکتا ہے۔

---

## خلاصہ
- **Strict mode** غلطیوں کو پکڑنے اور بہتر کوڈنگ کے لیے ضروری ہے۔
- یہ **گلوبل ویری ایبلز، اور چھپی ہوئی غلطیوں** سے بچاتا ہے۔
- یہ جاوا اسکرپٹ کی کارکردگی اور سیکیورٹی کو بہتر بناتا ہے۔

یہ باب **محمد رضا** (SMRIT - Smart Modern Revolutionary IT Training) کی جانب سے پیش کیا گیا ہے۔ 🚀

