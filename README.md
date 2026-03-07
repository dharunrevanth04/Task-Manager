---- Backend Setup
cd backend
npm install

Create a .env file inside the backend folder and add:

MONGO_URI=mongodb://localhost:27017/taskmanager
PORT=5000

Make sure MongoDB is running locally, then:
npm run dev

Backend runs on http://localhost:5000


-------. Frontend Setup
cd frontend
npm install
npm run dev

Frontend runs on http://localhost:5173
