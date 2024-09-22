<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>README - Next.js Authentication with Token and Cookies</title>
</head>
<body>
  <h1>Next.js Authentication with Token and Cookies</h1>

  <p>This project demonstrates how to implement authentication in a Next.js application using tokens and cookies. It showcases secure user login, logout, and user profile functionalities, storing authentication tokens in cookies.</p>

  <h2>Features</h2>
  <ul>
    <li>User signup and login functionality</li>
    <li>Token-based authentication stored in cookies</li>
    <li>Securely handle user sessions and data</li>
    <li>Profile page with user details fetched using an authentication token</li>
    <li>Logout functionality to clear cookies and invalidate the session</li>
    <li>Server-side authentication handling with APIs</li>
  </ul>

  <h2>Tech Stack</h2>
  <ul>
    <li><strong>Next.js</strong>: React framework for server-side rendering and static site generation</li>
    <li><strong>Axios</strong>: To handle HTTP requests</li>
    <li><strong>JWT (JSON Web Token)</strong>: For token-based authentication</li>
    <li><strong>Cookies</strong>: Used to store authentication tokens</li>
    <li><strong>Tailwind CSS</strong>: For styling components</li>
    <li><strong>Vercel</strong>: Deployment platform for frontend</li>
  </ul>

  <h2>Setup</h2>
  <ol>
    <li>Clone the repository:</li>
    <pre><code>git clone https://github.com/Abhi96k/nextjs_auth_token_cookies.git</code></pre>

    <li> Navigate to the project directory: </li>
    <pre><code>cd nextjs_auth_token_cookies</code></pre>

    <li>Install the dependencies:</li>
    <pre><code>npm install</code></pre>

    <li>Set up environment variables:</li>
    <p>Create a <code>.env.local</code> file and add the following variables:</p>
    <pre><code>JWT_SECRET=your_jwt_secret
NEXT_PUBLIC_API_URL=http://localhost:3000/api
</code></pre>

    <li>Run the development server:</li>
    <pre><code>npm run dev</code></pre>

    <li>Visit <a href="http://localhost:3000">http://localhost:3000</a> to see the application in action.</li>
  </ol>

  <h2>API Endpoints</h2>
  <ul>
    <li><strong>POST</strong> <code>/api/users/signup</code>: Handles user signup by creating a new user.</li>
    <li><strong>POST</strong> <code>/api/users/login</code>: Authenticates the user and returns a token stored in cookies.</li>
    <li><strong>GET</strong> <code>/api/users/me</code>: Fetches authenticated user details.</li>
    <li><strong>GET</strong> <code>/api/users/logout</code>: Clears the authentication cookies and logs the user out.</li>
  </ul>

  <h2>Project Structure</h2>
  <ul>
    <li><strong>/pages</strong>: Contains the Next.js page components like login, signup, profile, etc.</li>
    <li><strong>/api</strong>: API routes for handling authentication (login, logout, signup).</li>
    <li><strong>/components</strong>: Reusable React components like forms and buttons.</li>
    <li><strong>/styles</strong>: Global and component-specific styles using Tailwind CSS.</li>
  </ul>

  <h2>Deployment</h2>
  <p>The app is designed to be deployed on <strong>Vercel</strong>. To deploy:</p>
  <ol>
    <li>Push the repository to GitHub.</li>
    <li>Link the repository to Vercel.</li>
    <li>Add environment variables in Vercel's settings.</li>
    <li>Deploy the project.</li>
  </ol>

  <h2>License</h2>
  <p>This project is licensed under the MIT License.</p>
</body>
</html>
