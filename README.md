# Preliminary
PASTE FRONTEND REPO (https://github.com/resa18/react-news-app) TO FRONTEND FOLDER

# Setting Backend
1. Go to backend folder
2. Create .env from .env.example (adjust if any parameter need to be changes regarding your local requirement)
3. composer install

# Setting Frontend
1. Go to frontend folder
2. npm install --force

# Setting Docker
1. setting up docker-compose.yaml file. Adjusted with your local settings
2. open cli on root folder > run "docker compose up" and wait the process
3. Run : docker exec testlaravel-backend-1 php artisan migrate
4. Run :docker compose up

# Run this application
1. Open your browser
2. Go to localhost:3000 (by default i use port 3000 for react project)
3. You can regis user first if you running this app at the first time
4. After register user, you can do login and run the application

