# Interview-Tayari-Assignment-

Project Live Link: https://interview-tayari-assignment-frontend.onrender.com/

# Setup Instructions for Local system : 

# Set up backend

1. Clone the repo.:
   
git clone https://github.com/12345prashant/Interview-Tayari-Assignment-

3. move to server folder :
cd server 

4. create a .env file iniside server folder

5. inside .env put following keys :
MONGO_URI=mongodb+srv://sahiltripathi03:XQo5Fn521R9LSCVx@interviewtayari-db.hnns5.mongodb.net/?retryWrites=true&w=majority&appName=interviewTayari-db
JWT_SECRET=prashant

6. Run:
npm install

7. Start Backend server:
npx nodemon index.js

# SET UP Frontend

7. Move to client folder :
cd ..
cd client 

8. create a .env inside client folder :
REACT_APP_BASE_URL=http://localhost:5000

9. RUN following command: 
npm install 

10. Start front end server :
npm start




