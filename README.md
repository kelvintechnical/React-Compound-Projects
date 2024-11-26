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

I believe the best way to learn is by building, which is why I spend my free time creating projects to reinforce my skills. Through this repository, I aim to help others on their learning journey while continuing to grow as a developer.

---


# React Project Series: Foundational and Extended Projects

## Phase 1: Foundational React Projects

### [1. Welcome to Banking App](https://github.com/kelvintechnical/welcome-to-banking/tree/main)
**Goal:** Create a React app that displays "Welcome to Banking" and introduces state variables for account balance and user name.  
**Skills:** React basics, functional components, and `useState`.

### [2. User Input Form](https://github.com/kelvintechnical/-User-Input-Form/blob/main/README.md)
**Goal:** Build a form where users can input their name and account balance. Display the entered details on the screen.  
**Skills:** Handling forms, `useState` for managing form data.

### 3. Account Balance Checker

## **Progression Chart**

| Project # | Name                         | Goal                                     | Key Concepts                                                                                   | Output                                                                                   |
|-----------|------------------------------|-----------------------------------------|------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|
| 1         | React Basics - Hello React   | Learn React basics                      | Components, props, state, and handling user input.                                             | A web app that greets the user by name based on input.                                   |
| 2         | Styling in React             | Apply styling to components             | CSS modules, inline styling, conditional styling, and responsive design.                      | A styled greeting app with improved UI and layout.                                       |
| 3         | React Context API - User Profile | Manage global state using Context API | Context and Provider setup, consuming and updating context values.                            | A user profile app with a globally accessible and editable username.                    |
| 4         | Fetching Data with React     | Fetch and display data from an API      | `useEffect`, API calls (`fetch`/`axios`), loading/error states, and displaying dynamic lists.  | An app that fetches and displays mock account details with loading/error messages.       |
| 5         | Testing with Jest            | Write unit tests for React components   | Jest, React Testing Library, mocking API calls and context, and writing comprehensive tests.  | A test suite that verifies the functionality of the user profile app.                   |

Account Balance Checker**

### **Goal:** Combine all skills to build the final app.

1. **Objective:** Build the complete Account Balance Checker app using:
   - React Context for managing account details.
   - API calls to fetch user account balances.
   - A styled UI for account details.
   - Unit tests for critical features.
2. **Key Concepts:**
   - Integrating Context, API calls, and testing.
   - Finalizing responsive design.
   - Adding conditional rendering (e.g., no data/error states).
3. **Output:** A fully functional Account Balance Checker app.

