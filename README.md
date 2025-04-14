step 1---install following packages 

npm create vite@latest
npm i
attach tailwind
npm install @reduxjs/toolkit---------------->for redux toolkit
npm install react-redux----------->for redux
npm install 'react-router-dom'-------------------->for react router
npm install appwrite---------------------->for appwrite
npm install @tinymce/tinymce-react--------->for visual code editor
npm install html-react-parser -------->for converting html to react
npm install react-hook-form->library to manage form state, validation, and submission in a React application.

all the dependencies can be clearly seen on package.json->dependencies




step 2---setting environment variables which keeps on changing from library to library---for vite , next cra all are different 

-->create a file in main project named ".env"
-->note that we never export it to github as it contains sensitive data, so add it to gitignore folder , just right click and add or write manually.
--->but since we also want it for our convience so we create a file named as '.env.sample' keeping contents same as of main '.env' but empty.

✅ Why use .env.example?
It shows other developers what environment variables are needed.
It doesn’t expose secrets, so it’s safe to push to GitHub or share with your team.

to access in app.jsx ----------> import.meta.env.VITE_
to write in .env --------->VITE_



before deploying first  run  npm run build on cli than deploy
if you have env than needs to give key values in v ercel while setting