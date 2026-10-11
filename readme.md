# Expence-Tracker

A mobile-first personal expense tracker designed to fit Samsung Galaxy Z Fold screens, from the narrow cover display to the expanded inner screen. It includes local sign-up and sign-in with a one-time profile setup.

## Files

- `index.html` — page structure
- `Style.css` — responsive styling
- `App.js` — transaction, reminder, and lending interactions

## Open the website

Open `index.html` in a modern web browser. No build step or installation is required. Google Fonts are loaded from the internet; the site otherwise runs locally in the browser.

## Features

- Add income and expense transactions.
- Create custom categories and payment methods.
- Record upcoming payments with due dates and memo notes.
- Track money lent to people and record repayments.
- Save each account’s profile and finance records in browser storage, separated by email address.
- Sign in again on the same browser and device to reopen that account’s saved data.
- Ask for “Your information” only while creating an account; returning sign-ins skip profile setup.
- Start new accounts with no transactions, payment reminders, or loans. Existing accounts load their own saved entries.
- Responsive dashboard with overview, spending chart, upcoming reminders, recent activity, and loan balances.
- Switch between light and dark themes; the preference is remembered in the browser.
- Desktop sidebar and phone bottom navigation adapt to the screen size.
- Sidebar and mobile navigation switch between Overview, Transactions, Memorandum, and Loan tracker views.
- Delete mistaken transactions, payment reminders, and loans with a confirmation step.
- Month selector filters income, expenses, and recent transactions; “View all” shows full transaction history.

## Important storage note

This is a static, browser-only website. Account credentials and app data are stored on the current device in local browser storage; there is no server or cloud backup. Data will not automatically sync to another device or browser, and can be lost if browser storage is cleared or the device is lost. For reliable recovery and cross-device sign-in, connect the site to a hosted authentication and database service and add export/backup. Do not use this local prototype as the only copy of important financial records.
