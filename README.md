# TeamUp

## Problem Statement
A real-world issue we've encountered while looking for a team to participate in a hackathon is finding a random teammate or team and synchronizing our abilities. TeamUp helps users search for teams using multiple filters and learn about each other via user portfolios.

## Features
- User and Admin Authentication
- Team Creation & Searching
- Collaboration (Chat Feature)
- Team and User Profiles

## Tech Stack
**Client:** React.js, Redux, Material UI  
**Server:** Node.js (Express.js)  
**Database:** MongoDB  
**Others:** Socket.io, AWS S3

---

## Environment Variables
To run this project, you need to add the following variables to your `.env` file in the root directory:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

---

## Run Locally

### Clone the project
```bash
git clone https://github.com/veerreshr/team-maker.git
cd team-maker
```

### Install dependencies
```bash
npm install
```

### Go to the frontend directory and install dependencies
```bash
cd frontend
npm install
```

### Return to the root directory
```bash
cd ..
```

### Start the server
```bash
npm run dev
```

---

## Contributing
Contributions are always welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any queries or issues, reach out to [muskankandoi17@gmail.com].

