
🚀 Hackathon MSU

A modern React web application built for the Hackathon at MSU.

📦 Setup & Installation

1️⃣ Clone the Repository

git clone https://github.com/devjoshi-289/Hackathon-msu.git
cd Hackathon-msu

2️⃣ Install Dependencies

npm install

3️⃣ Run the Development Server

npm run dev

The app will be available at http://localhost:3000/.

🚀 Deploying to GitHub Pages

1️⃣ Install GitHub Pages Package

npm install gh-pages --save-dev

2️⃣ Add Deployment Scripts in package.json

Add the following under "scripts":

"predeploy": "npm run build",
"deploy": "gh-pages -d build"

3️⃣ Deploy

npm run deploy

Your app will be live at:
https://devjoshi-289.github.io/Hackathon-msu/

For direct online output:
  Remote Deployed link :
    https://effortless-kelpie-d7d7b2.netlify.app

📜 License

This project is open-source.
