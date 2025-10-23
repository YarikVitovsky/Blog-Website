

# Blog Website

This project demonstrates a clean and professional approach to backend development by separating server-side request handling from business logic.

## Project Purpose
The main goal is to show how organizing code into distinct layers—server and API—improves maintainability, scalability, and clarity in web applications.

## Project Structure
```
Blog Website/
├── .gitignore
├── index.js         # API: business logic, data processing
├── package.json
├── server.js        # Server: request handling, routing
├── solution.js
├── public/
│   └── styles/
│       └── main.css
└── views/
    ├── index.ejs
    └── modify.ejs
```


## How It Works
- `server.js` manages incoming requests, serves static files, and handles routing on port 3000.
- `index.js` contains the API logic, including business rules and data processing, and runs on port 4000.
- This separation makes the codebase easier to maintain and extend.


## Getting Started
1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the main server:
   ```bash
   node server.js
   ```
3. Start the API server:
   ```bash
   node index.js
   ```
4. Visit `http://localhost:3000` for the main site and `http://localhost:4000` for the API.

## Benefits of Separation
- **Maintainability:** Update business logic or server setup independently.
- **Scalability:** Add new features or endpoints without cluttering code.
- **Clarity:** Clear structure for easier collaboration and development.

## License
MIT
