🌟 Promptopia <br>
Promptopia is a dynamic full-stack platform designed to inspire creativity by allowing users to share and discover insightful prompts. Built with Next.js, Node.js, Express, and MongoDB, Promptopia simplifies prompt sharing and searching, enabling users to contribute and find content through an intuitive, tag-based system.

🚀 Live Demo


✨ Features <br>
🌐 Google Authentication: Secure and fast login using Google accounts. <br>
📢 Share Prompts: Post and manage your own creative or useful prompts. <br>
🏠 Explore All Prompts: Discover all user-submitted prompts on the homepage. <br>
🔍 Search Prompts: Search for prompts using tags, keywords, or phrases. <br>
📱 Fully Responsive: Seamless user experience across mobile, tablet, and desktop devices. <br>

🛠 Tech Stack <br>
Frontend <br>
Next.js: A React-based framework with server-side rendering.<br>
React.js: For building dynamic user interfaces.<br>
Tailwind CSS (optional): Used for styling and ensuring responsive design.<br>

Backend<br>
Node.js & Express.js: For API creation and server-side logic.<br>
MongoDB: A NoSQL database to store user data and prompts.<br>
Google OAuth: Authentication using Google’s OAuth 2.0 system.<br>

🛑 Prerequisites<br>
Before running the project, make sure you have the following installed:  <br>

Node.js: Download from here <br>
MongoDB: Use MongoDB Atlas for cloud-based storage or set up a local MongoDB instance. <br>
Google OAuth credentials: Create a project in the Google Developer Console. <br>

🚀 Getting Started <br>
Follow these instructions to set up the project locally. <br>

Clone the Repository <br>
git clone https://github.com/yashraj3340/promptopia.git <br>
cd promptopia <br>

Install Dependencies <br>
npm install <br>

Set up Environment Variables <br>
Create a .env.local file at the root of the project and add the following keys: <br>

MONGODB_URI=<Your_MongoDB_Connection_String> <br>
GOOGLE_CLIENT_ID=<Your_Google_OAuth_Client_ID> <br>
GOOGLE_CLIENT_SECRET=<Your_Google_OAuth_Client_Secret> <br>
NEXTAUTH_URL=http://localhost:3000 <br>

Run the Application <br>
npm run dev <br>
Navigate to http://localhost:3000 to see the app in action. <br>

