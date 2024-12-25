# Next.js 15 Runtime Error: Accessing Non-Existent Variable

This repository demonstrates a common runtime error in Next.js 15 applications that occurs when accessing a variable that has not been properly declared or initialized.

## Description
The issue arises when attempting to use a variable inside a functional component that has not been defined.
This can lead to unexpected behavior and runtime errors that are difficult to debug.

## Reproduction Steps
1. Clone this repository.
2. Navigate to the `pages` directory.
3. Run `npm install` to install the required packages.
4. Run `npm run dev` to start the development server.
5. Navigate to `/about` in your browser.
6. Observe the runtime error in the console.