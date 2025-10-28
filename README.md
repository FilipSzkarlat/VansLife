## 🚀 VansLife - A Modern Van Rental Application

**Live Demo (Netlify):** [https://vanslifebyfilip.netlify.app/](https://vanslifebyfilip.netlify.app/)

**VansLife** is a comprehensive **Frontend project** built with **React.js**, designed to showcase advanced skills in building **scalable and secure** web applications. The app simulates a vehicle rental platform with a public-facing catalog and a secured **Host Dashboard**.

---

## 🎯 My Key Skills Demonstrated (For Recruiters)

This project demonstrates my proficiency in the following areas, essential for a Frontend Developer role:

### 1. **Application Architecture & React Fundamentals**
* **Modular, Scalable Code:** Project structure relies on Functional Components and Hooks, ensuring a clear separation of concerns and maintainability.
* **State Management:** Effective use of built-in React Hooks (`useState`, `useEffect`, `useContext`, and `useReducer` for complex state) to manage application data flow.
* **Routing and Navigation:** Advanced implementation of **React Router** for:
    * **Nested Routes:** Utilized within the Host Dashboard for sections like Info, Pricing, and Photos.
    * **Dynamic Segments (`/vans/:id`)** for loading specific resource data.

### 2. **Security & User Experience (UX)**
* **Protected Routing:** Implemented a custom **authentication mechanism** (demo login) that secures the entire `/host` area using `React Router` and conditional rendering.
* **Error Handling:** Deployment of a **Custom 404 Page** and proper management of loading states and API errors across the interface.
* **Responsive Design:** Ensuring full responsiveness and an intuitive UI/UX for both mobile and desktop users.

### 3. **Workflow and Technologies**
* **Vite:** Utilizing a modern bundler for fast development and production build optimization.
* **CSS Modules:** Managing component-level styles to minimize the risk of collision and increase code isolation.
* **CI/CD Deployment:** Experience integrating with platforms like **Netlify** for continuous deployment.

---

## 🛠️ Tech Stack

| Category | Technology | Application in Project |
| :--- | :--- | :--- |
| **Main Framework** | **React.js** (Functional Components, Hooks) | The core foundation of the application. |
| **Routing** | **React Router v6+** | Navigation, **Protected Routes**, **Nested Routes**. |
| **Bundling** | **Vite** | Fast development and production optimization. |
| **Styling** | **CSS Modules** | Component style isolation. |
| **Deployment** | **Netlify** | Live deployment and CI/CD. |

---

## 📝 Key Features

* **Custom Authentication (Demo):** Implemented login flow to protect the host dashboard.
* **Van Catalog:** Displaying a list of vans with categorization (`Simple`, `Rugged`, `Luxury`).
* **Van Details:** Dynamic loading of data for individual vans.
* **Host Dashboard:** A secure area with dedicated sections:
    * `Income` (Earnings Summary)
    * `Reviews` (Customer Feedback)
    * `Vans` (Van Management)

---

## 📂 Routing Structure

The application uses a complex, two-tier routing structure:

### 1. Public Routes:
* `/` — Home Page
* `/vans` — Van Listing
* `/vans/:id` — Details Page
* `/login` — Login Page
* `*` — Custom 404

### 2. Host Dashboard (Protected Routes):
* `/host` — Main Dashboard
* `/host/income`
* `/host/reviews`
* `/host/vans` — Host Van Listing
* `/host/vans/:id`
    * `/host/vans/:id/pricing`
    * `/host/vans/:id/photos`
