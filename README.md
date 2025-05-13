# Horizon - A Full-Stack Banking Platform

<div align="center">
  <img src="https://www.markaustria.com/horizon.png" alt="Horizon Banking Platform" />

[![Portfolio](https://img.shields.io/badge/Portfolio-markaustria.com-darkblue?style=flat&logo=web&logoColor=white)](https://www.markaustria.com/) [![GitHub](https://img.shields.io/badge/GitHub-mjaus29-black?style=flat&logo=github)](https://github.com/mjaus29) [![LinkedIn](https://img.shields.io/badge/LinkedIn-markaustria-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/markaustria/) [![Email](https://img.shields.io/badge/Email-austriamark.mja%40gmail.com-darkred?style=flat&logo=gmail&logoColor=white)](mailto:austriamark.mja@gmail.com)
</div>

## 🌐 Live Site

🚀 Here is a working live site: [horizon.markaustria.com](https://horizon.markaustria.com/)

🗒️ Check out the case study here: [markaustria.com/horizon](https://www.markaustria.com/horizon)

## 📝 Description

Welcome to Horizon, a comprehensive online banking platform that connects to multiple bank accounts, displays real-time transactions, and enables secure money transfers between users!

Traditional financial trackers often function like simple to-do apps where users manually add income, deduct expenses, and view basic charts. These solutions lack real banking functionality and connectivity to actual financial institutions. I built Horizon to address this gap by creating a more sophisticated platform.

Horizon solves the problem of disconnected financial tracking by connecting to real bank accounts, displaying genuine transaction data, and facilitating actual money transfers between users.

The platform offers secure authentication, real-time bank account connectivity, transaction history with filtering, and a payment transfer system between accounts.

**Technologies Used:** Next.js, TypeScript, Tailwind CSS, Shadcn UI, Sentry, Appwrite, Plaid, Dwolla, React Hook Form, Zod, Chart.js

## 📖 Table of Contents

- [Features](#-features)
- [Installation](#%EF%B8%8F-setup-project)
- [How to Contribute](#%EF%B8%8F-how-to-contribute)
- [Bug / Feature Request](#-bug--feature-request)
- [Future Enhancements](#-future-enhancements)
- [Acknowledgements](#-acknowledgements)

## ✨ Features

- **Server-Side Authentication:** Secure authentication system using Appwrite that stores user data in a database and manages sessions securely, protecting sensitive financial information.
- **Real Bank Account Integration:** Integration with Plaid to connect real bank accounts, fetch transaction data, and display account balances, providing users with genuine financial information.
- **Inter-Account Money Transfers:** Secure payment transfer system using Dwolla that allows users to send money between different accounts on the platform, complete with transaction status tracking and processing.
- **Responsive Design:** Application features a responsive design that works across all device sizes and implements modern security practices.

## 🛠️ Setup Project

To get this project up and running in your development environment, follow these step-by-step instructions.

### 🍴 Prerequisites

We need to install or make sure that these tools are pre-installed on your machine:

- [Git](https://git-scm.com/downloads)
- [NodeJS](https://nodejs.org/en/download/)
- [NPM](https://docs.npmjs.com/getting-started/installing-node)

### 🚀 Install Project

1. Clone the Repository

   ```bash
   git clone https://github.com/mjaus29/horizon.git
   ```

2. Navigate into the project directory

   ```bash
   cd horizon
   ```

3. Install dependencies

   ```bash
   npm install
   ```

4. Set up environment variables

   - Create a .env file in the root directory.
   - Add the following environment variables:

   ```
   #NEXT
   NEXT_PUBLIC_SITE_URL=

   #APPWRITE
   NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
   NEXT_PUBLIC_APPWRITE_PROJECT=
   APPWRITE_DATABASE_ID=
   APPWRITE_USER_COLLECTION_ID=
   APPWRITE_BANK_COLLECTION_ID=
   APPWRITE_TRANSACTION_COLLECTION_ID=
   NEXT_APPWRITE_KEY=

   #PLAID
   PLAID_CLIENT_ID=
   PLAID_SECRET=
   PLAID_ENV=sandbox
   PLAID_PRODUCTS=auth,transactions,identity
   PLAID_COUNTRY_CODES=US,CA

   #DWOLLA
   DWOLLA_KEY=
   DWOLLA_SECRET=
   DWOLLA_BASE_URL=https://api-sandbox.dwolla.com
   DWOLLA_ENV=sandbox
   ```

5. Start the application

   ```bash
   npm run dev
   ```

6. Open your web browser and navigate to <a href="http://localhost:3000" target="_blank">http://localhost:3000</a> to see the project running.

## ⚒️ How to Contribute

Want to contribute? Great!

To fix a bug or enhance an existing module, follow these steps:

- Fork the repo
- Create a new branch (`git checkout -b improve-feature`)
- Make the appropriate changes in the files
- Add changes to reflect the changes made
- Commit your changes (`git commit -am 'Improve feature'`)
- Push to the branch (`git push origin improve-feature`)
- Create a Pull Request

### 📩 Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/mjaus29/horizon/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/mjaus29/horizon/issues/new). Please include sample queries and their corresponding results.

### ✅ Future Enhancements

- [ ] Implement recurring payments and scheduled transfers
- [ ] Add spending insights and budgeting tools
- [ ] Integrate with additional payment processors
- [ ] Develop mobile applications using React Native

### 📚 Acknowledgements

Special thanks to JSM for the inspiration and guidance on this project.

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-markaustria.com-darkblue?style=flat&logo=web&logoColor=white)](https://www.markaustria.com/) [![GitHub](https://img.shields.io/badge/GitHub-mjaus29-black?style=flat&logo=github)](https://github.com/mjaus29) [![LinkedIn](https://img.shields.io/badge/LinkedIn-markaustria-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/markaustria/) [![Email](https://img.shields.io/badge/Email-austriamark.mja%40gmail.com-darkred?style=flat&logo=gmail&logoColor=white)](mailto:austriamark.mja@gmail.com)
</div>
