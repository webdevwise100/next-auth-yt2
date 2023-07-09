# next-auth-yt2

This repository provides you all the building blocks to implement next-auth in your application.

The files included are:
1. SessionProviders.jsx -> This provides the session details to the childrens from next-auth (Client Component)
2. SignInButton.jsx -> This provides you the SignIn & SignOut button functionality. Also, a simple menu on SignIn using @headlessui. (Client Component)
3. Dashboard-page.js -> This page is a protected page and can be navigated only on authentication. (Client Route). Replace this file name to page.js and place it under /app/dashboard/
4. next-auth-api-route.js -> This file is used to provide the authOptions and next-auth handlers. (Replace file name with route.js and place it under /app/api/auth/[...nextauth]/)
5. env-file.local -> This file is used to store the environment variables. Rename this file to .env and place it in the topmost directory of your project.
