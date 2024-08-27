# Dream Homes

## Overview

**Dream Homes** is a property rental platform that connects property owners and potential renters. The platform allows owners to post properties for rent, while regular users can explore and rent these properties. This project is built using the MERN stack, featuring a range of functionalities designed to enhance user experience.

## Features

- **User Authentication:** Secure Google login for both owners and renters.
- **Property Listing:** Owners can easily list their properties for rent.
- **Real-Time Chat:** Facilitates communication between owners and renters using Socket.io.
- **Video Calls:** Enables virtual tours and face-to-face interactions.
- **Payments:** Integration with PayPal for secure transactions.
- **Real-Time Notifications:** Instant updates on property status and messages.

## Tech Stack

- **Frontend:** React.js, Tailwind CSS, Material Tailwind, Material UI
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** Google OAuth
- **Payments:** PayPal (Stripe integration planned)
- **Real-Time Features:** Socket.io
- **Styling:** Tailwind CSS for customization and responsiveness

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/fazil8848/Dream-Homes.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd Frontend
   ```
   **Install the dependencies:**
   ```bash
   npm install
   ```
3. **Navigate to the project directory:**
   ```bash
   cd Backend
   ```
   **Install the dependencies:**
   ```bash
   npm install
   ```
4. **Set up environment variables:**

   - Create a `.env` file in both frondend and backed directories.
   - 1. **Environment variables Frontend :**
        - REACT_APP_ADMIN_URL = ''
        - REACT_APP_USERS_URL = ''
        - REACT_APP_OWNER_URL = ''
        - REACT_APP_GOOGLE_API_KEY = ''
        - REACT_APP_PAYPAL_CLIENT_ID = ''
        - REACT_APP_PAYPAL_SECRET_KEY = ''
        - REACT_APP_PAYPAL_ACCESS_TOKEN = ""
        - REACT_APP_GOOGLE_AUTH_CLIENT_ID = ""
        - REACT_APP_GOOGLE_AUTH_SECRET_KEY = ""
        - REACT_APP_ZEGO_APP_SECRET = ""
        - REACT_APP_ZEGO_APP_ID =
        - REACT_APP_NEWS_API_KEY = ''
        - REACT_APP_SOCKET_URL = ''
   - 2. **Environment variables Backend :**
        - MONGODB_URL = ""
        - JWT_SECRET = ''
        - PORT=
        - NODE_ENV= ''
        - NODEMAILER_EMAIL = ''
        - NODEMAILER_PASS = ''
        - USER_BASE_URl= ''
        - OWNER_BASE_URl= ''
        - CLOUDINARY_NAME = ''
        - CLOUDINARY_KEY = ''
        - CLOUDINARY_SECRET = ''
        - PAYPAL_CLIENT_ID = ''
        - PAYPAL_CLIENT_SECRET = ''

5. **Start the development server:**
   - Backend:
   ```bash
   npm start
   ```
   - Fontend:
   ```bash
   npm run dev
   ```

## Usage

- **Frontend:** Visit `http://localhost:3000` in your browser.
- **Backend:** The API runs on `http://localhost:5000`.

## Future Enhancements

- **Stripe Integration:** Adding Stripe for more payment options.
- **Additional Logins:** GitHub and Facebook authentication.
- **Advanced Search:** Filters based on property features and location.
- **Improved UI/UX:** Continuous enhancements for better user experience.

## Contributing

Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, reach out to me at [fazilofficial05@gmail.com](mailto:fazilofficial05@gmail.com).
