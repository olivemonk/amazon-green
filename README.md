# AmazonGreen Admin Panel

Welcome to the AmazonGreen Admin Panel repository! This repository is dedicated to managing the AmazonGreen platform's administrative functions efficiently. Below are the key details and features of our AmazonGreen Admin Panel.

## Project Details

This repository is developed using the following technologies:

- *Next.js 13 App Router*
- *React*
- *Tailwind CSS*
- *Prisma*
- *MySQL*

## Key Features

Our AmazonGreen Admin Panel provides a comprehensive set of tools and functionalities for managing the platform effectively:

- *Shadcn UI for the Admin:* A user-friendly and visually appealing admin interface powered by Shadcn UI.
- *All-in-One CMS, Admin, and API:* Seamlessly integrates Content Management System (CMS), administration tools, and API functionalities.
- *Multi-Vendor Support:* Control multiple vendors and stores through a unified CMS. Manage diverse stores like "Shoe Store," "Laptop Store," and "Suit Store" individually, with automatic generation of API routes for each.
- *Category Management:* Create, update, and delete categories effortlessly.
- *Product Management:* Efficiently manage products by creating, updating, and deleting them.
- *Image Management:* Upload multiple product images and modify them as needed.
- *Filter Creation:* Create, update, and delete filters such as "Color" and "Size" to match products in the creation form.
- *Billboard Management:* Create, update, and delete billboards – prominent texts displayed on top of pages. Attach them to specific categories or use them standalone, with API generation for all scenarios.
- *Search and Pagination:* Easily search through categories, products, sizes, colors, and billboards with included pagination.
- *Featured Products:* Control which products are showcased as "featured," ensuring they appear on the homepage.
- *Order and Sales Monitoring:* View and manage orders and sales conveniently.
- *Revenue Graphs:* Visualize revenue data through graphs, gaining insights into business performance.
- *Clerk Authentication:* Learn and implement Clerk Authentication for enhanced security.
- *Order Creation:* Efficient order creation process for seamless transactions.
- *Stripe Checkout and Webhooks:* Implement Stripe checkout and handle Stripe webhooks for payment processing.
- *MySQL + Prisma + PlanetScale:* Utilize a robust stack featuring MySQL, Prisma, and PlanetScale for efficient database management.

## Prerequisites

Ensure you have the following prerequisites installed:

- Node version 14.x

## Setup Instructions

1. *Install Packages:*
   
   npm install
   

2. *Setup .env File:*
   - Create a `.env` file in the root directory and populate it with the necessary environment variables provided in the documentation.

3. *Connect to PlanetScale and Push Prisma:*
   
   npx prisma generate
   npx prisma db push
   

4. *Start the App:*
   
   npm run dev
   

## Available Commands

You can run the following commands using npm:

- *Start Development Server:*
  
  npm run dev
  

Feel free to explore, contribute, and enhance the AmazonGreen Admin Panel. Let's build a greener future together! 🌱🌎
