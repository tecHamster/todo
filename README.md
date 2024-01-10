# React Todo App

[**Visit the Website**](https://techamster.github.io/todo/)

## Overview
This project implements a todo list application with user registration, authentication, and CRUD operations for managing todos. It includes functionalities such as creating, editing, deleting todos, filtering by status, and toggling todo completion status.

**Performance Metrics:**
  ![Lighthouse Scores](https://imgdb.net/storage/uploads/f7b59a6cdaa643d9d0d987d8a6bf1d252ac8b1bda55097e37a27a984781b09a2.png)
  - [Test Performance Here](https://pagespeed.web.dev/analysis/https-techamster-github-io-backery/1pma2mu6ed?form_factor=desktop)

## Features
**User Registration and Authentication:**
  - Register users via email.
  - Authenticate users to access the application.

**Todo Management:**
  - Create todos with titles.
  - Edit todo titles.
  - Delete individual todos and clear completed todos.
  - Filter todos by status (All, Active, Completed).

**API Interaction:**
  - Utilizes API endpoints for user registration, authentication, and managing todos.
  - Handles error cases and displays appropriate notifications.

**User Interface:**
  - Responsive UI design.
  - Hides elements based on todo status to optimize user experience.

## Implementation Details
**Tech Stack:**
  - React: JavaScript library for building user interfaces.
  - React Hooks: Utilized `useState`, `useEffect`, `useContext`, `useRef` for managing component state and lifecycle methods.
  - Classnames: Library for conditional CSS classes in React components.
  - React Transition Group: Used for implementing animations within the application.
  - SCSS: Preprocessor scripting language for styling.
  - Bulma: CSS framework for building responsive web designs.
  - Font Awesome: Icon toolkit for adding vector icons and social logos.

**Usage:**
  - Register/Login using your email.
  - Create, edit, and delete todos.
  - Filter todos based on status.

**Error Handling:**
  - Displays appropriate error messages for failed API requests or invalid operations.
