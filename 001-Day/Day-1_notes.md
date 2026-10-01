# 📅 Day 1 — Computer Languages Evolution

- Machine Language
- Assembly Language
- C
- C++
- Why Scripting Languages Came
- Static vs Dynamic Languages
- Compiled vs Interpreted Languages
- Runtime Kya Hota Hai

---


## 📅 Day 1 — Computer Languages Evolution

## Machine Language

Chalo aao aaj samajhte hain ki **Machine Language** actually mein hai kya, isko Machine Language kyon kehte hain aur ye duniya ki sabse pehli programming language kyon maani jaati hai.

Agar tumhe Machine Language samajh aa gayi, to believe me, aage Assembly, C, C++, JavaScript aur baaki saari languages samajhna bahut easy ho jayega. Kyunki har language ka end goal sirf ek hi hota hai...

**Computer ko instruction dena.**

Lekin problem ye hai ki computer hamari language nahi samajhta.

Na usse Hindi aati hai.

Na English.

Na JavaScript.

Na Python.

Na C.

Computer sirf ek hi language samajhta hai...

**Machine Language.**

Isi wajah se iska naam **Machine Language** pada, kyunki ye language sirf machine (CPU) samajh sakta hai. Humans is language ko dekh to sakte hain, lekin ise padhna aur likhna bahut mushkil hota hai.

---

# Machine Language Actually Mein Kya Hoti Hai?

Ab sawal aata hai ki ye Machine Language dikhti kaise hai?

Ye kuch is tarah dikhti hai.

```text
010011001010101001010101010101010
```

Ya

```text
111001010101000101001010100101001
```

Ya

```text
000100100101010100101001010010101
```

Ye jo tum dekh rahe ho na...

Isi ko Machine Language ya Binary Language kehte hain.

Ye humans ke liye bilkul readable nahi hoti, lekin CPU isi language ko samajhta hai.

---

# Lekin Ek Minute...

Ye jo hum baar-baar `0` aur `1` bol rahe hain...

Ye actually hote kya hain?

Kya computer ke andar sach mein 0 aur 1 ghoom rahe hote hain?

**Nahi.**

Aur ye point bahut important hai.

Ye jo `0` aur `1` hain, ye sirf **hum humans ne samajhne ke liye naam diye hain.**

Computer ke andar actual mein sirf **Electricity** hoti hai.

Hum us electricity ko represent karte hain:

```text
0 = Low Voltage / Current Pass Nahi Ho Raha

1 = High Voltage / Current Pass Ho Raha
```

Ya simple language mein...

```text
0 = OFF

1 = ON
```

Dhyan rahe...

Computer ke andar literally `0` aur `1` nahi hote.

Andar sirf electricity hoti hai.

Hum us electricity ko samajhne ke liye `0` aur `1` likhte hain.

---

# Lekin Electricity Ko Control Kaun Karta Hai?

Yahin par entry hoti hai ek bahut important component ki...

**Transistor.**

Transistor ko abhi simple language mein samajho.

Jaise tumhare ghar mein ek switch hota hai.

Switch OFF.

Light band.

Switch ON.

Light chalu.

Bas transistor bhi almost waise hi kaam karta hai.

Difference sirf itna hai ki ghar ka switch light ko control karta hai.

Aur transistor electricity ko control karta hai.

Uski sirf do states hoti hain.

```text
OFF → Current Pass Nahi Hoga

ON → Current Pass Hoga
```

Aur in dono states ko hi hum represent kar dete hain.

```text
OFF = 0

ON = 1
```

Bas yahin se Binary shuru hoti hai.

---

# Sirf ON Aur OFF Se Itna Powerful Computer Kaise Ban Gaya?

Ab tumhare dimaag mein ek question aa raha hoga.

"Bhai sirf ON aur OFF se browser kaise chal gaya?"

"Game kaise chal gayi?"

"Video kaise play ho gayi?"

"Operating System kaise chal gaya?"

Aur ye sochna bilkul sahi hai.

Kyunki ek transistor sirf do hi kaam kar sakta hai.

```text
0

Ya

1
```

Lekin asli magic ek transistor mein nahi hai.

Asli magic hai...

**Billions of Transistors ek saath kaam karte hain.**

Aaj ke modern processors mein lagbhag **10 Billion+ Transistors** ho sakte hain.

Har transistor har second mein lakhon-crodo baar ON aur OFF hota rehta hai.

Jab ye saare transistors ek saath electricity ka ye ON/OFF pattern banate hain, tab CPU calculations karta hai.

