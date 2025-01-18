---
type: PostLayout
title: How to make a Computer from Scratch (Part 1)
date: '2024-11-29'
author: content/data/person1.json
excerpt: >-
  This part 1 will introduce you a beginner friendly tutorial to make a simple
  computer from scratch.
featuredImage:
  type: ImageBlock
  url: /images/cpu.png
  altText: Thumbnail
  elementId: ''
  styles:
    self:
      padding:
        - pt-0
        - pl-0
        - pb-0
        - pr-0
bottomSections:
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-3
          - pl-3
          - pb-3
          - pr-3
  - type: RecentPostsSection
    title:
      type: TitleBlock
      text: Recent posts
      color: text-dark
      styles:
        self:
          textAlign: center
    recentCount: 3
    showThumbnail: true
    showExcerpt: true
    showDate: true
    showAuthor: true
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
slug: how-to-make-a-computer-from-scratch-part-1
isFeatured: false
isDraft: false
seo:
  type: Seo
  metaTitle: lorem-ipsum
  metaDescription: lorem-ipsum
  addTitleSuffix: false
  metaTags: []
colors: bg-light-fg-dark
styles:
  self:
    flexDirection: col
---
### **Building a Simple MIPS Architecture Computer: A Beginner's Guide**

Welcome to Part 1 of this exciting journey! In this tutorial, you'll learn how to build a Microprocessor without Interlocked Pipelined Stages (MIPS) architecture computer from scratch. Get ready to dive into the fundamentals and create your very own simple computing engine!

### **What Will We Cover?**

In this section, we’ll explore the essential building blocks for constructing your MIPS architecture computer, including:

1.  **Transistors and How They Work (Part 1)** Learn the basics of transistors, the building blocks of modern electronics, and how they enable the operation of a computer.

2.  **Basics of Computer Systems (Part 2)**
    Understand what makes a computer tick, from fundamental concepts to how components work together.

3.  **Assembling and Coding in Low-Level Languages (Part 3)**
    Gain insights into assembling hardware and programming it using low-level languages to bring your computer to life.

### **Understanding Simple Computers**

At its core, a computer is a machine designed to perform calculations and solve problems. In this project, we’ll construct a basic computing engine based on MIPS architecture to simulate its functionality.

#### Why MIPS?

MIPS is a simplified microprocessor design that’s perfect for learning the fundamentals of how a computer operates. By building a MIPS-based computer, you’ll get hands-on experience with concepts like:

*   Instruction sets
*   Data processing
*   Low-level programming

#### What Will the Final Computer Look Like?

Our computer will be simple, stripped down to its essential features, and won’t include an operating system. This simplicity allows us to focus entirely on understanding the underlying architecture and operation.

### **Transistor and How It Works**

Transistors are the fundamental building blocks of all modern electronic devices. At their core, they are semiconductor devices that act as switches or amplifiers. Their significance becomes even clearer when diving into the architecture of systems like MIPS, which rely on binary logic to perform computations. Here's a detailed look at why transistors are crucial, particularly in the context of logic gates and computing:

#### Why Transistors Matter

Transistors are vital because they provide the mechanism to handle binary states, **HIGH (1)** and **LOW (0)**, which form the basis of digital computing. In the MIPS architecture (or any digital computing system), computations are performed by manipulating these binary states. Transistors enable this by acting as:

1.  **Switches:** Allowing or blocking the flow of electrical current, corresponding to binary 1 (HIGH) and 0 (LOW).

2.  **Amplifiers:** In analog circuits, they can amplify weak signals, though their role as switches is more relevant in digital systems.

#### Transistors and Logic Gates

A **logic gate** performs basic logical functions like AND, OR, NOT, NAND, NOR, XOR, etc., using combinations of binary inputs and outputs. Transistors, arranged in specific configurations, make up these gates.

For instance:

*   **NOT Gate:** Uses a single transistor. If the input is 1 (high voltage), the transistor turns on and outputs 0 (low voltage).

*   **AND Gate:** Typically uses multiple transistors to ensure the output is 1 only when all inputs are 1.

These logic gates are combined to create more complex circuits like adders, multiplexers, and ultimately, processors.

#### Types of Transistors

Understanding different types of transistors is crucial for designing efficient circuits:

1.  **BJT (Bipolar Junction Transistor):**

    *   Operates using current control.

    *   Less common in modern digital circuits due to higher power consumption.

2.  **FET (Field-Effect Transistor):**

    *   Voltage-controlled device.

    *   More energy-efficient and used in many modern applications.

3.  **MOSFET (Metal-Oxide-Semiconductor FET):**

    *   A subtype of FET.

    *   Dominates in digital electronics, including CPUs, due to its efficiency, speed, and scalability.

#### Transistor as Traditional Logic Gates

In traditional logic circuits, transistors are connected in arrangements that implement specific logical operations. For example:

*   **NAND Gate as Universal Gate:** A combination of BJTs can create a NAND gate, which is significant because all other gates (AND, OR, NOT, etc.) can be constructed from it.

To make NAND Gate, need 2 BJT, with 2 input, a ground, and a VCC. You can use another type of transistor like FET or MOSFET to make a logic gate, but in this tutorial, we will use a BJT.

![](/images/logic_gates_1.jpg)

src: [CPUville](http://cpuville.com/Educational/Logic-gates.html)

Now, we already have a NAND Gate, what will we do next is to know more about logic gates, how to use it, and anything else that will be served in PART 2.
