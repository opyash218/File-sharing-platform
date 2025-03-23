# File Sharing System

A file-sharing application built using Node.js, allowing users to upload, download, and share files securely.

## Features
- User Authentication (Register/Login)
- Upload & Download Files
- Secure File Sharing with Unique Links
- File Expiration & Deletion
- Profile Management

## Tech Stack
- **Backend:** Node.js, Express.js
- **Database:** MongoDB/MySQL (Choose based on preference)
- **Authentication:** JWT, bcrypt
- **Storage:** AWS S3, Local Storage, or Cloudinary
- **Frontend (Optional):** React.js, EJS, or any preferred framework
- **Deployment:** AWS, Heroku, or Vercel

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/opyash218/File-sharing-platform.git
   cd file-sharing-system
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables in a `.env` file:
   ```sh
   PORT=5000
   DB_URI=your_database_url
   JWT_SECRET=your_secret_key
   STORAGE_PATH=your_storage_location
   ```
4. Run the application:
   ```sh
   npm start
   ```
5. Open in browser:
   ```sh
   http://localhost:5000
   ```

## API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| POST | /api/auth/register | Register a new user |
| POST | /api/auth/login | User login |
| POST | /api/files/upload | Upload a file |
| GET | /api/files/:id | Download a file |
| DELETE | /api/files/:id | Delete a file |
| GET | /api/files/share/:id | Generate a shareable link |

## Contributing
Feel free to fork this repository and submit pull requests with improvements.



