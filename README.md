# React Compound

**React Compound** is a curated collection of React projects aimed at equipping developers with the skills and confidence to tackle real-world challenges. This repository serves as both a learning hub and a portfolio builder for aspiring and experienced developers alike.

Each project is designed to teach specific React concepts, progressively introducing more advanced topics. By the end of this series, developers will have a solid foundation in React, along with an impressive portfolio of projects to showcase their skills.

---

## 📖 Purpose of This Repository

- **Learn React Step-by-Step**: Start with foundational projects to build core skills in JSX, state management, and component-based architecture.
- **Master Advanced Concepts**: Progress to extended projects that incorporate React hooks, routing, context API, and lifecycle methods.
- **Portfolio Building**: Each project is structured to be a portfolio-worthy example of your React expertise.
- **Real-World Scenarios**: Simulate common development challenges, from form validation to dynamic dashboards, to prepare for real-world applications.

Whether you’re a beginner taking your first steps into React or a developer looking to solidify your knowledge, this repository has something for everyone.

---

## 📫 How to Reach Me:

**Email**: [ktobia10@wgu.edu](mailto:ktobia10@wgu.edu)  
**LinkedIn**: [Kelvin R. Tobias](https://www.linkedin.com/in/kelvin-r-tobias-211949219/)  
**Bluesky**: [@kelvintechnical.bsky.social](https://bsky.app/profile/kelvintechnical.bsky.social)  
**Instagram**: [@kelvinintech](https://www.instagram.com/kelvinintech/)  

---

## About Me

Hi, my name is **Kelvin R. Tobias**, and I’m currently pursuing my **Software Engineering** degree at **Western Governors University**. My studies and personal projects have helped me gain experience in programming languages and frameworks, including **Python**, **JavaScript**, **Java**, **React**, and **C#**.



# React Developer Roadmap: From Beginner to Professional

## 📚 Table of Contents

### 🧠 React Foundations
1. [Introduction to React: Basic Setup and "Hello, World!"](#introduction-to-react-basic-setup-and-hello-world)
2. [Understanding React Components](#understanding-react-components)
3. [State in React (useState)](#state-in-react-usestate)
4. [Handling User Input (Forms)](#handling-user-input-forms)
5. [Conditional Rendering in React](#conditional-rendering-in-react)
6. [Introduction to useEffect Hook](#introduction-to-useeffect-hook)
7. [Event Handling in React](#event-handling-in-react)
8. [Use of Arrays and Objects in State](#use-of-arrays-and-objects-in-state)
9. [Updating State Based on Previous State](#updating-state-based-on-previous-state)
10. [Dynamic Rendering of Multiple Components](#dynamic-rendering-of-multiple-components)
11. [Managing Feedback in the App (State and Conditional Rendering)](#managing-feedback-in-the-app-state-and-conditional-rendering)
12. [Working with Timers and Delays (setTimeout and setInterval)](#working-with-timers-and-delays-settimeout-and-setinterval)
13. [Integrating Clipboard Functionality](#integrating-clipboard-functionality)
14. [Code Review and Refactoring](#code-review-and-refactoring)

### 🚀 Building Projects
15. [Building the Final Project: Line-by-Line Code Training](#building-the-final-project-line-by-line-code-training)
16. [RESTful API Integration (Frontend to Backend)](#restful-api-integration-frontend-to-backend)
17. [Using PostgreSQL with Neon or Supabase](#using-postgresql-with-neon-or-supabase)
18. [Using External APIs (GitHub, OpenWeather, etc.)](#using-external-apis-github-openweather-etc)

### 💡 Advanced React Concepts
19. [Custom Hooks](#custom-hooks)
20. [Context API](#context-api)
21. [React.memo, useMemo, useCallback](#reactmemo-usememo-usecallback)
22. [Error Boundaries](#error-boundaries)
23. [Forward Refs and useImperativeHandle](#forward-refs-and-useimperativehandle)
24. [Portals and Modals](#portals-and-modals)
25. [Compound Component Pattern](#compound-component-pattern)

### 🌐 React Ecosystem & Tools
26. [Routing with React Router](#routing-with-react-router)
27. [React Query / TanStack Query](#react-query--tanstack-query)
28. [Global State with Zustand or Redux Toolkit](#global-state-with-zustand-or-redux-toolkit)
29. [Form Libraries (React Hook Form, Formik)](#form-libraries-react-hook-form-formik)
30. [UI Component Libraries (Tailwind CSS, ShadCN, Material UI)](#ui-component-libraries-tailwind-css-shadcn-material-ui)
31. [Animations with Framer Motion](#animations-with-framer-motion)

### 🧪 Testing and Quality
32. [Unit Testing with Jest and RTL](#unit-testing-with-jest-and-rtl)
33. [Integration and E2E Testing with Cypress](#integration-and-e2e-testing-with-cypress)
34. [Linting, Formatting, and Code Standards](#linting-formatting-and-code-standards)
35. [CI/CD with GitHub Actions or Vercel](#cicd-with-github-actions-or-vercel)

### 🏗️ Real-World Features & DevOps
36. [Authentication with JWT, Auth0, or NextAuth](#authentication-with-jwt-auth0-or-nextauth)
37. [Role-Based Access Control (RBAC)](#role-based-access-control-rbac)
38. [File Uploads (Cloudinary, Firebase)](#file-uploads-cloudinary-firebase)
39. [Real-time Features with WebSockets](#real-time-features-with-websockets)
40. [Internationalization (i18n)](#internationalization-i18n)
41. [PWA and Offline Access](#pwa-and-offline-access)
42. [Monitoring and Logging (Sentry, LogRocket)](#monitoring-and-logging-sentry-logrocket)

### 🌐 Portfolio and Deployment
43. [Next.js Portfolio Site (SSR or SSG)](#nextjs-portfolio-site-ssr-or-ssg)
44. [Responsive and Accessible Design](#responsive-and-accessible-design)
45. [Dark Mode Toggle](#dark-mode-toggle)
46. [Secure Contact Form](#secure-contact-form)
47. [Site Performance Optimization](#site-performance-optimization)
48. [Deploying with Vercel, Netlify, or AWS](#deploying-with-vercel-netlify-or-aws)

### 🧩 Project Showcase & Case Studies
49. [Detailed Case Studies](#detailed-case-studies)
- [ ] Problem Solved  
- [ ] Approach Taken  
- [ ] Results Achieved  
---

## 1. Introduction to React: Basic Setup and "Hello, World!"

**Goal:** Learn to set up a React app and display a basic output in the browser.
- Create a simple React app with `create-react-app`.
- Render the text "Hello, World!" inside a `<h1>` tag.

## 2. Understanding React Components

**Goal:** Learn about functional components in React.
- Create a simple component to display a greeting message.
- Use JSX to render content inside the component.

## 3. State in React (useState)

**Goal:** Learn how to use React state with `useState`.
- Create a button that toggles between two messages ("Hello" and "Goodbye").
- Use `useState` to update the state and re-render the component.

## 4. Handling User Input (Forms)

**Goal:** Learn to handle user input through forms.
- Create an input field and a button.
- Use `useState` to capture the input and display it dynamically.

## 5. Conditional Rendering in React

**Goal:** Learn to conditionally render content based on the state.
- Display different content based on whether a user has typed something in the input field or not.

## 6. Introduction to useEffect Hook

**Goal:** Learn how to run side effects in React components using `useEffect`.
- Set up an effect that runs when the component mounts.
- Display a message when the component is first rendered.

## 7. Event Handling in React

**Goal:** Learn how to handle user actions such as clicks.
- Add a button that, when clicked, updates a state variable.
- Display feedback based on the button click (e.g., "Button clicked!").

## 8. Use of Arrays and Objects in State

**Goal:** Learn how to store and manipulate arrays/objects in state.
- Set up a list of items in state and display them dynamically.
- Add functionality to add new items to the list.

## 9. Updating State Based on Previous State

**Goal:** Learn to update state based on the previous state.
- Create a counter that increments or decrements by 1 when buttons are clicked.

## 10. Dynamic Rendering of Multiple Components

**Goal:** Learn how to dynamically render components from an array.
- Render a list of components based on an array in state.
- Use the `.map()` method to iterate through the array and display the components.

## 11. Managing Feedback in the App (State and Conditional Rendering)

**Goal:** Learn to provide feedback to users based on actions (correct/incorrect).
- Create a simple feedback system that displays success or error messages after form submission.

## 12. Working with Timers and Delays (setTimeout and setInterval)

**Goal:** Learn how to use JavaScript timers in React.
- Create a timer that shows a countdown and then triggers a specific action (like showing feedback).

## 13. Code Review and Refactoring

**Goal:** Learn to refactor code for readability and maintainability.
- Refactor the previous projects into smaller reusable components.
- Separate logic, UI, and feedback into different functions or components.

## 14. Integrating Clipboard Functionality

**Goal:** Learn how to interact with the browser’s clipboard API.
- Create a "Copy to Clipboard" feature that copies some text or code from the page.
- Provide user feedback on whether the copy operation succeeded.

## 15. Building the Final Project: Line-by-Line Code Training

**Goal:** Combine all the learned skills into the final app.
- Create a stateful app that displays code lines and their corresponding explanations.
- Allow users to input their code and provide real-time feedback (correct or incorrect).
- Use state to manage the growing project code and user input.

---

## Conclusion

By the end of these projects, you'll have gained a solid understanding of React's core concepts, and you'll have built a full-featured app that teaches users how to code line-by-line. Each project in this guide builds on the previous one, enabling you to develop the necessary skills in a progressive, easy-to-follow manner.


## 20. Debugging with React Strict Mode
**Skills:** React Strict Mode, Lifecycle Methods  
- Create a timer app where users can start/stop/reset a timer.  
- Use Strict Mode to catch potential issues with state updates and effects.  
[Link to Project](#) <!-- Add the project link here -->
