# Malta Money Manager 💶

A simple and responsive household finance management application built with HTML, CSS, JavaScript, and Supabase.

Malta Money Manager helps individuals, couples, and small households manage their finances by tracking income, recording expenses, splitting shared costs, and monitoring repayments.

## ✨ Features

- **Financial Dashboard:** View monthly income, expenses, balances, and spending categories.
- **Expense Tracking:** Record, categorise, and manage personal and shared expenses.
- **Flexible Expense Splitting:** Split expenses equally, by percentage, or using custom amounts.
- **Shared Household Finances:** Calculate who owes whom and track outstanding balances.
- **Income Tracking:** Record salaries, freelance earnings, bonuses, and additional income.
- **Repayment Management:** Record repayments between household members.
- **Household Invitations:** Invite members to share household expenses.
- **CSV Export:** Export monthly expense records.
- **Authentication:** Secure account registration, login, and password recovery.
- **Live Synchronisation:** Keep household financial information updated using Supabase.

## 🛠️ Built With

- HTML5
- CSS3
- JavaScript
- Supabase
- Supabase Authentication
- Supabase Realtime

## 🚀 Getting Started

### Prerequisites

- A modern web browser.
- A Supabase account.
- A Supabase project.

### Installation

1. Clone the repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

2. Open the project directory.

3. Configure your Supabase project URL and publishable key in `index.html`.

4. Run the database setup script (`setup.sql`) in your Supabase SQL Editor.

5. Open `index.html` in your browser or serve it using a local web server.

## 💶 Currency and Regional Settings

- Currency: EUR (€)
- Locale: en-IE
- Timezone: Europe/Malta

## 👨‍👩‍👧 Household Support

The application supports households with up to three members, allowing users to share expenses and manage repayments.

## 🔐 Security

The application uses Supabase authentication and a publishable key. Database access should be protected using properly configured Row Level Security (RLS) policies.

Never expose your Supabase service-role key in frontend code.

## 📄 License

Add your preferred open-source license here.

## 🎯 Project Goal

To make household financial management easier, more transparent, and more organised by providing a simple platform for tracking expenses, income, and shared financial responsibilities.
