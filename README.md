# 🛒 Product Store & Inventory Manager

A full-stack **MERN** application for managing products and inventory in real time. Built with a clean MVC architecture, RESTful API design, and a responsive React.js UI featuring dark/light mode.

---

## 🚀 Tech Stack

| Layer      | Technology                          |
|------------|-------------------------------------|
| Frontend   | React.js, CSS3, Responsive UI       |
| Backend    | Node.js, Express.js                 |
| Database   | MongoDB                             |
| API Style  | RESTful (10+ routes)                |
| Architecture | MVC (Model-View-Controller)       |

---

## ✨ Features

- 📦 **Full CRUD Operations** — Create, Read, Update, and Delete products in real time
- 🔗 **10+ RESTful API Routes** — Clean, well-structured endpoints for all product operations
- 🏗️ **MVC Architecture** — Separation of concerns for maintainable, scalable code
- ⚡ **Optimised MongoDB Queries** — Efficient data retrieval and manipulation
- 🌗 **Dark / Light Mode Toggle** — Seamless theme switching across the entire UI
- 📱 **Fully Responsive** — Works across all device sizes (mobile, tablet, desktop)

---

## 📁 Project Structure

```
MERN_PS/
├── Backend/
│   ├── models/          # Mongoose data models
│   ├── routes/          # Express API route handlers
│   ├── controllers/     # Business logic (MVC controllers)
│   └── server.js        # Express app entry point
├── Frontend/
│   ├── src/
│   │   ├── components/  # Reusable React components
│   │   ├── pages/       # Page-level components
│   │   └── App.jsx      # Root component with theme toggle
│   └── public/
├── .env                 # Environment variables (root level)
├── package.json
└── README.md
```

---

## 🛠️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+)
- [MongoDB](https://www.mongodb.com/) (local or Atlas)
- [Git](https://git-scm.com/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/jahidunfarabi/MERN_PS.git
   cd MERN_PS
   ```

2. **Set up the backend**
   ```bash
   cd Backend
   npm install
   ```

3. **Configure environment variables**

   A `.env` file is already present at the project root. Update it with your values:
   ```env
   MONGO_URI=your_mongodb_connection_string
   PORT=5000
   ```

4. **Set up the frontend**
   ```bash
   cd ../Frontend
   npm install
   ```

### Running the App

**Start the backend server:**
```bash
cd Backend
npm run dev
```

**Start the frontend (in a new terminal):**
```bash
cd Frontend
npm run dev
```

The app will be available at `http://localhost:5173` (Vite default) or `http://localhost:3000`.

---

## 🔌 API Endpoints

| Method | Endpoint              | Description            |
|--------|-----------------------|------------------------|
| GET    | `/api/products`       | Fetch all products     |
| GET    | `/api/products/:id`   | Fetch a single product |
| POST   | `/api/products`       | Create a new product   |
| PUT    | `/api/products/:id`   | Update a product       |
| DELETE | `/api/products/:id`   | Delete a product       |

> Additional routes handle filtering, sorting, and inventory-specific operations.

---

## 📸 Screenshots

> _Add screenshots of your UI here (dark mode & light mode views recommended)._

---

## 🌱 Future Improvements

- [ ] JWT-based authentication and user accounts
- [ ] Product categories and search/filter functionality
- [ ] Pagination for large inventory lists
- [ ] Stock alert notifications

---

## 👨‍💻 Author

**MD Jahidun Muntaka Farabi**  
BSc in Computer Science & Engineering — AIUB  
📧 [jahidunmuntaka25@gmail.com](mailto:jahidunmuntaka25@gmail.com)  
🔗 [LinkedIn](https://linkedin.com) | [GitHub](https://github.com/jahidunfarabi) 

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
