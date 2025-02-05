# Next.js 15 Navigation Bug

This repository demonstrates a navigation issue in a Next.js 15 application.  The app consists of two pages: a home page and an about page. Navigation to the about page works as expected; however, the button to navigate back to the home page does not function correctly.  The bug and its solution are described in detail in the associated files.

## Bug
The `router.push('/')` call within the `handleClick` function in `pages/about.js` does not trigger navigation back to the home page. 

## Solution
The issue is resolved by ensuring that the `router.push('/')` method is correctly used. The provided solution ensures the correct behavior.

## How to reproduce
1. Clone this repository.
2. Run `npm install` to install the necessary dependencies.
3. Run `npm run dev` to start the development server.
4. Navigate to the about page.
5. Click the 'Go Back Home' button and observe that the navigation doesn't work as expected.