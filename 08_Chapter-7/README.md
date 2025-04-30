# Chapter 7: Type Conversions

## Introduction (English)

JavaScript is a **dynamically typed language**, which means variables can hold values of any type without a fixed data type. Sometimes, you’ll need to **convert a value** from one type to another — this is called **type conversion**.

There are three main types of conversions:
- To String
- To Number
- To Boolean

Let's explore each one with examples.

---

## 1. String Conversion
We can convert values to strings using `String(value)`.

```javascript
let value = true;
alert(typeof value); // boolean

value = String(value);
alert(typeof value); // string
```

📝 Use Case: When you want to display or log values as readable text.

---

## 2. Numeric Conversion
We can convert values to numbers using `Number(value)`.

```javascript
alert(Number("123")); // 123
alert(Number("123z")); // NaN (Not a Number)
alert(Number(true)); // 1
alert(Number(false)); // 0
```

📝 Use Case: When you receive numeric input as a string and want to perform math operations.

---

## 3. Boolean Conversion
Values can be converted to boolean using `Boolean(value)`.

```javascript
alert(Boolean(1)); // true
alert(Boolean(0)); // false
alert(Boolean("hello")); // true
alert(Boolean("")); // false
```

📝 Use Case: Used in condition checking (`if`, loops, etc.)

### Falsy Values
The following values become `false` when converted to boolean:
- `0`
- `""` (empty string)
- `null`
- `undefined`
- `NaN`

Everything else is considered `true`.

---

## Assignments
1. Convert `false` to string and log the type.
2. Convert string `'456'` to number and add 44 to it.
3. Check the boolean value of `"SMRIT"`.
4. Convert `undefined` to number.
5. Create a prompt to get a number and convert it explicitly before multiplying by 2.

---

## Summary
- Use `String(value)` to convert to string.
- Use `Number(value)` to convert to number.
- Use `Boolean(value)` to convert to boolean.

Understanding type conversion is essential for building interactive and dynamic applications.

This chapter is presented by **Muhammad Raza** (SMRIT - Smart Modern Revolutionary IT Training). 🚀

---

## تعارف (Urdu)

جاوا اسکرپٹ ایک **dynamically typed** زبان ہے، جس میں ویری ایبل کسی بھی ٹائپ کا ڈیٹا رکھ سکتا ہے۔ کئی بار ہمیں کسی ویلیو کو ایک ٹائپ سے دوسری میں **تبدیل (convert)** کرنا پڑتا ہے۔ اسے **type conversion** کہتے ہیں۔

تین بنیادی conversions:
- String میں تبدیل کرنا
- Number میں تبدیل کرنا
- Boolean میں تبدیل کرنا

آئیے ہر ایک کو مثالوں کے ساتھ سمجھتے ہیں:

---

## 1. String میں تبدیلی
`String(value)` کا استعمال کرتے ہیں:

```javascript
let value = true;
alert(typeof value); // boolean

value = String(value);
alert(typeof value); // string
```

📝 استعمال: جب آپ کسی ویلیو کو text کے طور پر دکھانا چاہتے ہیں۔

---

## 2. Number میں تبدیلی
`Number(value)` کا استعمال کریں:

```javascript
alert(Number("123")); // 123
alert(Number("123z")); // NaN
alert(Number(true)); // 1
alert(Number(false)); // 0
```

📝 استعمال: جب آپ کو input string میں ملے اور آپ اسے math میں استعمال کرنا چاہیں۔

---

## 3. Boolean میں تبدیلی
`Boolean(value)` کے ذریعے کیا جاتا ہے:

```javascript
alert(Boolean(1)); // true
alert(Boolean(0)); // false
alert(Boolean("hello")); // true
alert(Boolean("")); // false
```

📝 استعمال: if statement یا loops میں condition چیک کرنے کے لیے۔

### Falsy ویلیوز:
یہ ویلیوز Boolean میں تبدیل ہونے پر false بنتی ہیں:
- `0`
- `""` (خالی string)
- `null`
- `undefined`
- `NaN`

باقی سب true ہوتے ہیں۔

---

## اسائنمنٹس
1. `false` کو string میں تبدیل کریں اور type log کریں۔
2. `'456'` کو number میں تبدیل کریں اور 44 کا اضافہ کریں۔
3. `"SMRIT"` کی Boolean ویلیو چیک کریں۔
4. `undefined` کو number میں تبدیل کریں۔
5. `prompt()` سے نمبر لیں، convert کریں، اور 2 سے multiply کریں۔

---

## خلاصہ
- `String(value)` – string میں تبدیل کرنے کے لیے۔
- `Number(value)` – number میں تبدیل کرنے کے لیے۔
- `Boolean(value)` – boolean میں تبدیل کرنے کے لیے۔

Type conversions کو سمجھنا انٹرایکٹو اور ڈائنامک ایپلیکیشنز بنانے کے لیے ضروری ہے۔

یہ باب **محمد رضا** (SMRIT - Smart Modern Revolutionary IT Training) کی طرف سے پیش کیا گیا ہے۔ 🚀

