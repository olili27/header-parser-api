# Request Header Parser Microservice

## Get started

Run :
```bash 
npm install
```

Optionally, you can install nodemon if it is not globally installed locally on your machine by running the command below so that nodemon is installed as a dev-dependency for the project:
```bash
npm i nodemon -D
```

Run the script below to run the server in development mode:
```bash
npm run dev
```

## Route the API

A request to /api/whoami should return a JSON object with your IP address in the ipaddress key.
A request to /api/whoami should return a JSON object with your preferred language in the language key.
A request to /api/whoami should return a JSON object with your software in the software key.

```bash
{"ipaddress":"::1","language":"en-US,en;q=0.9","software":"Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/103.0.0.0 Safari/537.36"}
```
