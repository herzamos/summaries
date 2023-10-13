# Concepts of Objects Oriented Programming

## Table of Contents

- [Concepts of Objects Oriented Programming](#concepts-of-objects-oriented-programming)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
    - [Requirements](#requirements)
    - [Core Concepts](#core-concepts)
      - [1: The Object Model](#1-the-object-model)
      - [2: Interfaces and Encapsulation](#2-interfaces-and-encapsulation)
      - [3: Classification and Polymorphism](#3-classification-and-polymorphism)
  - [There exist various forms of polymorphism:](#there-exist-various-forms-of-polymorphism)
  - [Typing](#typing)
  - [Inheritance](#inheritance)

## Introduction

### Requirements
Every OOP language is (or should be) developed with the aim of solving a set of requirments,  shown in the picture below. 
![Requirments of an OOP language](<images/Screenshot 2023-10-13 at 14.43.41.png>)

### Core Concepts

#### 1: The Object Model
In every OOP language, **a software system is a set of cooperating objects**, which **exchange messages**. In the figure below, two objects `obj1`and `obj2` can be seen exchanging a message, in the form of a *method call*.
Every object has:
- State
- Identity
- Lifecycle
- Location
- Behavior

![Objects interaction](<images/Screenshot 2023-10-13 at 15.10.45.png>)

#### 2: Interfaces and Encapsulation
Each object has a well-defined interface, which describes its **publicly accessible fields and methods**. **Encapsulation** refers to the bundling of data with the methods that operate on that data, and is often used to hide the values or state of a structured data object inside a class.

#### 3: Classification and Polymorphism
We call **classification** the process of hierarchicarly structuring objects. Each object **can belong to different classes simultaneously**, an example is provided below.
This lead to the **substitution principle**: each object of a type `S` which is subtype of a type `T` can be used whenever the supertype `T` is expected. Looking at the example below, if a method expects an object of type `Assistant`, it will also accept an object of type `PhD Student` (but not `bachelor Student` or `Master Student`!).

![Classification example](<images/Screenshot 2023-10-13 at 16.25.41.png>)

We call a program part **polymorphic** if it can be used for objects of several classes.
There exist various forms of polymorphism:
- 

## Typing


## Inheritance

<!-- aa
<table><tr>
<th>Json 1</th>
<th>Markdown</th>
</tr><tr><td><pre>

```json
{
  "id": 1,
  "username": "joe",
  "email": "joe@example.com",
  "order_id": "3544fc0"
}
```
</pre></td><td>

```json
{
  "id": 5,
  "username": "mary",
  "email": "mary@example.com",
  "order_id": "f7177da"
}
```
</td></tr></table> -->
