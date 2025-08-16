 # React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
 

FILE STRUCTURE

├── .gitignore
├── README.md
├── backend
    ├── .env.sample
    ├── .flaskenv
    ├── app.py
    ├── db.py
    ├── decorators
    │   └── roles.py
    ├── models.py
    ├── requirements.txt
    └── routes
    │   ├── auth_routes.py
    │   ├── cart_routes.py
    │   ├── order_items.py
    │   ├── order_routes.py
    │   └── product_routes.py
└── frontend
    ├── .gitignore
    ├── eslint.config.js
    ├── index.html
    ├── package-lock.json
    ├── package.json
    ├── postcss.config.js
    ├── src
        ├── App.jsx
        ├── assets
        │   ├── home
        │   │   ├── homeImg1.png
        │   │   ├── homeImg2.png
        │   │   └── homeImg3.png
        │   ├── mens
        │   │   ├── ment1.png
        │   │   ├── ment2.png
        │   │   ├── ment3.png
        │   │   ├── mentrousers1.png
        │   │   ├── mentrousers2.png
        │   │   └── mentrousers3.png
        │   ├── react.svg
        │   ├── womenjeans
        │   │   ├── jeansImg1.png
        │   │   ├── jeansImg2.png
        │   │   └── jeansImg3.png
        │   └── womenshirts
        │   │   ├── tshirt1.png
        │   │   ├── tshirt2.png
        │   │   └── tshirt3.png
        ├── components
        │   ├── Button.jsx
        │   ├── Footer.jsx
        │   ├── Navbar.jsx
        │   ├── ProductCard.jsx
        │   ├── Register.jsx
        │   ├── ShowProduct.jsx
        │   ├── common
        │   │   ├── AdminSidebar.jsx
        │   │   ├── Container.jsx
        │   │   ├── Loader.jsx
        │   │   ├── Swiper.jsx
        │   │   └── index.js
        │   └── homepage
        │   │   ├── Categories.jsx
        │   │   ├── Newsletter.jsx
        │   │   ├── PromoBanner.jsx
        │   │   └── TrendingProduct.jsx
        ├── index.css
        ├── main.jsx
        ├── pages
        │   ├── Home.jsx
        │   ├── admin
        │   │   ├── AdminDashboard.jsx
        │   │   ├── AdminHome.jsx
        │   │   ├── AdminProducts.jsx
        │   │   ├── CreateProduct.jsx
        │   │   └── UpdateProduct.jsx
        │   ├── auth
        │   │   ├── Login.jsx
        │   │   └── SignUp.jsx
        │   └── customer
        │   │   ├── AboutPage.jsx
        │   │   ├── CheckoutOrderDetail.jsx
        │   │   ├── CheckoutPage.jsx
        │   │   ├── SearchPage.jsx
        │   │   ├── Shop.jsx
        │   │   ├── SuccessPage.jsx
        │   │   ├── UserProfile.jsx
        │   │   ├── cart
        │   │       └── CartPage.jsx
        │   │   ├── men
        │   │       ├── Mens.jsx
        │   │       ├── MensAll.jsx
        │   │       ├── MensCasualTrousers.jsx
        │   │       ├── MensShirts.jsx
        │   │       └── MensTshirts.jsx
        │   │   └── women
        │   │       ├── Womens.jsx
        │   │       ├── WomensAll.jsx
        │   │       ├── WomensJeans.jsx
        │   │       └── WomensTshirts.jsx
        ├── redux
        │   ├── authApi.js
        │   ├── cartApi.js
        │   ├── orderApi.js
        │   ├── productApi.js
        │   ├── productSlice.js
        │   └── store.js
        └── test
    ├── tailwind.config.js
    └── vite.config.js
