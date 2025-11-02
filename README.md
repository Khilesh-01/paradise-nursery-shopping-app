# 🌿 Paradise Nursery Shopping App

A modern, responsive plant e-commerce web application built using **React** and **Vite**.  
It offers a clean shopping experience for nursery products, including browsing, adding to cart, and viewing product details — all powered by **Redux Toolkit** for efficient state management.

---

## 🚀 Features

- 🪴 **Product Display**: Beautiful UI for browsing nursery items with images and details.
- 🛒 **Cart Management**: Add, remove, and update items in a shopping cart using Redux.
- 💰 **Dynamic Price Updates**: Cart total and quantity update in real-time.
- 🧭 **Navigation**: Seamless navigation between pages (e.g., About Us, Products).
- 🎨 **Custom Styling**: Component-level CSS with responsive layouts.
- ⚡ **Fast Development & Build**: Vite for blazing-fast builds and previews.

---

## 🧱 Project Structure

```
ParadiseNurseryShoppingApp/
├── index.html
├── package.json
├── vite.config.js
├── public/
│   └── vite.svg
└── src/
    ├── main.jsx
    ├── App.jsx
    ├── App.css
    ├── store.js
    ├── CartSlice.jsx
    ├── CartItem.jsx
    ├── CartItem.css
    ├── ProductList.jsx
    ├── ProductList.css
    ├── AboutUs.jsx
    ├── AboutUs.css
    └── assets/
        └── react.svg
```

---

## ⚙️ Installation & Setup

### Clone or extract the project

```bash
git clone <repo-url>
cd ParadiseNurseryShoppingApp
```

### Install dependencies

```bash
npm install
```

### Start development server

```bash
npm run dev
```

The app runs on [http://localhost:5173](http://localhost:5173)

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

---

## 🔒 Security Notes

If `npm audit` shows vulnerabilities in `esbuild`:

```bash
npm audit fix
```

If still present and non-production:

```bash
npm audit fix --force
```

These affect only dev servers, not production builds.

---

## 🧠 Tech Stack

| Category         | Tools/Frameworks       |
|------------------|------------------------|
| Frontend         | React (JSX, Hooks)     |
| State Management | Redux Toolkit          |
| Bundler          | Vite                   |
| Styling          | CSS (Component-based)  |
| Package Manager  | npm                    |

---

## 🧑‍💻 Scripts

| Command         | Description                          |
|-----------------|--------------------------------------|
| `npm run dev`   | Start local development server       |
| `npm run build` | Build optimized production version   |
| `npm run preview` | Preview built version locally     |
| `npm run lint`  | (If configured) Lint codebase        |

---

## 🌱 Future Improvements

- Add product search & filters  
- Integrate backend for live product data  
- Add user authentication and order management  
- Enhance UI/UX with animations and better responsiveness  

---