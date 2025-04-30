# Chapter 6: Interaction - alert, prompt, confirm

## Introduction (English)

In this chapter, we will learn about three important functions in JavaScript that allow **interaction with the user**:

- `alert()` – displays a message.
- `prompt()` – asks the user for input.
- `confirm()` – asks the user to confirm an action.

These functions are part of the **browser environment** and are used to interact with users directly.

---

## 1. alert()
The `alert()` function displays a popup message to the user.

```javascript
alert("Welcome to SMRIT JavaScript Course!");
```

📝 Use Case: Informing the user about a successful login or warning.

---

## 2. prompt()
The `prompt()` function asks the user for input and returns that input as a string.

```javascript
let name = prompt("What is your name?");
alert("Hello, " + name);
```

📝 Use Case: Getting user's name, age, or any input during runtime.

---

## 3. confirm()
The `confirm()` function shows a message with OK and Cancel buttons. It returns `true` if OK is clicked, and `false` if Cancel is clicked.

```javascript
let isConfirmed = confirm("Do you want to delete this item?");
if (isConfirmed) {
  alert("Item deleted");
} else {
  alert("Deletion cancelled");
}
```

📝 Use Case: Confirming critical actions (like delete, submit, etc.)

---

## Assignments
1. Show an alert with the message: "JavaScript is Fun!"
2. Use `prompt()` to ask the user for their favorite color and log it.
3. Create a confirmation box that asks: "Are you 18 or older?"
4. Ask the user for their name and greet them using `alert()`.
5. Use `confirm()` to ask the user if they want to reload the page, and if yes, use `location.reload()`.

---

## Summary
- `alert()` – for displaying messages.
- `prompt()` – for taking user input.
- `confirm()` – for asking the user to confirm an action.

These tools are great for **basic interactivity** in JavaScript programs.

This chapter is presented by **Muhammad Raza** (SMRIT - Smart Modern Revolutionary IT Training). 🚀

---

## تعارف (Urdu)

اس باب میں ہم تین اہم فنکشنز کے بارے میں سیکھیں گے جو جاوا اسکرپٹ میں **یوزر سے انٹرایکشن** کے لیے استعمال ہوتے ہیں:

- `alert()` – پیغام ظاہر کرنے کے لیے۔
- `prompt()` – یوزر سے ان پٹ لینے کے لیے۔
- `confirm()` – یوزر سے تصدیق لینے کے لیے۔

یہ فنکشنز براؤزر میں دستیاب ہوتے ہیں اور یوزر سے براہ راست بات چیت کے لیے استعمال کیے جاتے ہیں۔

---

## 1. alert()
`alert()` فنکشن ایک پاپ اپ میسج دکھاتا ہے:

```javascript
alert("SMRIT میں خوش آمدید!");
```

📝 استعمال: یوزر کو اطلاع دینے یا خبردار کرنے کے لیے۔

---

## 2. prompt()
`prompt()` فنکشن یوزر سے معلومات مانگتا ہے:

```javascript
let naam = prompt("آپ کا نام کیا ہے؟");
alert("خوش آمدید، " + naam);
```

📝 استعمال: یوزر سے نام، عمر یا دیگر معلومات حاصل کرنے کے لیے۔

---

## 3. confirm()
`confirm()` فنکشن ایک تصدیقی باکس دکھاتا ہے:

```javascript
let tasdeeq = confirm("کیا آپ اس آئٹم کو ڈیلیٹ کرنا چاہتے ہیں؟");
if (tasdeeq) {
  alert("آئٹم ڈیلیٹ ہوگئی");
} else {
  alert("ڈیلیٹ کینسل کردی گئی");
}
```

📝 استعمال: اہم ایکشنز سے پہلے یوزر سے تصدیق لینے کے لیے۔

---

## اسائنمنٹس
1. ایک alert دکھائیں جس میں لکھا ہو: "جاوا اسکرپٹ مزے دار ہے!"
2. `prompt()` سے یوزر سے اس کا پسندیدہ رنگ پوچھیں اور لاگ کریں۔
3. `confirm()` سے پوچھیں: "کیا آپ 18 سال یا اس سے زیادہ عمر کے ہیں؟"
4. یوزر سے نام پوچھ کر `alert()` کے ذریعے خوش آمدید کہیں۔
5. `confirm()` کے ذریعے یوزر سے پوچھیں کہ کیا وہ پیج ری لوڈ کرنا چاہتا ہے؟ اگر ہاں تو `location.reload()` استعمال کریں۔

---

## خلاصہ
- `alert()` پیغام دکھانے کے لیے۔
- `prompt()` یوزر سے معلومات لینے کے لیے۔
- `confirm()` یوزر سے تصدیق لینے کے لیے۔

یہ فنکشنز جاوا اسکرپٹ پروگرامز میں **بنیادی انٹرایکشن** کے لیے بہت مفید ہیں۔

یہ باب **محمد رضا** (SMRIT - Smart Modern Revolutionary IT Training) کی جانب سے پیش کیا گیا ہے۔ 🚀

