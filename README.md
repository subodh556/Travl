**Project Overview**
-------------------

This project is a Next.js application, a web platform for listing and renting properties. The codebase is written in TypeScript and utilizes various libraries and frameworks, including React, Next.js, and Prisma.

**Directory Structure**
-----------------------

The project's directory structure is organized as follows:

* `app`: Contains the main application code, including components, hooks, and actions.
* `app/components`: Holds various React components used throughout the application.
* `app/hooks`: Defines custom hooks for managing state and side effects.
* `app/actions`: Contains functions for interacting with the Prisma database and performing business logic.
* `app/libs`: Includes utility libraries, such as the Prisma database client.
* `pages`: Contains Next.js page components.
* `public`: Holds static assets, such as images and fonts.

**Key Components**
------------------

* **Listing**: A component that represents a single property listing, including its details and reservation information.
* **SearchModal**: A modal component that allows users to search for listings based on location, dates, and other criteria.
* **RentModal**: A modal component that enables users to rent a listing, including selecting dates and providing payment information.
* **Favorites**: A component that displays a user's favorite listings.
* **Navbar**: A navigation bar that includes links to various pages and features.

**Functionality**
----------------

The application appears to provide the following functionality:

* Users can search for listings based on location, dates, and other criteria.
* Users can view listing details, including photos, descriptions, and reservation information.
* Users can rent a listing, including selecting dates and providing payment information.
* Users can save listings as favorites.
* Users can view their favorite listings.

**Libraries and Frameworks**
---------------------------

* **Next.js**: A React-based framework for building server-rendered and statically generated websites.
* **React**: A JavaScript library for building user interfaces.
* **Prisma**: A database client for interacting with a PostgreSQL database.
* **TypeScript**: A superset of JavaScript that adds optional static typing and other features.

**Installation**
--------------

To install the project, follow these steps:

1. Clone the repository using `git clone`
2. Install the dependencies using `npm install` 
3. Create a new PostgreSQL database and update the `prisma/.env` file with your database credentials
4. Run `npx prisma migrate dev` to create the database schema
5. Start the development server using `npm run dev` 

