📚 LitBay - Mini E-Commerce Platform

LitBay is a full-stack Mini e-commerce platform built using the MERN stack (MongoDB, Express, React, Node.js) with Tailwind CSS for styling.
It lets users explore, search, and purchase books online — while admins manage products, categories, and orders.
## Features

- Light/dark mode toggle
- Responsive

👥 Users

- Register and log in securely (with Express-Session + Bcrypt for password hashing)

- Browse, search, and filter books by category or journal

- View detailed book information

- Place and track orders

- Persistent sessions and authentication

🧑‍💼 Admin

- Full CRUD for Books (Products)

- Full CRUD for Categories

- Manage orders and view user data

- Dashboard overview for easy management


## Tech Stack

**Client:** React, TailwindCSS

**Server:** Node, Express

**Database:** MongoDB Atlas

**Authentication:** Express-Session, Bcrypt (password hashing)

**Hosting/DevOps:** AWS EC2, Nginx, S3, CloudFront


## Installation

Install LitBay with npm

```bash
git clone https://github.com/hafzism/litbay.git

cd litbay

cd backend
npm install

cd ../frontend
npm install

```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`PORT`

`DATABASE_URI`

`SESSION_SECRET`

`NODE_ENV`

and in frontend , `VITE_API_URL`



## Feedback

If you have any feedback, please reach out to us at hafeezpallath@gmail.com


## Lessons Learned

Building a full MERN app from scratch

CRUD operations with MongoDB & Mongoose

Using Express-Session for authentication

Hosting apps with Nginx + AWS EC2 + S3 + CloudFront

Managing frontend-backend communication using Axios

Responsive UI with Tailwind CSS

## Contributing

Contributions, suggestions, and feedback are always welcome!
If you’d like to improve Libay:

Fork this repository

Create a new branch (feature/new-feature)

Commit your changes

Open a Pull Request 🎉


## License

This project is licensed under the MIT License — feel free to use, modify, and share!