Isi se...

- Browser chalta hai.
- Game run hoti hai.
- Videos play hoti hain.
- Photos open hoti hain.
- Operating System chalta hai.
- Aur tum jo ye notes padh rahe ho, wo bhi isi wajah se possible hai.

Matlab computer ki duniya ka har kaam aakhir mein sirf ek cheez par depend karta hai...

**Electricity ke ON aur OFF pattern par.**

---

# Bit Kya Hota Hai?

Ab ek aur word aata hai.

**Bit.**

Bit ka full form hota hai...

**Binary Digit**

Matlab Binary ka ek single digit.

Example:

```text
1
```

Ye 1 Bit hai.

```text
0
```

Ye bhi 1 Bit hai.

Aur agar hum likhen.

```text
1011
```

To isme total 4 Bits hain.

Aur

```text
10101010
```

Isme total 8 Bits hain.

Baad mein hum padhenge ki...

**8 Bits = 1 Byte**

---

# Machine Language Ko Fastest Language Kyon Kehte Hain?

Kyunki CPU ko ise translate nahi karna padta.

Machine Language directly CPU ko samajh aati hai.

Flow kuch aisa hota hai.

```text
Machine Language

↓

CPU

↓

Execution
```

Isliye Machine Language duniya ki sabse fast language maani jaati hai.

---

# Lekin Isme Problem Kya Thi?

Socho agar tumhe poora software kuch is tarah likhna pade.

```text
101010101010101001010101010101010

001010101010101010010101010101010

111010101010010101010101010100101
```

Aur galti se sirf ek bit change ho jaye.

```text
10101010

↓

10101011
```

To poora instruction badal sakta hai.

Bug dhoondhna almost impossible ho jata.

Isi wajah se humans ke liye Machine Language mein programming karna bahut difficult tha.

Aur isi problem ko solve karne ke liye baad mein **Assembly Language** aayi...

Jise hum agle topic mein detail se samjhenge.

---

# Yaad Rakhne Wali Baatein

- Machine Language computer ki native language hoti hai.
- CPU isi language ko directly execute karta hai.
- Machine Language Binary (0 aur 1) mein likhi hoti hai.
- 0 aur 1 actual numbers nahi, balki electricity ki states ka representation hain.
- Transistor ek electronic switch hota hai jo current ko control karta hai.
- OFF ko hum 0 aur ON ko hum 1 represent karte hain.
- Ek single 0 ya 1 ko Bit kehte hain.
- Modern CPU mein billions of transistors hote hain.
- Ye saare transistors milkar har calculation karte hain.
- Machine Language sabse fast hoti hai kyunki CPU ise directly execute karta hai.
- Lekin humans ke liye ise likhna aur samajhna bahut mushkil hota hai.

# 🟠 Assembly Language

## Kya hai?

Assembly Language Machine Language ka human readable version hai.

Machine Language me instructions 0 aur 1 me likhe hote the, jo humans ke liye bahut difficult tha.

Is problem ko solve karne ke liye Assembly Language aayi.

Isme binary ki jagah chhote keywords (Mnemonics) use hote hain.

Example:

```asm
MOV AX, 5
ADD AX, 10
```

Yaha

- MOV = Data copy karo
- ADD = Addition karo

Computer directly Assembly ko nahi samajhta.

Isliye ek software use hota hai jiska naam hai:

➡️ Assembler

Flow:

```

Assembly Code
↓
Assembler
↓
Machine Code (010101...)
↓
CPU Execute

```

### Advantages

- Machine Language se readable hai.
- Faster execution.
- Hardware ke bahut close hoti hai.
- Memory efficiently use hoti hai.

### Disadvantages

- Difficult syntax.
- Har CPU architecture ki alag Assembly hoti hai.
- Large software banana bahut hard hai.
- Maintain karna difficult hai.

---

# 🟢 C Language

## Kyu aayi?

Assembly me bade software banana almost impossible tha.

Har processor ki alag Assembly hoti thi.

Isliye ek High Level Language banayi gayi.

Uska naam tha

**C**

C ko Middle Level Language bhi bolte hain.

Kyuki isme

- High Level features bhi hain
- Low Level hardware access bhi hai

Example

```c
#include <stdio.h>

int main() {
    printf("Hello World");
}
```

Ye human easily samajh sakta hai.

Lekin CPU nahi.

Isliye Compiler use hota hai.

Flow

```

C Code
↓
Compiler
↓
Machine Code
↓
CPU

```

### Features

