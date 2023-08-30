
# ThreeJs AI shirt customizer

This project allows the user to customize a shirt by either uploading a logo or using an AI prompt to design a logo for the shirt or design the whole shirt. This would allow user an idea to how the shirt will look like with the design.
## Tech Stack

**Client:** React, Vite, TailwindCSS, React Three Fiber, Framer Motion

**Server:** Node, Express


## Development
Sure, here's how you could structure the development and deployment section in your GitHub README:

## Development and Deployment

### Frontend

#### Development

1. Navigate to the `client` directory:
   ```
   cd client
   ```

2. Install frontend dependencies:
   ```
   npm install
   ```

3. Start the Vite development server:
   ```
   npm run dev
   ```

   This will launch the development server with hot module replacement (HMR), allowing you to see changes instantly as you code.

#### Build for Production

To create a production-ready build:

1. In the `client` directory:
   ```
   npm run build
   ```

2. The optimized build files will be generated in the `dist` directory. You can deploy these files to your web server or hosting platform.

### Backend

#### Development

1. Navigate to the `server` directory:
   ```
   cd server
   ```

2. Install backend dependencies:
   ```
   npm install
   ```

3. Start the Express server using nodemon for automatic restarts on code changes:
   ```
   npm start
   ```

   Your backend server will be accessible at the specified port (usually 3000) by default.

### How to Run Locally

1. Clone this repository:
   ```
   git clone git@github.com:avengeance/threejs.git
   ```

2. Follow the frontend and backend development steps mentioned above to set up and run both parts of the project locally.

3. Make sure to set up environment variables as specified in `.env` files and configure APIs and services accordingly.

### Deployment

1. Frontend:
   - After building the frontend using `npm run build`, you'll have optimized files in the `dist` directory.
   - Deploy these files to your web server or hosting platform of choice.

2. Backend:
   - Deploy the backend server to your preferred hosting platform (e.g., Heroku, AWS, etc.).
   - Make sure to configure environment variables for production, including sensitive information.


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`OPENAI_API_KEY`


