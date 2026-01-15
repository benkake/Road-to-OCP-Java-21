# Road-to-OCP-Java-21
A comprehensive roadmap for the Oracle Certified Professional (OCP) Java SE 21 certification. Includes daily hands-on projects, detailed study notes, and exam-focused exercises based on the official 1Z0-830 curriculum.

This repository serves as a personal learning log and portfolio for the Java SE 21 Developer (1Z0-830) certification. It follows the structured path of the OCP Oracle Certified Professional Java SE 21 Developer Study Guide by Selikoff and Boyarsky.

Key Features:
- Daily Progression: From Java foundations to advanced topics like Virtual Threads and Sequenced Collections.
- Real-World Projects: Practical implementations such as a System Info Tool, CSV Analyzer, and JDBC-based applications.
- Cloud Integration: Integration with Oracle Autonomous Database (ADB) via JDBC.
- Exam Strategies: Notes on 'gotchas,' edge cases, and simulation results from tools like Enthuware

I am following a structured learning path based on the "OCP Java 21 Study Guide" by Selikoff & Boyarsky[cite: 20, 21].

## 📅 Roadmap
**Step 1:** Java Foundations & OOP Basics 
**Step 2:** Classes, Design & Inheritance 
**Step 3:** Interfaces, Generics & Collections 
**Step 4:** Lambdas, Streams & Exceptions 
**Step 5:** I/O, NIO.2 & Concurrency 
**Step 6:** Modules, Deployment & JDBC 
**Step 7:** Oracle Cloud (ADB) Integration 
**Step 8:** Final Review & Simulations 

## 🛠️ Current Project: Day 1 - Java System Info Tool
**Goal:** Master the basics of the JDK and the `System` class.

### Key Learning Objectives:
*Difference between `javac` (compiler) and `java` (launcher).
*Using JShell for rapid prototyping.
*Accessing environment metadata via `System.getProperty()`.

### OCP Exam Insight:
> In Java 21, the `System.getProperty(String key)` method returns `null` if the key does not exist. It does **not** throw an exception. This is a classic "gotcha" question on the exam.


*Created and maintained by Bonaventure KAKE K.*

