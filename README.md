<h1>MERN Stack AI Chatbot</h1>
<p>An AI Chatbot application inspired by ChatGPT, built using the MERN stack and OpenAI API.</p>

<h2>Overview</h2>
<p>This customized chatbot allows users to have conversational interactions with an AI, and all user messages are stored in a database for future retrieval or deletion. The application emphasizes both functionality and security.</p>

<h2>Features</h2>
<ul>
  <li>AI-powered chatbot using OpenAI API</li>
  <li>Message storage in MongoDB for future retrieval</li>
  <li>Message deletion feature</li>
  <li>Fully secure with:</li>
  <ul>
    <li>JWT (JSON Web Tokens) for authentication</li>
    <li>HTTP-Only Cookies</li>
    <li>Signed Cookies</li>
    <li>Password encryption for user accounts</li>
    <li>Middleware chains for request validation and security</li>
  </ul>
</ul>

<h2>Security</h2>
<p>This application prioritizes security, employing a range of techniques to protect user data and ensure the integrity of the communication, including:</p>
<ul>
  <li><strong>JWT Authentication:</strong> Secure token-based user authentication to protect API endpoints.</li>
  <li><strong>HTTP-Only Cookies:</strong> Used to store authentication tokens securely, inaccessible via JavaScript.</li>
  <li><strong>Signed Cookies:</strong> Cookies are signed to prevent tampering.</li>
  <li><strong>Password Encryption:</strong> Passwords are hashed and salted before being stored.</li>
  <li><strong>Middleware Chains:</strong> Predefined middleware chains are used for handling authentication, validation, and other operations.</li>
</ul>

<h2>Technologies</h2>
<ul>
  <li><strong>Frontend:</strong> React (as part of the MERN stack)</li>
  <li><strong>Backend:</strong> Node.js with Express</li>
  <li><strong>Database:</strong> MongoDB</li>
  <li><strong>Authentication:</strong> JWT (JSON Web Tokens), HTTP-Only Cookies, Signed Cookies</li>
  <li><strong>AI:</strong> OpenAI API for natural language processing and chatbot interaction</li>
</ul>

<h2>Getting Started</h2>
<p>To get the application running locally, follow these steps:</p>

<h3>1. Clone the Repository</h3>
<pre><code>git clone https://github.com/your-repo/mern-chatbot.git</code></pre>

<h3>2. Install Dependencies</h3>
<p>In both the <code>client</code> and <code>server</code> directories, run the following command:</p>
<pre><code>npm install</code></pre>

<h3>3. Setup Environment Variables</h3>
<p>Create a <code>.env</code> file in the <code>server</code> directory and include the following:</p>
<ul>
  <li>JWT_SECRET</li>
  <li>OPENAI_API_KEY</li>
  <li>MONGO_URI</li>
</ul>

<h3>4. Run the Application</h3>
<p>To start both the frontend and backend servers, run:</p>
<pre><code>npm run dev</code></pre>
<p>The React frontend will start on <a href="http://localhost:3000">http://localhost:3000</a> and the backend on <a href="http://localhost:5000">http://localhost:5000</a>.</p>

<h2>Contributing</h2>
<p>Contributions are welcome! If you want to contribute, feel free to fork the repository and submit a pull request.</p>
