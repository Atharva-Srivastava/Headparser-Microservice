# API : Request Header Parser Microservice

To run this repository:-
- Clone this repository from Github.
- In your favourite Code Editor or IDE run "npm install" to install the neccessary packages.
- Run "node server.js" to start the dvelopement server.

### User stories:

A request to the API by /api/whoami will return a JSON object with your IP address in the ipaddress key.

A request to the API by /api/whoami will return another JSON object with your preferred language in the language key.

A request to the API by /api/whoami will return another JSON object with your software in the software key.

#### Example usage:
* [base_url]/api/whoami

#### Example output:
* `{"ipaddress":"159.20.14.100","language":"en-US,en;q=0.5","software":"Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:50.0) Gecko/20100101 Firefox/50.0"}`
