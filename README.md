# **Zunnoon Store - React E-Commerce Product Store**

## **Overview**
Zunnoon Store is a **modern, high-performance e-commerce platform** built with React, offering a seamless shopping experience with:
- 🛍️ **Product catalog** with filters & search
- 🛒 **Shopping cart** functionality
- 🔐 **User authentication**
- 💳 **Secure checkout** (Stripe integration)
- 📱 **Fully responsive** design

## **Tech Stack**
- **Frontend**: React.js, Next.js (for SSR/SEO)
- **Styling**: Tailwind CSS + CSS Modules
- **State Management**: Redux Toolkit
- **Authentication**: Firebase Auth
- **Database**: Firebase Firestore
- **Payments**: Stripe API
- **Deployment**: Vercel/Netlify

## **Key Features**
1. **Product Management**
   - Product listings with images, prices, ratings
   - Advanced filtering (category, price range, brands)
   - Search functionality

2. **User Experience**
   - Login/Signup (Email + Social Auth)
   - Wishlist functionality
   - Order history tracking

3. **Checkout Flow**
   - Cart management (add/remove/update)
   - Multiple payment options
   - Order confirmation

4. **Admin Panel**
   - Add/edit products
   - Manage orders
   - View analytics

## **Getting Started**

# Clone repository
git clone https://github.com/zunnoonwaheed/React-Ecommerce-Product-Store.git
cd React-Ecommerce-Product-Store

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local

# Run development server
npm run dev


## **Environment Variables**
```env
NEXT_PUBLIC_FIREBASE_API_KEY=your_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_id
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_key
```

## **Project Structure**
```
src/
├── components/       # Reusable UI components
├── context/          # React context providers
├── features/         # Redux slices
├── firebase/         # Firebase config
├── hooks/            # Custom hooks
├── pages/            # Next.js routes
├── public/           # Static assets
├── styles/           # Global styles
├── utils/            # Helper functions
└── services/         # API services
```

## **Customization**
1. **Update branding** in `tailwind.config.js`
2. **Modify products** in Firebase/Firestore
3. **Change Stripe keys** in `.env.local`
4. **Add new features** using the modular structure



**Happy Selling!** 🚀 Your perfect e-commerce solution is ready to go live. Customize it further to match your brand identity and start selling today!
