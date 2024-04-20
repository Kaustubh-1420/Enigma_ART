markdown
Copy code
# Enigma

Welcome to Enigma! This repository contains three main folders:

## Frontend

The `frontend` folder contains the frontend application for artists to sell their artworks. It is built using React. The API for this frontend is hosted using json-server on port 8080.

### Running the Frontend

To run the frontend, navigate to the `frontend` directory and execute the following commands:

```bash
cd frontend
npm install
npm start
Enigma Artist
The enigma-artist folder contains the backend server for managing artists.

Running the Enigma Artist Server
To run the Enigma Artist server, navigate to the enigma-artist directory and execute the following command:

bash
Copy code
cd enigma-artist
npm install
npm run server
Blockchain
The blockchain folder contains the code for storing images on the Ethereum blockchain locally.

Deploying the Artwork Registry Contract
To deploy and interact with the Artwork Registry contract, follow these steps:

Clone the repository:
bash
Copy code
git clone https://github.com/your-username/artwork-registry.git
Navigate to the project directory:
bash
Copy code
cd blockchain
Install dependencies:
bash
Copy code
npm install
Deploy the contract to a local Ethereum network:
bash
Copy code
npx hardhat run scripts/deploy.js --network localhost
Once the contract is deployed, the contract address along with the unique identifier of the artwork will be displayed.
Json Server
The json-server is used to mock the API for the frontend. It serves data from a JSON file named data.json on port 8080.

Running Json Server
To run json-server with data.json on port 8080, execute the following command:

bash
Copy code
json-server --watch data.json --port 8080
Contribution Guidelines
We welcome contributions to Enigma! Please follow these guidelines when contributing:

Fork the repository and make your changes in a feature branch.
Ensure your code follows the existing coding style and conventions.
Write clear and concise commit messages.
Test your changes thoroughly before submitting a pull request.
Provide a detailed description of your changes in the pull request.
Thank you for your interest in contributing to Enigma!

rust
Copy code

Copy and paste this content into your README.md file. Adjust any paths or commands as needed to ma