**Technologies:**  
- [React Context API](https://reactjs.org/docs/context.html): To manage global state for the account balance.  
- [Jest](https://jestjs.io/): For unit testing the balance checking logic.

---

### 4. Fixed Deposit Tracker
**Goal:**  
Create a button to add fixed deposit amounts to the account balance. Use a loop to simulate 5 deposits and update the balance iteratively.

**Skills:**  
- `useState`, event handling, and loops in React.

**Technologies:**  
- [Redux](https://redux.js.org/): To manage state across multiple components.  
- [Lodash](https://lodash.com/): For simplifying array operations and loops.

---

### 5. Personalized Welcome Component
**Goal:**  
Display a personalized welcome message using the user’s name and formatted account balance.

**Skills:**  
- Props, state management, and string interpolation.

**Technologies:**  
- [Styled Components](https://styled-components.com/): For styling the welcome message dynamically.  
- [i18next](https://www.i18next.com/): For handling internationalization and localization of messages.

---

## Phase 2: Extended React Projects

### 6. Input Validation Form
**Goal:**  
Validate user inputs (e.g., ensure the account balance is numeric). Show error messages for invalid inputs.

**Skills:**  
- Form validation.  
- Conditional rendering for error messages.

**Technologies:**  
- [Formik](https://formik.org/): For managing form state and validation.  
- [Yup](https://github.com/jquense/yup): For schema validation.

---

### 7. Multi-User Banking Dashboard
**Goal:**  
Allow adding multiple users with their names and account balances. Display a list of all users with their details.

**Skills:**  
- Managing lists with React state.  
- Rendering dynamic lists.

**Technologies:**  
- [React Query](https://tanstack.com/query): For fetching and managing user data from a server.  
- [Material-UI](https://mui.com/): For creating a responsive and interactive user interface.

---

### 8. Account Balance Threshold Notifier
**Goal:**  
Notify the user dynamically (e.g., red text for low balance and green text for sufficient balance) when they input their balance.

**Skills:**  
- Dynamic class names.  
- Inline styling.  
- Conditional rendering.

**Technologies:**  
- [Styled Components](https://styled-components.com/): For dynamic styling based on balance.  
- [React Spring](https://react-spring.dev/): For adding smooth animations to balance notifications.

---

### 9. Transaction Simulator
**Goal:**  
Add a feature for users to "deposit" or "withdraw" money. Update the balance dynamically based on their transactions.

**Skills:**  
- Event handling.  
- State updates based on user actions.

**Technologies:**  
- [Recoil](https://recoiljs.org/): For simplified state management.  
- [React Transition Group](https://reactcommunity.org/react-transition-group/): For adding transitions to transaction updates.

---

### 10. Welcome Carousel
**Goal:**  
Create a rotating carousel of personalized welcome messages for multiple users.

**Skills:**  
- React component lifecycle.  
- `useState` and `useEffect`.

**Technologies:**  
- [React-Slick](https://react-slick.neostack.com/): For creating a responsive and customizable carousel.  
- [Framer Motion](https://www.framer.com/motion/): For adding animations to the carousel transitions.

---

### Project Links
- [Welcome to Banking App](#welcome-to-banking-app)
- [User Input Form](#user-input-form)
- [Account Balance Checker](#account-balance-checker)
- [Fixed Deposit Tracker](#fixed-deposit-tracker)
- [Personalized Welcome Component](#personalized-welcome-component)
- [Input Validation Form](#input-validation-form)
- [Multi-User Banking Dashboard](#multi-user-banking-dashboard)
- [Account Balance Threshold Notifier](#account-balance-threshold-notifier)
- [Transaction Simulator](#transaction-simulator)
- [Welcome Carousel](#welcome-carousel)


# 20 React Projects to Learn Essential Skills

## 1. JSX Introduction: Todo List
**Skills:** Understanding JSX, Components  
- Create a simple Todo List app where users can add and display tasks.  
- Learn how to use JSX to render the UI and break the app into functional components.  
[Link to Project](#) <!-- Add the project link here -->

---

## 2. Counter App
**Skills:** State Management, Functional Components  
- Build a Counter app with buttons to increment and decrement a value.  
- Use `useState` for managing the counter value and functional components for structure.  
[Link to Project](#) <!-- Add the project link here -->

---

## 3. User Profile Card
**Skills:** Props, Functional Components  
- Create a reusable user profile card that accepts user details (name, photo, bio) as props.  
- Focus on passing and rendering props in components.  
[Link to Project](#) <!-- Add the project link here -->

---

## 4. Weather Dashboard
**Skills:** Lifecycle Methods, State Management  
- Build a weather app that fetches weather data using an API.  
- Use `useEffect` for fetching data on component mount and `useState` for managing API responses.  
[Link to Project](#) <!-- Add the project link here -->

---

## 5. Simple Blog Navigation
**Skills:** React Router, Components  
- Create a blog app with navigation between Home, About, and Posts pages using React Router.  
- Structure the app with reusable components for each page.  
[Link to Project](#) <!-- Add the project link here -->

---

## 6. Theme Switcher
**Skills:** React Context, State Management  
- Build a theme switcher (dark mode/light mode) using React Context for global state sharing.  
- Use `useState` to toggle between themes.  
[Link to Project](#) <!-- Add the project link here -->

---

## 7. Form Validator
**Skills:** Custom Hooks, State Management  
- Create a form validator app with fields for email and password.  
- Build a custom hook for validation logic, reusing it across multiple fields.  
[Link to Project](#) <!-- Add the project link here -->

---

## 8. Error-Handled Calculator
**Skills:** Error Boundaries, Functional Components  
- Develop a basic calculator that handles invalid operations (e.g., division by zero) with an error boundary.  
- Learn to isolate errors in components using `componentDidCatch`.  
[Link to Project](#) <!-- Add the project link here -->

---

## 9. Debugging with Strict Mode: Feedback Form
**Skills:** React Strict Mode, State Management  
- Create a feedback form app where users can submit their feedback.  
- Use React Strict Mode to debug and identify best practices in your component structure.  
[Link to Project](#) <!-- Add the project link here -->

---

## 10. Image Gallery with Pagination
**Skills:** React Router, Lifecycle Methods  
- Build an image gallery with multiple pages using React Router for navigation.  
- Use `useEffect` to fetch images dynamically when navigating between pages.  
[Link to Project](#) <!-- Add the project link here -->

---

## 11. Context-Based Authentication
**Skills:** React Context, Props  
- Build a simple authentication system with login/logout functionality.  
- Use Context to manage the authentication state and pass it down via props.  
[Link to Project](#) <!-- Add the project link here -->

---

## 12. E-Commerce Cart
**Skills:** State Management, Props  
- Build a shopping cart that displays selected items and their total price.  
- Use `useState` to manage the cart state and props to display item details.  
[Link to Project](#) <!-- Add the project link here -->

---

## 13. Dynamic Dropdown Menu
**Skills:** Custom Hooks, Props  
- Create a dynamic dropdown menu where options are passed as props.  
- Write a custom hook to handle dropdown open/close state and logic.  
[Link to Project](#) <!-- Add the project link here -->

---

## 14. Blog Post Editor
**Skills:** Lifecycle Methods, Props  
- Build a blog post editor that fetches existing posts and allows editing.  
- Use `useEffect` to fetch the initial data and props to pass the post content to components.  
[Link to Project](#) <!-- Add the project link here -->

---

## 15. Task Manager with Context
**Skills:** React Context, Functional Components  
- Create a task manager app with categories (e.g., Work, Personal).  
- Use Context to manage tasks globally and functional components for structure.  
[Link to Project](#) <!-- Add the project link here -->

---

## 16. Error-Tolerant Search Bar
**Skills:** Error Boundaries, Lifecycle Methods  
- Develop a search bar that fetches and displays suggestions but gracefully handles API errors.  
- Implement error boundaries to catch issues with data fetching logic.  
[Link to Project](#) <!-- Add the project link here -->

---

## 17. Themed User Profiles
**Skills:** React Context, Custom Hooks  
- Build a user profile app with global theme support and reusable custom hooks for fetching user data.  
- Use Context for theme state and hooks for API logic.  
[Link to Project](#) <!-- Add the project link here -->

---

## 18. Navigation Bar
**Skills:** React Router, Props  
- Create a dynamic navigation bar where routes and labels are passed as props.  
- Implement navigation with React Router to switch between views.  
[Link to Project](#) <!-- Add the project link here -->

---

## 19. Data Table with Pagination
**Skills:** State Management, Lifecycle Methods  
- Build a data table displaying paginated user information fetched from an API.  
- Use `useState` to manage pagination state and `useEffect` for data fetching.  
[Link to Project](#) <!-- Add the project link here -->

---

## 20. Debugging with React Strict Mode
**Skills:** React Strict Mode, Lifecycle Methods  
- Create a timer app where users can start/stop/reset a timer.  
- Use Strict Mode to catch potential issues with state updates and effects.  
[Link to Project](#) <!-- Add the project link here -->
