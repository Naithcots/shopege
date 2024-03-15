# Shopege
![thumbnail](https://naithcots.ovh/projects/shopege.png)
> The simulation of an e-commerce store platform including account and payment systems.

[Live Version Preview](https://shopege.naithcots.ovh/)

## Technologies and Modules
### Frontend

 - **React** (client library)
 - Vite (environment)
 - Zustand (client state management)
 - React Hook Form
 - Radix UI
 - TailwindCSS

### Backend

 - **Node.js**
 - Express (web server framework)
 - **PostgreSQL** (database)
 - pg-promise (raw database driver)

### Mixed

- Stripe (payment module)
 - Zod (validation of requests and forms)

## What I've learned?

 1. For the first time I created an API with raw database driver instead of ORM and query builders. I had to write SQL queries and take care of potential security issues such as SQL injections.
 2. At was also my first opportunity to use Stripe platform. I implemented a custom payment flow for orders on the website and created my first webhook to catch events.
