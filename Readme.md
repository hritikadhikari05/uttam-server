# Backend

---

## Setup
1. Clone the repo
2. Install dependencies
npm install
3. Setup .env with the following variables with the values received from the team
MONGO_URL=mongodb+srv://<user>:<password>@cluster0.qristfw.mongodb.net/<database>?retryWrites=true&w=majority
PORT=
URL= 
TOKEN_KEY=
4. Start the server
npm start

## Available API Endpoints
- /auth/signup
- /auth/login
- /auth/forgot-password
- /auth/reset-password/
- /auth/username-available/
- /user/add-post
- /user/editpost/:id
- /user/getpost/:id
- /user/delete-post
- /user/upvote-post
- /user/downvote-post
- /admin/status/:status
- /admin/update-status
- /admin/assign-reward-point
- /user/get-all-posts
- /user/comment
- /user/solution
- /user/upvote-solution
- /user/downvote-solution
- /user/update-solution-status/
- /user/comment
- /user/accept-solution
- /user/solution/:id
- /comments/:id
- /user/:id
- /user/unredeemed-points
- /dashboard/get-dashboard-details