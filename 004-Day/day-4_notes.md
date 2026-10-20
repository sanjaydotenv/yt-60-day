## 📅 Day 4 — JavaScript Engines

> **Understand how JavaScript actually runs.**

### Engines

- V8
- SpiderMonkey
- JavaScriptCore
- Chakra

### Internals

- Parser
- AST (Abstract Syntax Tree)
- Ignition
- TurboFan
- JIT Compiler
- Interpreter
- Compiler
- Optimization
- Hidden Classes
- Inline Cache
- Deoptimization

---


# ⚙️ Day 04 — JavaScript Engines

> 🚀 **Goal:** Understand how JavaScript actually runs behind the scenes.

---

## 📌 1. What is a JavaScript Engine?

JavaScript Engine ek program hai jo JavaScript code ko process aur execute karta hai.

Hum JavaScript mein code likhte hain, aur engine us code ko execute karne mein help karta hai.

**Example:** Chrome aur Node.js mein V8 engine use hota hai.

---

## 🌐 2. JavaScript Engines

| Engine            | Used In               |
| ----------------- | --------------------- |
| 🔹 V8             | Chrome, Node.js       |
| 🦊 SpiderMonkey   | Firefox               |
| 🍎 JavaScriptCore | Safari                |
| 🔷 Chakra         | Legacy Microsoft Edge |

---

## 🔍 3. JavaScript Engine Internals

### 1️⃣ Parser

Parser JavaScript code ki syntax aur structure ko analyze karta hai.

```js
let name = "Sanjay";
```

Parser check karta hai ki code ki syntax sahi hai ya nahi.

### 2️⃣ AST (Abstract Syntax Tree)

AST code ki structure ko tree-like format mein represent karta hai.

**Simple meaning:** Code ko structured form mein represent karna, taaki engine uski structure ko process kar sake.

### 3️⃣ Ignition

Ignition, V8 engine ka interpreter hai.

Ye JavaScript code se generate hue bytecode ko execute karta hai.

### 4️⃣ TurboFan

TurboFan, V8 engine ka optimizing compiler hai.

Ye frequently executed code ko optimize karke uski execution performance improve karne mein help karta hai.

### 5️⃣ JIT Compiler (Just-In-Time Compiler)

JIT compilation mein code execution ke dauran compile hota hai.

V8 jaise engines interpretation aur compilation dono techniques use karte hain, taaki JavaScript efficiently execute ho sake.

### 6️⃣ Interpreter

Interpreter instructions ko execute karta hai.

V8 mein Ignition bytecode ko execute karta hai.

### 7️⃣ Compiler

Compiler code ko ek doosre representation mein translate karta hai, jaise machine code.

V8 ka TurboFan optimizing machine code generate kar sakta hai.

### 8️⃣ Optimization

Optimization ka matlab code ko efficiently execute karne ke liye improve karna hai.

Engine runtime par milne wali information ka use karke optimization kar sakta hai.

### 9️⃣ Hidden Classes

V8 objects ki structure ko track karne ke liye Hidden Classes, jinhe Maps bhi kaha jata hai, use karta hai.

Ye objects ke properties ko efficiently access karne mein help karti hain.

### 🔟 Inline Cache (IC)

Inline Cache, property access aur kuch operations ko fast karne mein help karta hai.

Engine pehle dekhe gaye object structures ki information reuse kar sakta hai.

### 1️⃣1️⃣ Deoptimization

Jab optimized code ki assumptions valid nahi rehti, engine optimized code se less-optimized execution par wapas ja sakta hai.

Is process ko Deoptimization kehte hain.

---

## 🔄 4. How JavaScript Executes in V8

```text
      JavaScript Code
             |
             ▼
           Parser
             |
             ▼
             AST
             |
             ▼
       Bytecode Generation
             |
             ▼
          Ignition
        (Interpreter)
             |
             ▼
    Runtime Feedback & Profiling
             |
             ▼
          TurboFan
     (Optimizing Compiler)
             |
             ▼
      Optimized Machine Code
```

> 💡 Note: Ye V8 ke execution process ka simplified overview hai. Actual execution flow isse zyada complex hai.

---

## 🎯 5. Key Takeaways

* ✅ JavaScript Engine code ko execute karta hai.
* ✅ Parser code ki syntax aur structure analyze karta hai.
* ✅ AST code ki structure ko represent karta hai.
* ✅ Ignition V8 ka interpreter hai.
* ✅ TurboFan V8 ka optimizing compiler hai.
* ✅ JIT ka full form Just-In-Time hai.
* ✅ Hidden Classes objects ki structure track karti hain.
* ✅ Inline Cache frequently repeated operations ko fast karne mein help karta hai.
* ✅ Deoptimization tab ho sakta hai jab optimized code ki assumptions invalid ho jati hain.

---

## 📚 Learning Progress

* [x] JavaScript Engines
* [x] Parser
* [x] AST
* [x] Ignition
* [x] TurboFan
* [x] JIT Compiler
* [x] Interpreter & Compiler
* [x] Optimization
* [x] Hidden Classes
* [x] Inline Cache
* [x] Deoptimization

---

### 💻 Crafted by Sanjay

**Keep Learning. Keep Building. Keep Improving. 🚀**
