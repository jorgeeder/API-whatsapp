# API-whatsapp
API for sending messages on whatsapp for Brazilian numbers.

## Technologies

-   **[Venom](https://github.com/orkestral/venom)**
-   **[Nodejs](https://nodejs.org/en/)**

## Running The Project

```bash
#install dependencies
npm install
#or 
yarn install

#run the project
npm run dev
# or
yarn dev
```
Scan the QR code that will appear on the terminal to connect the cell phone that will send the messages.

the server will be running on port: 5000

use    **[Insomnia](https://insomnia.rest/)** or **[Postman](https://www.postman.com/)** to test and use

route: http://localhost:5000/send  <br />

json format:
```bash
 {
	"number": "+5500000000000",
	"message": "Olá"
}
```

route: http://localhost:5000/status <br />

to see server status