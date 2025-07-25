chitri_frontend/
├── public/
│   └── (e.g., logo.png, robots.txt, index.html - Vite handles this)
├── src/
│   ├── assets/
│   │   ├── images/
│   │   │   └── (painting images, etc.)
│   │   ├── fonts/
│   │   └── animations/
│   │       └── (GSAP related files if any)
│   ├── components/
│   │   ├── common/
│   │   │   ├── Navbar.jsx
│   │   │   ├── Footer.jsx
│   │   │   ├── LoadingSpinner.jsx
│   │   │   └── ProtectedRoute.jsx
│   │   ├── paintings/
│   │   │   ├── PaintingCard.jsx
│   │   │   └── PaintingSlideshow.jsx
│   │   ├── admin/
│   │   │   ├── AddEditPaintingForm.jsx
│   │   │   └── OrderTable.jsx
│   │   └── ui/
│   │       ├── Button.jsx
│   │       ├── Input.jsx
│   │       └── Modal.jsx
│   ├── hooks/
│   │   └── useAuth.js
│   ├── pages/
│   │   ├── Auth/
│   │   │   ├── LoginPage.jsx
│   │   │   └── SignupPage.jsx
│   │   ├── HomePage.jsx
│   │   ├── PaintingDetailsPage.jsx
│   │   ├── MyCartPage.jsx
│   │   ├── ProfilePage.jsx
│   │   ├── AdminPage.jsx
│   │   ├── OrdersPage.jsx
│   │   └── NotFoundPage.jsx
│   ├── context/
│   │   ├── AuthContext.js
│   │   └── CartContext.js
│   ├── utils/
│   │   ├── firebase.js
│   │   ├── api.js (axios instance)
│   │   ├── helpers.js
│   │   └── constants.js
│   ├── styles/
│   │   ├── index.css (TailwindCSS imports)
│   │   └── animations.css (custom GSAP/Three.js related CSS)
│   ├── App.jsx
│   └── main.jsx
├── tailwind.config.js
├── postcss.config.js
├── vite.config.js
├── .env
├── package.json
└── README.md

chitri_backend/
├── config/
│   ├── db.js (MongoDB connection)
│   ├── firebaseAdmin.js (Firebase Admin SDK init)
│   └── razorpay.js
├── controllers/
│   ├── authController.js
│   ├── paintingController.js
│   ├── userController.js
│   ├── orderController.js
│   └── paymentController.js
├── middleware/
│   ├── authMiddleware.js (JWT verification)
│   └── adminMiddleware.js (Role-based access)
├── models/
│   ├── User.js
│   ├── Painting.js
│   └── Order.js
├── routes/
│   ├── authRoutes.js
│   ├── paintingRoutes.js
│   ├── userRoutes.js
│   ├── orderRoutes.js
│   └── paymentRoutes.js
├── utils/
│   ├── jwt.js
│   └── errorHandler.js
├── .env
├── package.json
├── server.js
└── README.md
