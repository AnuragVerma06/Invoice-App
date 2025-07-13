# Vue Invoice App

A fully functional invoice application built with Vue 3, Vuex, and Firebase—featuring full CRUD (Create, Read, Update, Delete) capabilities.

🚀 Features

    Invoice management: Create, view, edit, delete invoices.

    Client and product details: Add and manage client info, invoice line items, totals.

    State management: Uses Vuex for a centralized store and reactive UI.

    Real-time persistence: Powered by Firebase Firestore for live data syncing.

    Authentication (optional): You can add user authentication via Firebase (some forks include this)
    GitHub
    .

    Responsive UI: Built with Vue 3’s Composition API; easy to extend and customize.

🧠 Tech Stack

    Framework: Vue 3 with Composition API

    State: Vuex for state management

    Database: Firebase Firestore (NoSQL, real‑time)

    (Optional) Auth: Firebase Authentication (email/password, Google, etc.)

    Styling: CSS or Sass (depending on original tutorial)

🧭 App Flow Overview

    State store (Vuex):

        invoices module: holds list of invoices, CRUD actions

        (Optional) auth module: handles sign‑in, sign‑out, persists user state

    Views:

        Dashboard: shows invoices, allows filtering/sorting.

        Invoice form: for creating or editing invoice items.

        Invoice detail: view and print invoice.

    Main logic:

        Firestore observers sync on changes (add, update, delete).

        Vuex actions dispatch Firebase calls to persist data.

        Components subscribe to store state and dispatch mutations.

📦 Deployment

You can deploy via platforms like Firebase Hosting, Vercel, or Netlify:

    Firebase Hosting: preferred if you're already using Firestore.

    Static Export: use npm run build and host the dist/ folder.

🧩 Customization Ideas

    Add user authentication, multi-user support, and invoice isolation.

    Enhance styling using Tailwind CSS or other frameworks.

    Integrate PDF export or printing functionality.

    Connect to a serverless backend or Stripe for invoice payments.

    Use Pinia as a modern alternative to Vuex if refactoring.

🧾 License

MIT License
