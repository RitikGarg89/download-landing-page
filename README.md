# React Router Landing Page

A simple, responsive multi-page landing page built with React, React Router, and Tailwind CSS.

## 🚀 Features

- **Nested Routing**: Clean layout structure using `createBrowserRouter` and `<Outlet />`.
- **Pages**:
  - **Home**: Hero section with download CTA and preview images.
  - **About**: Company and developer info showcase.
  - **Contact**: Contact form and company details.
  - **User**: Dynamic route parameter handling (`/user/:userid`).
  - **Github**: Fetches live GitHub profile data and followers.
- **Responsive Design**: Mobile-friendly layout styled with Tailwind CSS.

## 🛠️ Tech Stack

- **React 19**
- **Vite**
- **React Router DOM (v7)**
- **Tailwind CSS (v4)**

## 📦 Getting Started

### 1. Install dependencies
```bash
npm install
```

### 2. Run the development server
```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

## 📁 Project Structure

```text
src/
├── Components/
│   ├── About/
│   ├── Contact/
│   ├── Footer/
│   ├── Github/
│   ├── Header/
│   ├── Home/
│   └── User/
├── App.jsx          # Root layout with Header, Outlet, and Footer
├── Layout.jsx       # Alternate layout wrapper component
├── main.jsx         # Router setup and root entry point
└── index.css        # Tailwind styling
```
