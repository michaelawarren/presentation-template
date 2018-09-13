---
title: Clean Architecture
theme: night
---

> If our designs are failing due to the constant rain of changing requirements, it is our designs that are at fault. We must somehow find a way to make our designs resilient to such changes and protect them from rotting.
> ~ Robert Cecil Martin

---

# Clean Architecture
## An overview

---

## Source
Robert Martin's Clean Architecture

note:
Robert Martin's Credentials
* Author
* decades of experiance as a software engineer in many diverse fields

The goal of this presentation is to give a very high level overview of the book. It is not ment to be a deep dive into pratical application but a taste to give you a desire to want more.

---

## Overview
* Why Clean Architecture Matters
* What is Clean Architecture

---

## Why Clean Architecture Matters
* Cost of Poor Architecture
* The Two values

----

## Cost of Poor Architecture

insert charts from book

note:
This is where i want to show the charts in the book about the project that after 8 release cycles the project's productivity platues even though the number of developers on the project continues to increase.
The author points out that he has worked on projects where the architecture is clean and changes are quick to make.

----

## The Tale of two values
* Behavior
* Architecture

note:
Behavior is what the system does
Architecture is making the system easy to change
most software developers focus on behavior without much thought to the architecture of the system

---

## What is Clean Architecture
* SOLID
* Component Cohesion
* Component Coupling

----

## SOLID

----

## Component Cohesion
### The Reuse/Release Equivalence Principle

----

## Component Cohesion


----

### The Common Closure Principle

----

### The Common Reuse Principle

----

### Tension diagram

----

## Component Coupling

----

### The Acyclic Dependencies Principle
> Allow no cycles in the component dependency graph

----

### The Stable Dependencies Principles
> Depend in the direction of stability

> I = Fan-out / (Fan-in + Fan-out)

----

### The Stable Abstraction Principle
> A component should be as abstract as it is stable

----

### The Zone of Pain and Uselessness

---

## Questions

---

## feedback
insert link to feedback survey