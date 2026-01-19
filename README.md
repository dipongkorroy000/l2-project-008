# 🌍 Local Guide Project

A modern **Local Guide Web Application** built with **Next.js (frontend)** and **Express + Prisma (backend)**.  
This project helps users explore, manage, and interact with local services seamlessly with a polished UI/UX.

🔗 **Live Demo:** [Local Guide App](https://l2-assignment-008-frontend-577l.vercel.app)

---

## 🚀 Tech Stack

### **Frontend (Client)**

- **Framework:** [Next.js 16](https://nextjs.org/)
- **UI & Styling:**
  - [TailwindCSS 4](https://tailwindcss.com/)
  - [Radix UI](https://www.radix-ui.com/) components (`accordion`, `dialog`, `select`, `tooltip`, etc.)
  - [lucide-react](https://lucide.dev/) (icons)
  - [framer-motion](https://www.framer.com/motion/) (animations)
  - [nprogress](https://github.com/rstacruz/nprogress) (loading bar)
  - [tw-animate-css](https://www.npmjs.com/package/tw-animate-css) (animations)
- **Forms & Validation:**
  - [react-hook-form](https://react-hook-form.com/)
  - [zod](https://zod.dev/) (schema validation)
  - [@hookform/resolvers](https://react-hook-form.com/docs/useform/#resolver)
- **State & Utilities:**
  - [next-themes](https://github.com/pacocoursey/next-themes) (theme switching)
  - [clsx](https://github.com/lukeed/clsx) & [tailwind-merge](https://tailwind-merge.vercel.app/) (class utilities)
  - [class-variance-authority](https://cva.style/) (variant styling)
- **Charts & Maps:**
  - [recharts](https://recharts.org/) (data visualization)
  - [ol (OpenLayers)](https://openlayers.org/) (maps)
- **Other Tools:**
  - [sweetalert2](https://sweetalert2.github.io/) (alerts)
  - [sonner](https://sonner.emilkowal.ski/) (toast notifications)
  - [react-day-picker](https://react-day-picker.js.org/) (date picker)
  - [react-icons](https://react-icons.github.io/react-icons/) (icon library)
  - [cmdk](https://cmdk.paco.sh/) (command palette)

---

### **Backend (Server)**

- **Framework:** [Express 5](https://expressjs.com/)
- **Database & ORM:** [Prisma 6](https://www.prisma.io/) with [@prisma/client](https://www.prisma.io/docs/concepts/components/prisma-client)
- **Authentication & Security:**
  - [jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) (JWT auth)
  - [bcryptjs](https://github.com/dcodeIO/bcrypt.js) (password hashing)
  - [cookie-parser](https://github.com/expressjs/cookie-parser) (cookies)
  - [cors](https://github.com/expressjs/cors) (CORS handling)
- **File Uploads & Media:**
  - [multer](https://github.com/expressjs/multer) (file uploads)
  - [cloudinary](https://cloudinary.com/) (image hosting)
- **Payments:**
  - [stripe](https://stripe.com/) (payment gateway)
- **Utilities:**
  - [dotenv](https://github.com/motdotla/dotenv) (environment variables)
  - [date-fns](https://date-fns.org/) (date utilities)
  - [http-status](https://www.npmjs.com/package/http-status) (status codes)

---

## 📦 Package Managers

- **Frontend:** npm / pnpm
- **Backend:** pnpm `v10.17.1`

---

## ⚙️ Scripts

### **Frontend**

- `dev` → Run Next.js development server
- `build` → Build production bundle
- `start` → Start production server
- `lint` → Run ESLint

### **Backend**

- `dev` → Run Express server with `ts-node-dev`
- `test` → Placeholder test script

---

## 🛠️ Development Setup

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd local-guide
   ```
