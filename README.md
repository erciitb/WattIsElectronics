# ER101
## Hello everyone, and welcome to ER 101!

![image](https://github.com/user-attachments/assets/a97bf91e-5eca-45b2-bf77-175d9c5d605e)

Have you ever been amazed by how electronics actually work? Like, how are phones, laptops, or robots even possible? It’s crazy to think that something as small as moving electrons and electric fields somehow powers all the tech we use every day — from gaming and social media to automation and AI.

It almost feels like magic… but it’s not. It’s science — and humans figured it out.

So, where do you begin if you want to really understand how computers and electronics work? Right here.

The Electronics and Robotics Club of IIT Bombay brings you ER 101 — a beginner-friendly roadmap to help you build a solid foundation in electronics and get a clear picture of how we use electricity to process information and build the tech around us.

---

 #### *We’re starting from the absolute basics, so feel free to skip around or move ahead — take it at your own pace.*
 
---

### To kick things off, here’s an excellent playlist that covers the fundamentals of digital electronics.
We’ll be referring to specific video numbers from this playlist throughout our journey in ER 101, so I highly recommend going through it as we progress. It’s genuinely one of the most well-structured and informative resources out there.

[▶️ Link to the Playlist](https://youtube.com/playlist?list=PLwjK_iyK4LLBC_so3odA64E2MLgIRKafl&si=oMMceoZ6F5fteiB8)

This playlist is an absolute goldmine — don’t overlook it. It’ll make a big difference in how clearly you understand the concepts ahead.

---

### Here’s another great resource to explore digital electronics.
If you prefer reading over videos — or want to explore certain topics in a different format — this GeeksforGeeks resource is a great alternative.

[📚 Digital Electronics Articles on GeeksforGeeks](https://www.geeksforgeeks.org/digital-electronics-logic-design-tutorials/)

It’s well-structured, beginner-friendly, and covers a wide range of topics in digital electronics. Definitely worth exploring if you enjoy learning by reading.

---

### 🔌 Try It Yourself — Simulations for Hands-On Practice

We’ll guide you through the concepts in this course, but if you *really* want to understand how things work, you’ve got to try them out yourself.  
Here are some platforms where you can experiment and build your own circuits:

---

#### 🧠 For Digital Logic Circuit Simulation

- 🔗 [**CircuitVerse**](https://circuitverse.org)  
  **CircuitVerse** is an online simulator designed for building and testing digital logic circuits. It’s perfect for experimenting with logic gates, flip-flops, multiplexers, and more — all in a visual, beginner-friendly environment.

  ![image](https://github.com/user-attachments/assets/5833b72d-a727-44ca-935a-8a3a967e10a3)


---

#### ⚙️ For Real-World Electronics & Arduino Simulation

- 🔗 [**Wokwi**](https://wokwi.com)  
  Wokwi is a powerful browser-based simulator for **Arduino**, ESP32, Raspberry Pi Pico, and more. It lets you build and test embedded systems with real-world components like sensors, displays, and microcontrollers — all without any hardware. Great for prototyping, debugging, or just learning how things work.

  ![image](https://github.com/user-attachments/assets/e06be3d5-63db-407d-b07f-729bff8dd87c)

- 🔗 [**TinkerCAD Circuits**](https://www.tinkercad.com/circuits)  
  **TinkerCAD** Circuits is a beginner-friendly online tool that lets you simulate basic electronics and **Arduino** projects. It’s simple, intuitive, and great for quickly testing ideas or learning how circuits work — no hardware needed

  ![image](https://github.com/user-attachments/assets/eeea2e30-1f66-4ef0-9b2f-f3c193326aa8)

---

## 🔌 What is Digital Electronics?
Digital electronics is the part of electronics that deals with systems using digital signals — signals that can only be 1 (high) or 0 (low).

Why just two values? Because it makes things much more reliable. Unlike analog signals that can be messy and affected by noise, digital signals are clear and easy to work with — which is why almost all modern devices like phones, laptops, and calculators are built using them.

<img src=https://github.com/user-attachments/assets/b77cbf50-43d1-49eb-8a9c-633b0961bda1 width=500>

---

## The Language of Digital Electronics: Binary
In digital electronics, everything comes down to 0s and 1s — they represent the low and high signals in a circuit. That’s why it’s important to understand the binary number system early on. Computers and digital devices store and handle all kinds of data — numbers, text, images — using just these two values. So, if you want to really get how digital systems work, binary is where it all begins.

![image](https://github.com/user-attachments/assets/5fbae6f6-dfb4-465f-9f00-85947e1ce293)


Here are some great resources to get you started :
- [Number Systems and Base Conversions](https://www.geeksforgeeks.org/number-system-and-base-conversions/)  
  Understand binary, decimal, octal, and hexadecimal systems — and how to convert between them.

- [Binary Arithmetic](https://www.geeksforgeeks.org/binary-number-system/)  
  Learn how addition, subtraction, and multiplication work in binary.

- [2’s Complement and Signed Representation](https://www.geeksforgeeks.org/binary-representations-in-digital-logic/)  
  Explore how negative numbers are handled using 1’s and 2’s complement.'

📼 **Relevant Videos:** *Videos 2–15 in the playlist*

- [🧠 IEEE 754 — How Do Computers Store Decimal Numbers?](https://www.geeksforgeeks.org/introduction-of-floating-point-representation/)

📼 **Relevant Videos:** *Videos 25–29 in the playlist*

![image](https://github.com/user-attachments/assets/80ddf543-9cf4-43f6-a25d-b07c2a3537bb)


---

### 🎯 Side Quest (Optional, but Super Cool)

Want to go a bit deeper or explore some bonus topics? These are not mandatory, but definitely fun to look into:

- **Gray Code, XS-3, BCD**  
  → [BCD](https://www.geeksforgeeks.org/bcd-or-binary-coded-decimal/)
    Represents each decimal digit separately in 4-bit binary. Easy to read, used in displays.
  
  → [XS-3](https://www.geeksforgeeks.org/excess-3-code/)
    Adds 3 to each digit before converting to binary. Helps avoid negative values in circuits.
  
  → [Gray Code](https://www.geeksforgeeks.org/what-is-gray-code/)
    Only one bit changes between consecutive numbers. Reduces errors in sensors and encoders.
  
    📼 *Videos 17–29 in the playlist*
  

- **Hamming Code (Error Correction)**  
  [Hamming Codes](https://www.geeksforgeeks.org/hamming-code-in-computer-network/) Learn how data can be checked and corrected — used in memory systems, communication, and more.  
  📼 *Videos 20–24 in the playlist*

![image](https://github.com/user-attachments/assets/f07b536b-bb99-4a88-b985-5565390e3e61)


---

## ⚙️ Intro to Logic Gates & Boolean Algebra

Let’s start with the real basics of digital electronics **— logic gates**.

Any complex operation a computer performs can be broken down into smaller logical steps. That’s exactly what Boolean algebra helps us do — describe and simplify these steps using logic.

Logic gates are the physical building blocks that implement this logic. Just like atoms make up all matter, logic gates form the core of all digital processes.

Understanding them is the first step to understanding how our technology really works.

---

### Logic Gates
- **AND**, **OR**, and **NOT** are the basic gates — everything in digital logic builds off of these. Then we’ve got **NAND** and **NOR**, known as universal gates because you can create any other gate using just one of them. Pretty interesting, right? Let’s check them out.

  [🔗 Explore Basic & Universal Gates](https://computerengineeringforbabies.com/blogs/engineering/logic-gate/)
  
  📼 *Videos 30–34, 49 and 51 in the playlist*

![image](https://github.com/user-attachments/assets/359950fd-e7ec-461a-ba8c-f0150fbc1514)

#### CMOS Logic Gates
We also take a quick peek under the hood to see how logic gates are actually built using transistors. Understanding the physical side — how these abstract logic blocks are made real — is pretty cool and helps make sense of how digital electronics work at the lowest level.  

- [CMOS Logic Gates](https://www.geeksforgeeks.org/cmos-logic-gate/)
  
📼 *Video 173* — How logic gates are built using complementary MOSFETs in CMOS technology.  

<img src=https://github.com/user-attachments/assets/654a9485-d1d5-4ba1-8736-2198ac7ce144 width=500>


Not familiar with how a MOSFET works? Here are some quick tutorials to get you up to speed:

* [Intro to MOSFETs](https://www.circuitbread.com/tutorials/how-a-mosfet-works-at-the-semiconductor-level) — Basics of how MOSFETs function.

* [NMOS vs PMOS Comparison](https://www.circuitbread.com/tutorials/nmos-vs-pmos-and-enhancement-vs-depletion-mode-mosfets) — The two types of MOSFETs and how they differ.


<img src=https://github.com/user-attachments/assets/73a29fba-a0a5-47a8-80f1-7e0a0579ec56 width=500>

---

### 🧠 Boolean Logic

Once you’ve got a grip on individual logic gates, the next step is learning how to represent and simplify more complex logic using Boolean algebra. This helps make your circuits cleaner, faster, and more efficient.

- **[Boolean Algebra & Laws](https://www.geeksforgeeks.org/boolean-algebra/)**  
  Learn the core rules and operations (like AND, OR, NOT) that help describe and manipulate logic expressions. These laws form the foundation for all logic simplification.
  
  📼 *Videos 35, 37*

  ![image](https://github.com/user-attachments/assets/01b43256-33b2-4dae-ad83-2342e5fabe85)


- **[SOP](https://www.geeksforgeeks.org/what-is-sum-of-product-sop-form/) | [POS](https://www.geeksforgeeks.org/what-is-product-of-sum-pos-form/)**  
  When writing Boolean expressions, there are two common formats — Sum of Products (SOP) and Product of Sums (POS). In SOP, you combine multiple ANDed terms using OR, while POS does the opposite by combining ORed terms using AND. These formats aren’t just theoretical — they’re incredibly useful when designing actual logic circuits, especially when it comes to optimization and simplification later using tools like K-Maps.
  
  📼 *Video 53*

- **[K-Maps & Minimization](https://www.geeksforgeeks.org/k-mapkarnaugh-map/)**  
  Karnaugh Maps (or K-Maps) are like cheat sheets for simplifying Boolean expressions. Instead of writing out a truth table and using algebra, you just group 1s or 0s on a grid. It’s a visual method that quickly helps reduce logic circuits into simpler versions with fewer gates.
Once you get used to it, this becomes your go-to technique when circuits start looking messy or redundant.

  📼 *Videos 57–61*

  ![image](https://github.com/user-attachments/assets/4ca49040-dd03-4917-b03b-c5083ecb6a0c)


- **[Don't Care Conditions](https://www.geeksforgeeks.org/dont-care-x-conditions-in-k-maps/)**  
  Sometimes, certain input combinations are either invalid or won’t occur in a real-world use case. These are called “don’t care” conditions, and they’re marked as 'X' in K-Maps.
The cool part? You can use these Xs however you want — either as 1 or 0 — to help you create larger groups and simplify your expressions even more.

  📼 *Video 62*

- **[Quine-McCluskey (Optional)](https://www.geeksforgeeks.org/quine-mccluskey-method/)**  
  Think of this as a more systematic, step-by-step way of minimizing Boolean expressions — perfect for writing logic simplification algorithms that computers can use.
While it’s not something you’ll always use by hand, knowing how it works helps when dealing with larger circuits where K-Maps get impractical. Great for those who want to dive deeper or are curious about how logic simplification is automated.

---
## ⚙️ Combinational Circuits


Let’s level up our logic. Using our understanding of basic gates, we now start building more complex circuits — the kind that actually do stuff. Combinational circuits are the next step: they don’t use any memory, which means their output depends only on the current inputs, nothing more. In this section, we’ll explore how simple gates can be combined to form higher-level blocks like adders, multiplexers, and comparators — circuits capable of performing real calculations and decision-making. It’s like upgrading from individual Lego bricks to full structures.

---

### ➕ Adders
Okay, first up — let’s build circuits called adders.
As we’ve learned about binary addition, it’s time to start building circuits that can actually add. Just imagine — a bunch of transistors, wired up and flowing with electricity, somehow doing math! They’re helping us add two numbers. Sure, it’s all in binary and we don’t get to see the satisfying decimal answers just yet… but don’t worry. With some more circuitry, it will all add up 😉.

- **[Half Adder](https://www.geeksforgeeks.org/digital-electronics-half-adder/)**  
  This is the most basic adder circuit — it takes in two single-bit binary inputs and gives you a sum and a carry. No carry-in here, just a simple intro to how logic gates can literally "add." It’s made using just an XOR and an AND gate. Pretty neat for something so simple.

  ![image](https://github.com/user-attachments/assets/589f6396-5fe4-4e8d-bb19-6fb08ad90f60)


- **[Full Adder](https://www.geeksforgeeks.org/full-adder-digital-electronics/)**  
  The full adder builds on the half adder and adds one more input: the carry-in. So now it can actually be used to add multi-bit numbers by chaining multiple full adders. This one’s essential for any real arithmetic in digital systems.

  <img src=https://github.com/user-attachments/assets/c96d4ca6-4d3a-4d14-a530-bfe65238bd87 width=500>
  

- **[Ripple Carry Adder](https://www.geeksforgeeks.org/parallel-adder-and-parallel-subtractor/)**  
Now that we’ve got full adders, we can connect them in series to add multi-bit binary numbers. That’s exactly what the ripple carry adder does. Each full adder handles a bit of the numbers and passes its carry to the next. It’s simple and easy to build — but as the name suggests, the carry "ripples" through each stage, which slows things down when dealing with lots of bits. Great for learning, not ideal for speed.

![image](https://github.com/user-attachments/assets/b58ab830-079b-4b13-96a9-5240f0694db4)


- **[Carry Look Ahead Adder](https://www.geeksforgeeks.org/digital-logic-carry-look-ahead-adder/)**  
  To fix the delay caused by ripple carry, we use a smarter design — the carry look ahead adder. Instead of waiting for the carry to travel through each adder, this circuit predicts it using logic based on the input bits. It uses the concepts of generate and propagate to compute all carries in parallel. That makes it way faster and far more efficient, especially in real-world CPUs. It’s a great example of how we trade off complexity for performance in circuit design.

  📼 *Videos 67–71*

  ![image](https://github.com/user-attachments/assets/e88bf9ff-f5e1-46cd-9343-42f16843876d)


- **[BCD Adder (Optional)](https://www.geeksforgeeks.org/digital-electronics-bcd-adder/)** | [📺 Video](https://www.youtube.com/watch?v=ss9FpyRgIjw)  
  Remember BCD? (Yeah, the one where we awkwardly fit decimal digits into 4-bit binary.) Now let’s try designing an adder that can handle numbers in that exact format. It’s a bit different from normal binary addition, but super useful in things like calculators and digital clocks where we actually care about decimal digits.


---

### ✖️ Multipliers

Alright — we’ve tackled addition, so next up is multiplication. Sounds straightforward, right? And yeah, conceptually it is: multiplying binary numbers is just repeated addition. But when it comes to the actual circuits... yeah, they can look pretty scary at first glance 😵‍💫.

But don’t worry — the core idea is still simple, and once you break it down, it's totally manageable. The videos do a great job walking through it, and I really recommend grabbing a pen and actually drawing out the circuit step by step. You’ll appreciate how the logic unfolds bit by bit(yep, pun intended 😏).  

📼 *Video 75 (Signed → 76 (signed multiplication is optional)*  


<img src=https://github.com/user-attachments/assets/5ef2828b-f642-451c-8b94-610366fd9246 width=600>


![image](https://github.com/user-attachments/assets/24118f79-99b2-47d8-b1a8-9f0d24eb45ad)

  
##### *P.S. Don’t worry — once you learn a bit about sequential circuits, we’ll be able to build a much more efficient (and slightly smaller!) circuit for binary multiplication*
---

#### ➖ Subtractors & Dividers
We’ve done addition and multiplication — so why stop there? Let’s cover the full set of basic operations. Subtractors and dividers aren’t always covered in depth, but they’re definitely worth checking out if you're curious about how binary subtraction and division work in hardware. Not strictly necessary, but definitely a fun dive!
- [Subtractor](https://www.geeksforgeeks.org/digital-logic/full-subtractor-in-digital-logic/)
- Divider (Sorry we dont have a reading resource for this)
  
📼 *Video 75, 85* 


---

### 🔁 Comparator
Alright — we’ve done addition, subtraction, and multiplication. Now let’s look at something a bit different: comparison. Sometimes you don’t want to calculate a value, you just want to know which number is bigger. That’s where comparators come in. A magnitude comparator takes in two binary numbers and tells you if one’s greater than, less than, or equal to the other. Pretty straightforward, but super important in decision-making circuits.  

**[Read More Here](https://www.geeksforgeeks.org/magnitude-comparator-in-digital-logic/)**  
  📼 *Video 78*

---

### 🎛️ MUX, DEMUX, Encoders & Decoders

Now let’s look at some basic but powerful logic circuits that act more like managers than calculators. These circuits don’t directly compute values, but they control how data flows in more complex systems. Whether it’s selecting inputs, routing outputs, or translating data formats, these blocks play a huge role in organizing and directing the logic inside a digital system. You'll see them pop up all over the place later on, so it's worth getting comfortable with them now.

- **[Multiplexers & Demux](https://www.elprocus.com/what-is-multiplexer-and-demultiplexer-types-and-differences/)**  
  Now let’s look at some logic circuits that aren’t doing calculations themselves, but are super useful for controlling where data goes. These are things like MUX, DEMUX, encoders, and decoders — they help manage inputs and outputs in bigger systems, and you’ll see them show up a lot as we go forward.  


  ![image](https://github.com/user-attachments/assets/377bffd1-06ee-43ac-ac8b-3725c237fea0) ![image](https://github.com/user-attachments/assets/e5106223-4df7-4eaf-9408-55946d3ac77d)



- **[Encoders & Decoders](https://www.geeksforgeeks.org/digital-logic-encoders-decoders/)**  
  Now let’s look at encoders and decoders — circuits that don’t really compute anything but are super useful when you need to convert data from one format to another. An encoder takes multiple inputs and compresses them into a smaller set of outputs, while a decoder does the opposite — it expands coded data into a more readable form. You'll see these often when dealing with memory, displays, or instruction sets.  

![image](https://github.com/user-attachments/assets/e6a762f1-a9c8-4ff4-9f15-4b4e25907112)

   
  📼 *Videos 79–90* (skip 85)

---
## ⏱️ Sequential Circuits
Until now, we’ve explored combinational circuits — where outputs depend only on the current inputs. But real-world tasks often need memory. Think about it: in many everyday tasks, each step depends on what happened just before. You can’t always make decisions based only on the present; sometimes the past matters too. That’s where sequential circuits come in. These circuits have a memory element, meaning their output depends on both current inputs and past states. Pretty cool, right? Let’s dive in!    

- [Intro to Sequential Circuits](https://www.geeksforgeeks.org/introduction-of-sequential-circuits/)
  
![image](https://github.com/user-attachments/assets/1710dfbd-31d4-4673-afed-03ddc86e6112)  
  📼 *Video 91*

---

### Latches and FlipFlops
First things first — you might be wondering, how do we even store data? How can a digital circuit remember anything?
Surprisingly, with just a clever arrangement of the basic logic gates we already know, it’s possible to build a circuit that holds on to its previous value. That’s the most fundamental unit of memory in digital electronics — the latch.

And when we make a few improvements to handle timing more reliably, we get the flip-flop — a more stable and practical memory element.

With just these two basic building blocks, we can create all sorts of memory-based circuits. So let’s dive in and see how they work!

- [Latches](https://www.geeksforgeeks.org/latches-in-digital-logic/) – These are the simplest memory elements in digital electronics that can store a single bit of data by feeding the output back into the input using logic gates.

![image](https://github.com/user-attachments/assets/ba2e0825-3069-4aa6-a74f-1cfbd4fb83d9)  

  
- [Flip-Flops](https://www.geeksforgeeks.org/flip-flop-types-their-conversion-and-applications/)– These are clock-controlled memory elements that store one bit of data and are more stable and reliable than latches, making them the building blocks of most sequential circuits.

  


- [Master-Slave Flip-Flop](https://www.geeksforgeeks.org/master-slave-jk-flip-flop/) – a setup where two flip-flops are connected in series: the master captures input when the clock is low, and the slave updates the output when the clock goes high. This separation helps eliminate glitches and ensures clean, synchronized output transitions.


<img src=https://github.com/user-attachments/assets/9dbd7ada-1089-4642-abcd-12ca602b85e9 width=600>

  📼 *Videos 92–117*
  
---
### Registers 

Okay, storing a single bit is cool and all — but let’s be real, that’s not going to take us very far. What we really want is to store multiple bits, and that’s exactly what registers are for.

At their core, registers are just a bunch of flip-flops lined up next to each other, working together. Depending on how we connect them, we get different types of registers like PIPO, PISO, SISO, SIPO, and the universal register.

Sounds a bit confusing? Don’t worry — it’s not as bad as it seems. Here's a quick breakdown:

- **P/S** stands for **Parallel/Serial** — parallel means all bits move at once, serial means one at a time.

- **I/O** just means **Input/Output**.

- And a **universal register** is like an all-rounder — it can handle everything.

With just this info, you can actually try building a simple register yourself! But if you want to understand it properly, here’s a solid resource:  

* [Register Circuits (PIPO, SISO, etc.)](https://www.geeksforgeeks.org/shift-registers-in-digital-logic/)

![image](https://github.com/user-attachments/assets/d441136a-6c19-4b48-bcb3-fec8cb4fc670)


  📼 *Videos 119–124*
