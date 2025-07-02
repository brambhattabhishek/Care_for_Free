# 💼 Care for Free

**Care for Free** is a modern, open-source web application designed to help individuals streamline their job application process. Built with **Next.js** and **Tailwind CSS**, the platform offers intelligent tools to create resumes, generate personalized cover letters, and prepare for interviews — all in one place, completely free.

---

## 📖 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Available Scripts](#available-scripts)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---


---

## 📋 Quick Setup Summary

To get started with this project, follow these steps:

- 📦 **Install Dependencies** – Run `npm install`
- ▶️ **Start the Development Server** – Run `npm run dev` and visit `http://localhost:3000`
- 📁 **Project Structure** – Organized for clarity and scalability (see section below)
- 🔧 **Available Scripts** – Run, build, or lint with ease
- 🤝 **Contributing** – Fork, branch, and submit pull requests
- 📬 **Contact** – Get in touch with the creator

---
## 📌 About the Project

In today’s fast-paced world, job seekers often struggle to organize their application materials effectively. **Care for Free** provides a central platform to generate polished resumes, write impactful cover letters, and prepare for interviews using smart tools — all without any cost. Whether you're a fresher or an experienced professional, this tool aims to make job hunting less stressful and more successful.

---

## ✨ Features

- ✅ **Resume Generator** – Create a professional resume quickly
- ✅ **Cover Letter Assistant** – Get personalized cover letters using inputs
- ✅ **Interview Preparation** – Access relevant questions and answers
- ✅ **User Dashboard** – View, edit, and manage your documents in one place
- ✅ **Secure Middleware** – Route protection for logged-in users
- ✅ **Clean UI/UX** – Responsive design using Tailwind CSS

---

## 🧰 Tech Stack

| Technology      | Purpose                     |
|------------------|-----------------------------|
| **Next.js**       | React framework for SSR & routing |
| **Tailwind CSS**  | Utility-first CSS framework |
| **JavaScript**    | Core scripting language |
| **Node.js**       | Backend runtime |
| **PostCSS**       | CSS transformations |
| **ESLint**        | Linting and code quality |
| **Git & GitHub**  | Version control & collaboration |

---


---

## 🧠 Tech Stack (Extended)

This project is a **Full Stack AI Career Coach** built using modern technologies:

- ⚛️ **Next.js** – React Framework for SSR and routing
- 🌈 **Tailwind CSS** – Utility-first styling
- 🔄 **Prisma** – Type-safe ORM for database access
- 🧬 **Neon DB** – Serverless Postgres database
- 🧰 **Inngest** – Background jobs and event handling
- 💅 **Shadcn UI** – Accessible, customizable components
- 🔐 **Clerk** – Authentication and user management

---

## 🔐 Environment Variables

Before running the application, make sure to create a `.env` file in the root directory and include the following variables:

```env
# Database
DATABASE_URL=

# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

# Gemini AI Key (for AI features)
GEMINI_API_KEY=
```

> ⚠️ Keep your `.env` file safe and never commit it to version control.
## 🚀 Getting Started

Follow the steps below to set up the project on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/brambhattabhishek/care-for-free.git
cd care-for-free
```

### 2. Install Dependencies

Make sure you have Node.js and npm installed. Then, run:

```bash
npm install
```

### 3. Start the Development Server

```bash
npm run dev
```

Visit `http://localhost:3000` in your browser to view the app.

---

## 📁 Project Structure

```plaintext
care-for-free/
├── app/                  # Next.js pages, layout, and global styles
├── actions/              # Server-side logic (resume, cover letter, etc.)
├── public/               # Static files like favicon
├── .eslintrc.json        # ESLint configuration
├── jsconfig.json         # JavaScript config for path aliases
├── middleware.js         # Authentication middleware
├── next.config.mjs       # Next.js configuration
├── postcss.config.mjs    # PostCSS config
├── tailwind.config.mjs   # Tailwind CSS settings
├── package.json          # Project metadata and scripts
```

---

## 📜 Available Scripts

In the project directory, you can run:

- `npm run dev` – Runs the app in development mode
- `npm run build` – Builds the app for production
- `npm run lint` – Checks for linting issues

---

## 🤝 Contributing

Contributions are what make open-source communities thrive!

To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

Please follow the existing code style and structure.

---

## 📄 License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute it with proper credit.

---

## 📬 Contact

**Author**: [Abhishek Brahmbhatt]  
**GitHub**: [https://github.com/your-username](https://github.com/brambhattabhishek)  
**Email**: brambhattabhishek@gmail.com  

If you find this project useful, please consider giving it a ⭐ on GitHub.
