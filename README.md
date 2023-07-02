# Request Header Parser Microservice

This is a full stack JavaScript app that serves as a request header parser microservice. It extracts and displays information from the request header of an HTTP request.


## Features

- Extracts and displays information from the request header.
- Returns the IP address, preferred language, and software details of the client.

## Installation and Setup

To run this project locally, follow these steps:

1. Clone this repository: `git clone https://github.com/yourusername/request-header-parser.git`
2. Navigate to the project directory: `cd request-header-parser`
3. Install the dependencies: `npm install`
4. Start the application: `npm start`
5. Open your browser and visit `http://localhost:3000` to access the application.

## Usage

Once the application is running, you can use it as follows:

- Send an HTTP GET request to `http://localhost:3000/api/whoami`.
- The response will be a JSON object containing the IP address, preferred language, and software details of the client.

## Example

Here's an example of how to use the request header parser microservice API:

- Request: `http://localhost:3000/api/whoami`
- Response:
  ```json
  {
    "ipaddress": "127.0.0.1",
    "language": "en-US,en;q=0.9",
    "software": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/91.0.4472.124 Safari/537.36"
  }
  ```

## Technologies Used

- Node.js
- Express.js

## License

This project is licensed under the [MIT License](LICENSE).

## Additional Information

This project is part of the FreeCodeCamp curriculum. The main goal of this project is to build a request header parser microservice using JavaScript and showcase the ability to extract and display information from the request header of an HTTP request. The information extracted includes the client's IP address, preferred language, and software details.
