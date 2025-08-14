

## **📄 README.md**


# ProjectSupabase

A simple authentication and user management app built with **Next.js**, **Supabase**, and **TailwindCSS**.



## 🚀 Tech Stack
- [Next.js 15](https://nextjs.org/) – React framework for server-side rendering
- [Supabase](https://supabase.com/) – Backend-as-a-Service for authentication and database
- [TailwindCSS](https://tailwindcss.com/) – Utility-first CSS framework
- [Shadcn/UI](https://ui.shadcn.com/) – UI components for a clean design



## 📌 Features
- Email/password authentication
- Google OAuth login
- Protected routes
- Signup and login forms
- Logout functionality
- Environment variable configuration for Supabase



## 🛠 Setup Instructions

 1️⃣ Clone the repository

git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
````

 2️⃣ Install dependencies


npm install
```

 3️⃣ Configure environment variables

Create a `.env.local` file in the root folder and add:

```env
NEXT_PUBLIC_SUPABASE_URL=<your-supabase-url>
NEXT_PUBLIC_SUPABASE_ANON_KEY=<your-supabase-anon-key>
SUPABASE_SERVICE_ROLE_KEY=<your-supabase-service-role-key>
```

> You can get these from your Supabase project settings.

 4️⃣ Run the development server

```bash
npm run dev
```

Visit: [http://localhost:3000](http://localhost:3000)



## 📈 Future Improvements

* Dark mode
* Forgot password flow
* Profile page with avatar upload
* Database CRUD operations
* Deploy to Vercel

---

## ⏱ Time Spent

Approx. **X hours** on initial build and testing.

---

## 📄 License

This project is licensed under the MIT License.

````

---

## **📄 .gitignore**
```gitignore
# dependencies
node_modules

# production
/.next
/out

# misc
.DS_Store
*.log

# env files
.env
.env.local
.env.development.local
.env.test.local
.env.production.local

# vercel
.vercel

# vscode
.vscode
````

---

## **📁 Folder structure**

```
projectsupabase/
│── components/
│── lib/
│── app/ or pages/
│── public/
│── screenshots/
│    ├── login.png
│    └── signup.png
│── styles/
│── .gitignore
│── README.md
│── package.json
│── .env.local
```

---

## **📦 Commit & Push Commands**

From VS Code terminal:

```bash
git add .
git commit -m "Added README and .gitignore for Supabase project"
git pull origin main --rebase
git push origin main
```

---


