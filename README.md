[here]: ./LICENSE
[architecture]: ./docs/architecture.md

## Whisp API (Backend)

Whisp API is a simple API for storing and retrieving messages. It is designed to be used as a backend for whisps, a simple open source
cryptographically secure app for sending and receiving messages.

The project borrow's concept's from **Bitcoin's blockchain**, to secure messages.

### Architecture

The architecture is still being decided and once it's done the [Architecture][architecture] document would be updated. I'm still actively
working on building a design which is immuateable and also secure.

### Technologies used

The following technologies are used in the backend. (Pre-Development, Not Final)
- Express
- Node.js
- Possible Technologies: MongoDB, Redis, PostgreSQL, RabbitMQ
 
### Installation

This API is written in Node.js and Express. You can install it by running the following commands:

```bash
git clone <repository link>
cd whisp
npm install
```

### Usage

You can run the API by running the following command:

```bash
npm start
```

### Contributing

We <3 contributors! You can contribute to this project by forking the repository and making a pull request. We will review your pull request and merge it if it is good. Your contribution is very **truly** appreciated!

### License

The project is licensed under the MIT License. You can read the license [here]