# PizzaApp

A modern, responsive pizza ordering app built with Next.js and Tailwind CSS, designed as a polished portfolio project for hiring managers and interviewers.

## 🚀 Project Overview

PizzaApp is a full-stack pizza ordering experience with a clean UI and smooth shopping flow:

- Browse menu items with images, pricing, and descriptions
- Choose pizza size, crust, and toppings
- Add/remove items in cart, update quantities
- Mobile-first responsive design with desktop and mobile cart variants
- Real-time cart totals and order summary
- Built with scoped React/Next.js state via Context API

## ✨ Key Features

- User-friendly product selection: size, crust, toppings
- Live cart updates (quantity controls, remove item)
- Distinct cart UX for desktop and mobile devices
- Animated and accessible UI components
- Modular, reusable component architecture

## 🛠️ Tech Stack

- Framework: `Next.js (App Router)`
- UI: `React`, `Tailwind CSS`
- State Management: `React Context API` (`CartContext`)
- Component library includes: `Banner`, `Pizza`, `CartItem`, `SizeSelection`, `CrustSelection`, `Topping`
- Route-based API (example endpoint under `src/app/api/hello/route.js`)

## 👨‍💻 What makes it ready to use

- Demonstrates Next.js app architecture and folder-based routing
- Shows ability to build state-driven UI with context + dynamic updates
- Includes responsive + accessible design patterns
- Clean code organization and component reuse

## 📁 Project Structure

- `src/app` - main pages and layout
- `src/app/components` - reusable UI components
- `src/app/context/CartContext.js` - shared cart state

## 🧪 Run locally

```bash
npm install
npm run dev
```

Open `http://localhost:3000`.

## 💡 Enhancement ideas

- Adding authentication + personalized orders
- Integrating backend API (orders db, payment processing)
- Adding search, filters, and persistence (localStorage)
