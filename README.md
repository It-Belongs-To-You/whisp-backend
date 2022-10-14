[here]: ./LICENSE
[architecture]: ./docs/architecture.md

## Whisp Node

Whisp Node is a simple express app for storing all the client's public key's in a list. The server is also responsible for storing encrypted message's until they can be transferred to the client. It is designed to be used as a backend for client, a simple open source cryptographically secure client for sending and receiving messages.

The project borrow's concept's from **Bitcoin's blockchain**, to secure messages. Such as BIP39 and Encryption Mechanisms.

### Architecture

The architecture is still being decided and once it's done the [Architecture][architecture] document would be updated. I'm still actively
working on building a design which is immuateable and also secure. Contributions/Ideas/Suggestions are truly welcome.

The current architecture is a simple websocket server which is used to send and receive encrypted messages. The server is also responsible for storing the public keys of the clients, storing the encrypted messages until they can be transferred to the client's public key.

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