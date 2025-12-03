# ⚡ Resume Analyzer  
> AI-powered Resume Uploader & Analyzer built with **React Router v7**, **TypeScript**, **TailwindCSS**, and **Puter.js**

![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=fff&style=flat)
![React Router](https://img.shields.io/badge/React_Router-v7-CA4245?logo=reactrouter&logoColor=fff&style=flat)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwindcss&logoColor=fff&style=flat)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff&style=flat)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

Upload your resume 📂 → Store it on **Puter Cloud** ☁️ → Get instant insights 📊.  
This project makes resume analysis simple, stylish, and lightning fast ⚡.

---

## ✨ Features
- 📂 **Upload Resumes** – Drag & drop PDF files with ease  
- 🧠 **Smart Analysis** – AI-driven score, summary & suggestions  
- 📊 **Resume Dashboard** – Browse uploaded resumes beautifully  
- 🎨 **Modern UI** – TailwindCSS + Inter font = sleek design  
- 🌐 **Puter Integration** – Store files in the cloud seamlessly  
- 🚦 **Error Boundaries** – Handles 404 & runtime errors gracefully  

---

## 📂 Project Structure

```tree
src/
 ├── root.tsx           # App layout, meta, error boundary
 ├── routes.ts          # Route definitions
 ├── routes/
 │   ├── home.tsx       # Homepage
 │   ├── auth.tsx       # Auth (login/signup)
 │   ├── upload.tsx     # Upload form
 │   ├── resume.tsx     # Resume details + AI analysis
 │   └── wipe.tsx       # Clear user session
 ├── components/
 │   ├── FileUploader.tsx
 │   ├── ResumeCard.tsx
 │   ├── ScoreBadge.tsx
 │   └── Summary.tsx
 └── lib/
     └── puter.ts       # Puter.js store hook
```

---

## 📜 License

This project is licensed under the **MIT License**.
