# Building a SaaS With Nextjs, React, Honojs Finance Project.
![3](https://github.com/user-attachments/assets/33944341-794d-48fc-a031-3f8b55680697)


This project is a personal finance application that allows you to track your income and expenses, categorise transactions and assign them to specific accounts, transfer transactions to the project using a CSV file, and connect to your bank accounts through Plaid. 

## 🎯 Project Features:
- 📊 **Interactive financial dashboard:** Allows users to view financial data with interactive charts.
- 🔁 **Changeable chart types:** Provides options to change chart types. 
- 🗓 **Account and date filters:** Enables filtering by account and date
- 💹 **Detailed transactions table:** Displays a detailed transaction list in table format.
- ➕ **Form to add transactions:** Includes a form to add new transactions.
- 🧩 **Customizable select components:** Customizes selection components based on user preferences.
- 💵 **Income and expense toggle:** Switches between income and expense views.
- 🔄 **CSV transaction imports:** Allows importing transaction data in CSV format.
- 🔥 **API via Hono.js:** Provides a fast and reliable API with Hono.js.
- 🪝 **State management via Tanstack React Query:** Manages state with Tanstack React Query.
- 🔗 **Bank account connections with Plaid:** Allows connecting bank accounts via Plaid.
- 💳 **Premium upgrades via Lemon Squeezy:** Enables premium upgrades through Lemon Squeezy.
- 🔐 **Authentication via Clerk (Core 2):** Secures user authentication with Clerk Core 2.
- 🗑 **Bulk delete and search in transactions:** Supports bulk delete and search within transactions.
- ⚙️ **Bank disconnection and subscription management:** Manages bank disconnection and subscription settings.
- 👤 **User settings customization:** Allows customization of user settings.
- 🌐 **Built with Next.js 14:** Developed with Next.js 14.
- 🎨 **Styled with TailwindCSS and Shadcn UI:** Uses TailwindCSS and Shadcn UI for design.
- 💾 **PostgreSQL & Drizzle ORM:** Utilizes PostgreSQL as the database and Drizzle as the ORM.
  
## 🚀 Necessary:

- **Node version:** 14.X

## 📝 Cloning the repository

Use the following command to clone the repository:

```shell
(https://github.com/DogukanErzurum/finance.git)
```

## 📦 Installing Packages:

```shell
npm i
```

## 🔐 Setup .env file

This is the section where the person hashes the registration status given by google github and my own system after registration. It is personalized!

```js
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_ID=
GITHUB_SECRET=
NEXTAUTH_JWT_SECRET=
NEXTAUTH_SECRET=
```

##💻 Start the app

npm run dev starts the application at localhost:3000.

```shell
npm run dev
```
