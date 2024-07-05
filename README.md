# Blog

Welcome to the **Blog** repository! This project provides a fully functional blogging platform where users can create, edit, and share blog posts. The platform supports user authentication, rich text editing, and responsive design.

## Features

- **User Authentication**: Secure login and registration system.
- **Create & Edit Posts**: Rich text editor for writing and formatting blog posts.
- **Post Management**: View, edit, and delete your posts.
- **Comment System**: Users can comment on posts to interact with the content.
- **Categories & Tags**: Organize posts using categories and tags.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Search Functionality**: Search for posts by title or content.
- **Profile Management**: Users can manage their profiles and view their posts.

## Technologies

- **Frontend**: HTML5, CSS3, JavaScript, React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Deployment**: Netlify, Vercel, Heroku

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/blog.git
   cd blog
   ```

2. **Install frontend dependencies**:
   ```bash
   cd client
   npm install
   ```

3. **Install backend dependencies**:
   ```bash
   cd ../server
   npm install
   ```

4. **Configure the environment variables**:
   - Create a `.env` file in the `server` directory and add your MongoDB URI and JWT secret.
   ```
   MONGO_URI=your_mongo_db_uri
   JWT_SECRET=your_jwt_secret
   ```

5. **Run the backend server**:
   ```bash
   npm start
   ```

6. **Run the frontend application**:
   ```bash
   cd ../client
   npm start
   ```

7. **Access the application**:
   - Navigate to `http://localhost:3000` in your web browser.

## Usage

1. Sign up for a new account or log in if you already have one.
2. Create new blog posts using the rich text editor.
3. Edit or delete your existing posts from the dashboard.
4. Browse posts by categories and tags.
5. Comment on posts to engage with the content.
6. Search for posts by title or content.
7. Manage your profile and view your posts.

## Project Structure

- `client/`: React.js frontend source code
- `server/`: Node.js backend source code
- `public/`: Public assets and static files
- `models/`: MongoDB models for storing user data and blog posts
- `routes/`: API routes for the backend

## License

This project is licensed under the MIT License – see the [LICENSE.md](LICENSE.md) file for details.
