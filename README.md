🛍️ Nxt Trendz – Cart Features
A fully functional e-commerce frontend application built using React.js, implementing cart management, authentication, protected routes, and dynamic product rendering.

🚀 Live Features
🔐 User Authentication (JWT based)
🛒 Add to Cart functionality
➕ Increment / ➖ Decrement product quantity
❌ Remove individual cart items
🧹 Remove all cart items
💰 Dynamic cart total calculation
📦 Prime Deals section
🔍 Filters (Category, Rating, Search, Sort)
🔒 Protected Routes
📱 Fully Responsive Design


🧠 Concepts Used
React Class Components
Context API (Global State Management)
React Router DOM
Protected Routes
Conditional Rendering
API Integration (Fetch)
JWT Authentication
State Management
Dynamic UI Updates


🗂️ Project Structure
src/
 ├── components/
 │   ├── LoginForm
 │   ├── Home
 │   ├── Products
 │   ├── ProductItemDetails
 │   ├── Cart
 │   ├── CartItem
 │   ├── CartSummary
 │   ├── Header
 │   ├── FiltersGroup
 │   ├── PrimeDealsSection
 │   ├── SimilarProductItem
 │   ├── ProtectedRoute
 │   └── NotFound
 ├── context/
 │   └── CartContext
 └── App.js

 
🔑 Login Credentials
Prime User
  username: rahul
  password: rahul@2021
Non-Prime User
  username: raja
  password: raja@2021
  
⚙️ Installation & Setup
Clone the repository:
  git clone https://github.com/YOUR-USERNAME/nxt-trendz-cart-features.git

Navigate into project:
  cd nxt-trendz-cart-features

Install dependencies:
  npm install

Start the application:
  npm start

App runs at:
http://localhost:3000


🌐 APIs Used
  Products API
  Prime Deals API
  Login API
(All provided by CCBP/NxtWave)

🎯 Key Implementation Highlights
Cart logic ensures:
  Same product added multiple times updates quantity
  Cart count in header reflects unique items only
  Quantity update dynamically updates total

Clean separation of components
Context API used for global cart state
Fully tested and passing all test cases

🛠️ Tech Stack
React.js
JavaScript (ES6+)
React Router DOM
Context API
CSS3
Git & GitHub

📌 Future Improvements

Backend integration
Payment gateway integration
Wishlist feature
User profile management
Redux migration

👨‍💻 Author
Aditya Kirdat
Frontend Developer | React Enthusiast
