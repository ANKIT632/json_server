# JSON Server Project

This project sets up a simple JSON server using `json-server` to serve mock data for testing and development purposes.

## Project Structure

```
json-server-project
├── src
│   ├── db.json          # Contains the JSON data served by the server
│   └── server.js        # Entry point for the JSON server
├── package.json         # Configuration file for npm
└── README.md            # Documentation for the project
```

## Getting Started

To set up the project, follow these steps:

1. **Clone the repository** (if applicable):
   ```
   git clone <repository-url>
   cd json-server-project
   ```

2. **Install dependencies**:
   Make sure you have Node.js installed. Then run:
   ```
   npm install
   ```

3. **Run the JSON server**:
   Use the following command to start the server:
   ```
   npm start
   ```

   This will start the JSON server and serve the data from `src/db.json` at `http://localhost:3000`.

## API Endpoints

The server will expose the following endpoints based on the data structure in `db.json`:

- `/questions` - Access the list of questions.

## Customization

You can modify the `src/db.json` file to change the data served by the JSON server. Adjust the structure as needed for your application.

## License

This project is licensed under the MIT License.