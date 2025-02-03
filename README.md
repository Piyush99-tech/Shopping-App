Shopping App 🛒
A simple shopping app built with React and Redux for state management. This app allows users to browse products, add items to their cart, and manage their shopping experience efficiently.

🚀 Features
Product Listing: Displays a list of available products.
Add to Cart: Users can add/remove items from the cart.
Redux State Management: Efficiently manages global state.
Responsive UI: Optimized for different screen sizes.
🛠 Tech Stack
React (Frontend Framework)
Redux (State Management)
React Router (Navigation)
CSS Modules (Styling)
📂 Folder Structure
bash
Copy
Edit
/src
│── components       # Reusable UI components  
│── pages            # Main pages (Home, Cart, etc.)  
│── redux            # Redux store and slices  
│── App.js           # Root component  
│── index.js         # Entry point  
│── data.js          # Sample product data  
│── index.css        # Global styles  
⚡ Installation & Setup
Clone the repository:
sh
Copy
Edit
git clone <your-repo-url>
cd shopping-app
Install dependencies:
sh
Copy
Edit
npm install
Run the development server:
sh
Copy
Edit
npm run dev
💡 How It Works
The Redux store manages product and cart data.
Reducers & actions handle adding/removing items from the cart.
React components fetch and display products dynamically.
