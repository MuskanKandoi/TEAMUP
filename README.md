Team Up
The problem Team Up solves
A real-world issue we've encountered while looking for a team to participate in a hackathon is finding a random teammate or team and synchronising our abilities as best we can, which is extremely difficult to do with people we don't know anything about. Team Maker attempts to address this issue by allowing users to search for teams using multiple filters and learn about one another via user portfolios.

Features
User and Admin Authentication.
Creation of Teams.
Searching for Teams.
Colloboration with Teams( Chat functionality ).
List of all events like hackathons, competitions(for now we only support few events).
Custom addition of events by Admin.
Team and User Profiles.
Tech Stack
Client: React Js, Redux, Material UI

Server: Node Js ( Express Js )

Database: MongoDB

Others: Socket.io, AWS S3

Environment Variables
To run this project, you will need to add the following environment variables to your .env file in root directory.

MONGO_URI

JWT_SECRET

Run Locally
Clone the project

git clone https://github.com/veerreshr/team-maker.git
Go to the project directory

cd team-maker
Install dependencies

npm install
Go to the fronend directory

cd frontend
Install dependencies

npm install
Go to the root directory

cd ..
Start the server

npm run dev
