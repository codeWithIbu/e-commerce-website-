Technologies Used
Frontend: React 18

State Management: Redux

Routing: React Router 6

Styling: Custom CSS with Tailwind-inspired design

UI Features: Glassmorphism, gradient accents, responsive design

Installation
Clone the repository:

bash
git clone https://github.com/yourusername/shopelegance.git
cd shopelegance
Install dependencies:

bash
npm install
Start the development server:

bash
npm run dev
Open your browser at:

text
http://localhost:3000
Project Structure
text
src/
├── components/
│   └── Header.jsx        # Navigation header
├── pages/
│   ├── Home.jsx          # Home page
│   ├── ProductDetail.jsx # Product details
│   ├── Cart.jsx          # Shopping cart
│   └── NotFound.jsx      # 404 page
├── redux/
│   └── store.js          # Redux store
├── App.jsx               # Main application
├── main.jsx              # Entry point
└── index.css             # Global styles
Features
Modern Glassmorphism UI - Semi-transparent header with backdrop blur

Vibrant Gradient Accents - Purple-to-indigo gradients throughout

Fully Responsive Design - Adapts to mobile, tablet, and desktop

Interactive Cart System - With badge notifications

Smooth Animations - Hover effects and transitions

Code Splitting - Optimized loading with React.lazy

Redux State Management - Centralized cart and product state