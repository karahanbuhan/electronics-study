# Building Basic Logic Gates with Transistors

This project showcases the implementation of fundamental digital logic gates (**AND**, **OR**, **NOT**, **XOR**, and **BUFFER**) using basic electronic components like transistors on a breadboard. Each circuit demonstrates the core principles of digital electronics.

---

## AND Gate

An **AND** gate is a basic digital logic gate that implements logical conjunction. The output is HIGH (1) only when **both** of its inputs are HIGH (1).

#### Truth Table

| Input A | Input B | Output |
| :-----: | :-----: | :----: |
|    0    |    0    |   0    |
|    0    |    1    |   0    |
|    1    |    0    |   0    |
|    1    |    1    |   1    |

#### Schematic
![AND Gate Schematic](./and-schematic.jpeg)

#### Breadboard Setup
![Photo of the AND gate circuit](./and.png)

#### Demonstration
[Watch the AND Gate in action](./and.mp4)

---

## OR Gate

An **OR** gate is a digital logic gate that implements logical disjunction. The output is HIGH (1) if **one or more** of its inputs are HIGH (1).

#### Truth Table

| Input A | Input B | Output |
| :-----: | :-----: | :----: |
|    0    |    0    |   0    |
|    0    |    1    |   1    |
|    1    |    0    |   1    |
|    1    |    1    |   1    |

#### Schematic
![OR Gate Schematic](./or-schematic.jpeg)

#### Breadboard Setup
![Photo of the OR gate circuit](./or.png)

#### Demonstration
[Watch the OR Gate in action](./or.mp4)

---

### NOT Gate (Inverter)

**Schematic Symbol:**

![NOT Gate Schematic](not-schematic.png)

**Demo / Principle of Operation:**

*Note: Click the image to watch the video.*

[![NOT Gate Demo](not.png)](not.mp4)

---

## XOR (Exclusive-OR) Gate

The **Exclusive-OR (XOR)** gate is a digital logic gate that gives a HIGH (1) output only if its two inputs are **different**.

#### Truth Table

| Input A | Input B | Output |
| :-----: | :-----: | :----: |
|    0    |    0    |   0    |
|    0    |    1    |   1    |
|    1    |    0    |   1    |
|    1    |    1    |   0    |

#### Schematic
![XOR Gate Schematic](./xor-schematic.png)

#### Breadboard Setup
![Photo of the XOR gate circuit](./xor.png)

#### Demonstration
[Watch the XOR Gate in action](./xor.mp4)

---

## BUFFER Gate

A **BUFFER** gate doesn't perform any logical operation; its output is simply equal to its input. Buffers are primarily used to amplify a weak signal or to isolate different parts of a circuit.

#### Truth Table

| Input A | Output |
| :-----: | :----: |
|    0    |   0    |
|    1    |   1    |

#### Schematic
![BUFFER Gate Schematic](./buffer-schematic.jpeg)

#### Breadboard Setup
![Photo of the BUFFER gate circuit](./buffer.jpeg)
