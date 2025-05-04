# ✨ ShopCart - E-Commerce Website ✨

ShopCart is a modern e-commerce platform featuring product listings, shopping cart functionality, and user authentication.

## Features ⚡

- 🛍️ Product catalog with categories
- 🛒 Interactive shopping cart with quantity adjustment
- 🔐 User authentication (login/signup)
- 🔍 Product detail pages
- 🚀 Responsive design for all devices
- 🔄 Real-time cart updates using localStorage

## Technologies Used 🚀

- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Custom CSS with responsive design
- **Authentication**: Firebase Authentication
- **Hosting**: GitHub

## Project Structure 🧾
shopcart/ <br>
├── index.html - Homepage with product listings <br>
├── cart.html - Shopping cart page <br>
├── item.html - Product detail page <br>
├── login.html - User login page <br>
├── signup.html - User registration page <br>
├── index.css - Main stylesheet <br>
├── item.css - Product page styles <br>
├── Pics/ - Image assets <br>
└── README.md - Project documentation <br>

## Getting Started 💥

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

## Contributing ⭐
Contributions are welcome! Please follow these steps:
1. Fork the project
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

⭐️ Support the Project If you find this project helpful, please consider giving it a star on GitHub! Your support helps to grow the project and reach more contributors.
