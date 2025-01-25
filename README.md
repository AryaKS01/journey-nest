# Journey-Nest

Journey-Nest is a web application designed to enhance your travel planning experience. It allows users to create accounts, manage travel listings and destinations, and interact with the community through comments and reviews.

## Features

- **User Authentication**:
  - Secure login and signup functionalities.
  - User-specific session management.

- **Destination Management**:
  - Add new travel listings or destinations.
  - View details of all added destinations.

- **Community Interaction**:
  - Leave comments on listings to share thoughts or ask questions.
  - Add reviews with star ratings for destinations.
  - Delete personal comments when needed.

- **Additional Features**:
  - Fully responsive design for an optimal user experience across devices.
  - Visualize data and interactions dynamically.

## Tech Stack

### Frontend
- **HTML**: Structuring the application.
- **CSS**: Styling and layout designs.
- **EJS (Embedded JavaScript)**: Templating engine for server-side rendering.

### Backend
- **Node.js**: JavaScript runtime for server-side development.
- **Express.js**: Web framework for building robust APIs and application logic.

### Database
- **MongoDB**: NoSQL database for managing data such as users, destinations, comments, and reviews.

### Authentication
- **Passport.js**: Authentication middleware for managing user logins securely.

### Media Storage
- **Cloudinary**: Cloud-based media storage for images and other assets.

## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AryaKS01/journey-nest.git
   cd journey-nest
   ```

2. **Install Dependencies**:
   Ensure Node.js and npm are installed on your system. Then run:
   ```bash
   npm install
   ```

3. **Environment Configuration**:
   Create a `.env` file in the root directory and configure the following environment variables:
   ```env
   MONGO_URI=<your-mongodb-connection-string>
   CLOUDINARY_URL=<your-cloudinary-api-url>
   SESSION_SECRET=<your-session-secret>
   ```

4. **Start the Server**:
   ```bash
   npm start
   ```
   The application will be accessible at `http://localhost:3000`.

## Usage

1. **Sign Up/Login**:
   Create an account or log in to access all features.

2. **Add Destinations**:
   Use the "Add Listing" feature to contribute new destinations.

3. **Explore**:
   Browse and interact with travel listings added by others.

4. **Engage**:
   Leave comments, reviews, and star ratings for destinations.

## Contributing

We welcome contributions to enhance Journey-Nest. Here's how you can contribute:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add a meaningful commit message'
   ```
4. Push your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

Special thanks to the contributors and the open-source community for their invaluable support in building this application.

---
