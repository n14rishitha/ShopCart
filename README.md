# ShopCart - E-Commerce Website

![ShopCart Logo](Pics/k-logo.png)

ShopCart is a modern e-commerce platform featuring product listings, shopping cart functionality, and user authentication.

## Features

- 🛍️ Product catalog with categories
- 🛒 Interactive shopping cart with quantity adjustment
- 🔐 User authentication (login/signup)
- 🔍 Product detail pages
- 🚀 Responsive design for all devices
- 🔄 Real-time cart updates using localStorage

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Custom CSS with responsive design
- **Authentication**: Firebase Authentication
- **Hosting**: (Specify if applicable)

## Project Structure
shopcart/
├── index.html - Homepage with product listings
├── cart.html - Shopping cart page
├── item.html - Product detail page
├── login.html - User login page
├── signup.html - User registration page
├── index.css - Main stylesheet
├── item.css - Product page styles
├── Pics/ - Image assets
└── README.md - Project documentation

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- (Optional) Firebase project for authentication

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/shopcart.git
2. Open index.html in your browser to launch the application.

### Firebase Setup (For Authentication)
1. Create a Firebase project at firebase.google.com
2. Enable Email/Password authentication
3. Replace the Firebase config in login.html and signup.html with your project's config:
   ```bash
      const firebaseConfig = {
      apiKey: "YOUR_API_KEY",
      authDomain: "YOUR_AUTH_DOMAIN",
      projectId: "YOUR_PROJECT_ID",
      storageBucket: "YOUR_STORAGE_BUCKET",
      messagingSenderId: "YOUR_SENDER_ID",
      appId: "YOUR_APP_ID"
    };

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the project
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request
