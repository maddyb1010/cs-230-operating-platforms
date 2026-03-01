# cs-230-operating-platforms

Software design and architecture project for The Gaming Room. Includes system design documentation and Java implementation using Singleton and Iterator patterns.

---

## Project Overview

In this course, I worked as a technology consultant for The Gaming Room. The client wanted to expand their existing Android game, *Draw It or Lose It*, into a web based application that could support multiple operating systems and devices. The goal was to design a scalable system that allows multiple teams and players while enforcing unique names and ensuring that only one instance of the game service exists in memory at a time.

This repository includes both a full software design document and a working Java prototype demonstrating object oriented programming principles and design patterns.

---

## Key Implementation Highlights

The application uses a structured domain model with a shared `Entity` base class to promote inheritance and code reuse. The `GameService` class is implemented using the Singleton pattern to ensure that only one instance exists in memory. Iteration logic is used to enforce unique game, team, and player names before creating new objects.

The system architecture section of the design document evaluates Linux, Windows, macOS, and mobile platforms, and proposes a scalable web based deployment approach.

---

## Reflection

This project strengthened my ability to translate business requirements directly into technical design decisions. Completing the software design document before finalizing the implementation helped me think more strategically about system architecture, scalability, memory management, and security instead of jumping straight into code.

If I were to revise this project, I would expand further on distributed systems and security considerations, particularly in areas such as authentication strategies and fault tolerance. Overall, this project reinforced how important early design decisions are to long term system growth and maintainability.
