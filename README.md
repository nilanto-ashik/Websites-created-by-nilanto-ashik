# Ecommerce Website

A full-stack responsive ecommerce web application built with modern web technologies including HTML, CSS, JavaScript, Bootstrap, and the MERN stack.

## 🚀 Features

- **User Authentication**: Secure login and registration system
- **Responsive Design**: Fully responsive layout that works on all devices
- **Product Catalog**: Browse and search through products
- **Shopping Cart**: Add, remove, and manage items in cart
- **User Dashboard**: Personalized user experience
- **Admin Panel**: Manage products, orders, and users
- **Payment Integration**: Secure payment processing
- **Order Management**: Track and manage orders

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with flexbox and grid
- **JavaScript (ES6+)**: Interactive functionality
- **Bootstrap**: Responsive framework for rapid UI development
- **React.js**: Component-based user interface

### Backend
- **Node.js**: Server-side JavaScript runtime
- **Express.js**: Web application framework
- **MongoDB**: NoSQL database for data storage
- **Mongoose**: MongoDB object modeling

## 📁 Project Structure

```
ecommerce-website/
├── client/                 # Frontend React application
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── styles/
│   │   └── utils/
│   └── package.json
├── server/                 # Backend Node.js application
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── package.json
├── README.md
└── package.json
```

## 🔧 Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Clone the Repository
```bash
git clone https://github.com/yourusername/ecommerce-website.git
cd ecommerce-website
```

### Backend Setup
```bash
cd server
npm install
```

Create a `.env` file in the server directory:
```env
MONGODB_URI=mongodb://localhost:27017/ecommerce
JWT_SECRET=your_jwt_secret_key
PORT=5000
```

Start the backend server:
```bash
npm run dev
```

### Frontend Setup
```bash
cd client
npm install
npm start
```

## 🌐 Usage

1. **User Registration/Login**: Create an account or login with existing credentials
2. **Browse Products**: Explore the product catalog with filtering and search options
3. **Shopping Cart**: Add products to cart and proceed to checkout
4. **Payment**: Complete secure payment processing
5. **Order Tracking**: Monitor order status and history

## 📱 Pages Included

- **Login Page**: User authentication
- **Home Page**: Landing page with featured products
- **Product Listing**: Display all products with filters
- **Product Details**: Individual product information
- **Shopping Cart**: Cart management
- **Checkout**: Order placement and payment
- **User Profile**: Account management
- **Admin Dashboard**: Administrative controls

## 🎨 Responsive Design

The website is fully responsive and optimized for:
- Desktop computers (1200px and above)
- Tablets (768px - 1199px)
- Mobile phones (below 768px)

## 🔒 Security Features

- JWT-based authentication
- Password hashing with bcrypt
- Input validation and sanitization
- CORS configuration
- Rate limiting

## 🚀 Deployment

### Frontend Deployment (Netlify/Vercel)
```bash
cd client
npm run build
```

### Backend Deployment (Heroku/Railway)
```bash
cd server
npm start
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Nilanto Ashik - [GitHub Profile](https://github.com/nilanto-ashik)

## 📞 Support

If you have any questions or issues, please open an issue on GitHub or contact us at:
- Email: nilantoashik@gmail.com
- GitHub Issues: [Project Issues](https://github.com/yourusername/ecommerce-website/issues)

## 🎯 Future Enhancements

- [ ] Wishlist functionality
- [ ] Product reviews and ratings
- [ ] Social media integration
- [ ] Multi-language support
- [ ] Advanced analytics dashboard
- [ ] Mobile app development

---

**Made with ❤️ using MERN Stack**
