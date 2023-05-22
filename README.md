# Request Header Parser Microservice

This is a simple Node.js application that acts as a Request Header Parser Microservice. It provides an API endpoint that returns information from the request headers.

## How to Use

1. Clone the repository or download the code.
2. Make sure you have Node.js and npm installed on your system.
3. Install the dependencies by running `npm install`.
4. Start the server by running `node index.js`.
5. The server will start running on `http://localhost:3000`.
6. Access the API endpoint at `http://localhost:3000/api/whoami`.
7. The API will return a JSON response containing the requester's IP address, preferred language, and software/browser information.

## API Endpoint

- `GET /api/whoami`: Returns a JSON object with the requester's IP address, preferred language, and software/browser information from the request headers.

## Example Response

```json
{
  "ipaddress": "::ffff:127.0.0.1",
  "language": "en-US,en;q=0.9",
  "software": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/90.0.4430.212 Safari/537.36"
}
