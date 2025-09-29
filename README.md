# cookie_session_auth

Example app showing session-based authentication using cookies, express-session and MongoDB session store.

Dependencies
- express
- express-session
- connect-mongo
- cookie-parser
- mongoose
- bcryptjs

Setup
1. Install dependencies: `npm install`
2. Ensure you have a running MongoDB instance and set the connection URI in the code or environment.
3. Start the app: `node app.js`
4. Visit http://localhost:3000 and follow the auth routes in `routes/auth.js`.

Notes
- The app stores sessions in MongoDB using `connect-mongo`.
- See `models/User.js` for the user schema and password hashing.
