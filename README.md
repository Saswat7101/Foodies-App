# NextLevel Food

A platform for foodies to share their favorite recipes with the world. It's a place to discover new dishes and connect with other food lovers.

## Features

- **Browse Meals**: Explore a collection of delicious meals shared by the vibrant community.
- **Share Recipes**: Submit your favorite recipes with details like title, summary, instructions, and images.
- **Community**: Join the community to connect with fellow food enthusiasts.
- **Image Upload**: Upload images for your shared meals using the built-in image picker.

## Tech Stack

- **Framework**: Next.js 15
- **Frontend**: React 19
- **Database**: SQLite (via better-sqlite3)
- **Styling**: CSS Modules
- **Utilities**: slugify, xss for security

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd foodies-app
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the development server:

   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

## Usage

- **Home Page**: Introduction to the platform with links to explore meals and join the community.
- **Meals Page**: Browse all shared meals. Click on a meal to view details.
- **Share Meal**: Fill out the form to share your favorite recipe. Includes fields for name, email, title, summary, instructions, and image upload.
- **Community Page**: Connect with other food lovers.

## Scripts

- `npm run dev`: Start the development server
- `npm run build`: Build the app for production
- `npm run start`: Start the production server
- `npm run lint`: Run ESLint for code linting

## Project Structure

- `app/`: Next.js app directory with pages and layouts
- `components/`: Reusable React components
- `lib/`: Utility functions and database interactions
- `assets/`: Static assets like images
- `public/`: Publicly accessible files

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is private.