- Fast
- Portable
- Structured Programming
- Memory Access
- Pointer Support
- Operating System Development

Linux ka kernel mostly C me likha gaya hai.

---

# 🔵 C++

## C++ Kyu bana?

C bahut powerful thi.

Lekin bade projects me code maintain karna difficult tha.

Isliye C ke upar Object Oriented Programming add ki gayi.

Aur bana

C++

Example

```cpp
class Student{
public:
    string name;
};

int main(){
    Student s;
}
```

Ab hum Objects bana sakte hain.

Inheritance

Polymorphism

Encapsulation

Abstraction

Ye sab C++ me aaye.

### Use Cases

- Game Engines
- Unreal Engine
- Browsers
- High Performance Software
- Desktop Applications

---

# 🟣 Why Scripting Languages Came

Ab ek problem thi.

Har baar

Code likho

Compile karo

Fir run karo.

Development slow tha.

Developers ko fast development chahiye tha.

Tab aaye

Scripting Languages

Examples

- JavaScript
- Python
- PHP
- Ruby

Example

```javascript
console.log("Hello");
```

Save karo.

Run karo.

Bas.

Compilation manually nahi karni padti.

Development speed bahut increase ho gayi.

---

# 🔴 Static vs Dynamic Languages

## Static Language

Variable ka type pehle hi decide hota hai.

Example

```cpp
int age = 20;
```

Ab age me string nahi rakh sakte.

Compiler error dega.

Advantages

- Fast
- Type Safe
- Bugs kam

Languages

- C
- C++
- Java
- Rust
- Go

---

## Dynamic Language

Variable ka type runtime me decide hota hai.

Example

```javascript
let value = 10;

value = "Mayur";

value = true;
```

Har baar type change ho sakta hai.

Advantages

- Flexible
- Fast Development
- Less Code

Disadvantages

- Runtime Errors
- Type Related Bugs

Languages

- JavaScript
- Python
- Ruby

---

# 🟡 Compiled vs Interpreted Languages

## Compiled

Compiler pura program ek baar me Machine Code me convert karta hai.

Flow

```

Source Code
↓
Compiler
↓
Executable File
↓
Run

```

Advantages

- Fast execution
- Optimization
- Better performance

Examples

- C
- C++
- Rust
- Go

---

## Interpreted

Interpreter code ko line by line execute karta hai.

Flow

```

Source Code
↓
Interpreter
↓
Execute

```

Advantages

- Fast testing
- Easy debugging
- Platform Independent

Examples

- Python
- JavaScript (Engine ke through)
- Ruby

---

# 🟢 Runtime Kya Hota Hai?

Runtime ka matlab hai

**Jab program actually chal raha hota hai.**

Example

Tumne game install kar diya.

Ab game open ki.

Jo time game chal rahi hai...

Wo Runtime hai.

Compilation runtime se pehle hoti hai.

Runtime ke time

- Memory allocate hoti hai.
- Variables bante hain.
- Functions execute hote hain.
- Objects create hote hain.
- Input liya jata hai.
- Output diya jata hai.

Example

```javascript
let a = 10;
let b = 20;

console.log(a + b);
```

Jab ye execute hoga tab

Runtime

- Variable banayega.
- Memory allocate karega.
- Addition karega.
- Console me output dega.

---

# 🧠 Complete Evolution

```

Machine Language
        │
        ▼
Assembly Language
        │
        ▼
C Language
        │
        ▼
C++
        │
        ▼
Scripting Languages
(JavaScript, Python...)

```

---

# 📌 Important Points

- Machine Language sirf Binary hoti hai.
- Assembly me Mnemonics use hote hain.
- Assembly ko Assembler convert karta hai.
- C ek High/Middle Level Language hai.
- C ko Compiler Machine Code me convert karta hai.
- C++ ne Object Oriented Programming introduce ki.
- Scripting Languages fast development ke liye bani.
- Static Languages me type pehle fix hota hai.
- Dynamic Languages me type runtime par decide hota hai.
- Compiled Language pehle compile hoti hai fir execute hoti hai.
- Interpreted Language line by line execute hoti hai.
- Runtime matlab program ka actual execution time.

---

# 🎯 Day 1 Outcome

Aaj humne samjha:

- Assembly Language kya hai.
- C aur C++ kyu aaye.
- Scripting Languages ki need kya thi.
- Static aur Dynamic Languages me difference.
- Compiled aur Interpreted execution ka process.
- Runtime ka actual meaning.
- Computer Languages ki complete evolution.

---

---

---

---

---

---

---

---

---

---

---

---
