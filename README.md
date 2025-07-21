# LaraSQ Kit ✨

Modern Laravel 12 + Inertia.js + React + TypeScript Boilerplate

![Banner](./assets/banner.png)

<p align="center">
  <a href="https://github.com/saherqaid/larasq-kit/actions"><img src="https://img.shields.io/github/actions/workflow/status/saherqaid/larasq-kit/ci.yml?branch=main&label=CI&logo=github" alt="CI Status"></a>
  <a href="https://github.com/saherqaid/larasq-kit/blob/main/LICENSE"><img src="https://img.shields.io/github/license/saherqaid/larasq-kit?color=blue" alt="License"></a>
  <a href="https://github.com/saherqaid/larasq-kit/stargazers"><img src="https://img.shields.io/github/stars/saherqaid/larasq-kit?style=social" alt="GitHub stars"></a>
</p>

---

## 📚 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Architecture](#-architecture)
- [Quickstart](#-quickstart)
- [FAQ](#-faq)
- [Community & Support](#-community--support)
- [Documentation](#-documentation)

---

## 🚀 Overview

LaraSQ Kit is a modern, batteries-included boilerplate for building robust web applications with the power of Laravel 12, Inertia.js, React, and TypeScript. Designed for rapid development, scalability, and developer happiness.

---

## ✨ Key Features

- ⚡️ **Modern Stack**: Laravel 12, Inertia.js, React, TypeScript
- 🔐 **Authentication**: Secure, ready-to-use auth scaffolding
- 🎨 **Beautiful UI**: Prebuilt components and layouts
- 🔁 **Hot Reloading**: Instant feedback during development
- 🧪 **Testing Ready**: Out-of-the-box test setup
- 🛠️ **Easy Customization**: Modular structure for rapid iteration
- 🌍 **Localization**: Multilanguage support
- 🧩 **Extensible**: Easily add packages and features
- 📦 **API Ready**: RESTful and SPA-friendly
- 📝 **Comprehensive Docs**: Clear, up-to-date documentation

---

## 🛠️ Tech Stack

- **Backend:** Laravel 12 (PHP)
- **Frontend:** React 18, TypeScript, Inertia.js
- **Styling:** Tailwind CSS
- **Testing:** PHPUnit, Pest, React Testing Library
- **Tooling:** Vite, ESLint, Prettier
- **Database:** MySQL, SQLite (dev)

---

## 🏗️ Architecture

> **Diagram Placeholder:**
>
> ![Architecture Diagram](./assets/architecture.png)
>
> _A visual overview of the LaraSQ Kit architecture._

- **Monorepo structure** for backend and frontend
- **Inertia.js** bridges Laravel and React seamlessly
- **Modular components** for easy reuse and extension
- **API-first** design for future-proofing

---

## 🏁 Quickstart

### 1. Clone & Install

```bash
# Clone the repository
git clone https://github.com/saherqaid/larasq-kit.git
cd larasq-kit

# Install PHP dependencies
composer install

# Install JS dependencies
npm install
```

### 2. Environment Setup

```bash
cp .env.example .env
php artisan key:generate
```

### 3. Database & Migrate

```bash
# Configure your .env database settings
php artisan migrate
```

### 4. Start Development Servers

```bash
# Start Laravel backend
php artisan serve

# Start Vite dev server
npm run dev
```

### 5. Run Tests

```bash
php artisan test
npm run test
```

---

## ❓ FAQ

**Q: Can I use a different frontend framework?**
> LaraSQ Kit is optimized for React, but you can adapt it for Vue or Svelte with effort.

**Q: Is it production-ready?**
> Yes! It includes security, testing, and best practices out of the box.

**Q: How do I deploy?**
> Standard Laravel deployment applies. See the [Laravel docs](https://laravel.com/docs/deployment) for details.

---

## 🤝 Community & Support

- Open an [issue](https://github.com/saherqaid/larasq-kit/issues) for bugs or feature requests
- Join the discussion on [GitHub Discussions](https://github.com/saherqaid/larasq-kit/discussions)
- For security issues, see [Security Policy](.github/SECURITY.md)

---

## 📚 Documentation

- [🤝 Contributing](CONTRIBUTING.md)
- [📦 Commit Guidelines](COMMIT_GUIDELINES.md)
- [🔒 Security Policy](.github/SECURITY.md)

---

<p align="center">
  Made with ❤️ by <a href="https://saherqaid.com">Saher Qaid</a>
</p> 
