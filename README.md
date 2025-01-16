  # ***Don't Forget Your Lists !!***

  A fun and useful checklist app to help you remember everything before leaving your room! Whether it's your keys, your phone, or your pants, this app ensures you never forget the essentials (and some quirky items too)!

## Project Overview :

The Don't Forget List is a personalized checklist app that allows users to create, edit, and manage lists of items they need to remember before leaving their room. With a humorous twist, the app suggests funny and practical items to ensure users start their day with a smile while staying prepared

#### Key Features :

1. ##### User Authentication:

    Users can register for an account and login to view their personalized lists.

2. ##### Customizable Checklist:

    Users can add, edit and delete entries
    Add, edit, delete, and prioritize items based on importance
    Priority labeling (high/low) for must-haves

4. ##### Funny Smart Suggestions:

    Daily ideas of humorous things to include on the list

    For Example: Brain, Backup charger, Socks,ect..,

5. ##### Set Reminders:

    Notifications to remind users of their checklist

    Optional funny reminder messages 

    Don’t be that guy who forgets his keys!

6. ##### List Sharing:

    Users can share their list with friends or family or with your girlfriend


#### Tech Stack :

   ##### Frontend :

   1. React: Fast and modular development of the user interface

   2. Vite: Quick setup for a performant React environment.

   3. CSS/Tailwind CSS: Styling for a visually appealing and responsive design.

   #### Backend :

   1. Node.js: Backend server for handling requests and responses
   2. Express.js: Framework for building RESTful APIs
   3. MongoDB: Database to store user details and lists
   4. Mongoose: To define and interact with the database schema

  #### Hosting and Deployment :
  
  1. Frontend: Hosted on platforms like Netlify or Vercel
  2. Backend: Hosted on Render or Heroku
  3. Database: MongoDB Atlas (cloud-based database)


  #### Installation and Setup :
  
  Follow these steps to set up and run the Don't Forget List application locally:

  ##### Clone the Repository
  
   1. Clone the repository to your local system using the following command:

    git clone https://github.com/your-username/dont-forget-list.git
    cd dont-forget-list

  #### Backend Setup :
  
   1. Navigate to the backend folder:

    cd backend
  
   2. Install dependencies using npm:

    npm install
  
   3. Create a .env file in the backend folder and add the following environment variables:

    MONGO_URI=your-mongodb-uri
    JWT_SECRET=your-secret-key
  
  4. Start the backend server:

    npm start

  #### Frontend Setup :
  
   1. Navigate to the frontend folder:

    cd ../frontend

   2. Install dependencies using npm:

    npm install

   3. Start the development server:

    npm run dev

   4. Open your browser and visit the development URL provided by Vite (usually http://localhost:5173)


  #### Full Application :

  Once both the backend and frontend servers are running:

   1. The backend will be available on the configured port (e.g., http://localhost:5000)
   2. The frontend will connect to the backend API seamlessly


  #### Usage :
   1. Sign up or log in to create your personalized checklist
   2. Add items to your checklist and mark them as high or low priority
   3. Get daily suggestions to make your day more productive and entertaining!
   4. Export or share your checklist with friends or family

  #### Why This Project :
  
  1. Uniqueness:
     
     A humorous twist on a practical concept makes this project stand out. The quirky suggestions keep it engaging and relatable

  2. Skill Development:

     Setting up user authentication
     Building and deploying a full-stack application
     Learning CRUD operations in React and Node.js
     Practicing API design and database management
   
  3. Real-World Relevance:
     
     The project addresses a universal problem: forgetting important items when leaving. It’s both useful and entertaining 

