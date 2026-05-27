# mern-product-store 

A simple full-stack product management system built with the MERN stack. You can add, update, delete and view products. It also has a dark/light mode toggle!

---

## What I used to build this

- **Frontend** - React.js
- **Backend** - Node.js, Express.js
- **Database** - MongoDB
- **Styling** - CSS3 (fully responsive)

---

## Features

- ✅ Add a new product
- ✅ View all products
- ✅ Update a product
- ✅ Delete a product
- ✅ Dark mode / Light mode toggle
- ✅ Works on mobile and desktop

---

## Project Structure

```
mern-product-store/
├── Backend/        → Express server, API routes, MongoDB models
├── Frontend/       → React app (components, pages)
├── .env            → Your environment variables (don't share this!)
└── package.json
```

---

## How to run this project locally

### You'll need

- Node.js installed
- MongoDB (local or MongoDB Atlas)

### Steps

**1. Clone the repo**
```bash
git clone https://github.com/jahidunfarabi/mern-product-store.git
cd mern-product-store
```

**2. Setup backend**
```bash
cd Backend
npm install
```

**3. Create a `.env` file in the root folder**
```
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

**4. Setup frontend**
```bash
cd ../Frontend
npm install
```

**5. Run backend** (Terminal 1)
```bash
cd Backend
npm run dev
```

**6. Run frontend** (Terminal 2)
```bash
cd Frontend
npm run dev
```

Now open your browser and go to → `http://localhost:5173`

---

## API Routes

| Method | Route | What it does |
|--------|-------|-------------|
| GET | `/api/products` | Get all products |
| GET | `/api/products/:id` | Get one product |
| POST | `/api/products` | Add a new product |
| PUT | `/api/products/:id` | Update a product |
| DELETE | `/api/products/:id` | Delete a product |

---

## Screenshots

> Coming soon...

---

## What I want to add next

- [ ] User login / signup
- [ ] Search and filter products
- [ ] Pagination

---

## Made by

**Jahidun Muntaka Farabi**  
📧 jahidunmuntaka25@gmail.com  
🔗 [GitHub](https://github.com/jahidunfarabi)
