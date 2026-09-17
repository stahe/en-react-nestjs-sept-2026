# RdvMedecins - A Client/Server Example with NestJS and React

This repository accompanies a course on rebuilding a client/server medical appointment scheduling application (`RdvMedecins`) using modern tools. It contains only this README; the complete course is available online.

## 📖 Read the course

**[https://stahe.github.io/en-react-nestjs-sept-2026](https://stahe.github.io/en-react-nestjs-sept-2026)**

## About

This document adapts an original 2014 course (*A Client/Server Example - AngularJS 1.x / Spring 4*) to current technologies:
- The server, written in Java with Spring MVC, is replaced by a **NestJS** server (TypeScript);
- the **AngularJS 1.x** client is replaced by a **React** client (functional components, hooks);
- the core functionality and the database remain unchanged in principle, with the addition of role-based authentication (JWT), which was absent from the original.

This course was written with the assistance of the AI Claude (Anthropic), which generated most of the code and explanations; the author tested and validated the entire course by following the generated document.

## Course Content

1. **Introduction** - Objectives, prerequisites, general application architecture
2. **Chapter 1** - Setting up the development environment
3. **Chapter 2** - Introduction to NestJS
4. **Chapter 3** - The NestJS server for the RdvMedecins application
5. **Chapter 4** - Introduction to React
6. **Chapter 5** - The React client for the RdvMedecins application
7. **Chapter 6** - Conclusion and next steps

## Technologies Covered

- **Server**: NestJS, TypeORM, MySQL, JWT authentication (`@nestjs/passport`, `@nestjs/jwt`), role-based access control
- **Client**: React 19, Vite, TypeScript, hooks, i18next (French/English internationalization), Bootstrap

## Prerequisites

No prior knowledge of NestJS or React is required. A basic understanding of JavaScript, HTTP, and the command line is sufficient to successfully complete the course.

## Authors

IA Claude (primarily) and Serge Tahé (code testing and course review)
