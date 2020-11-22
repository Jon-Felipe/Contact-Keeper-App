# Contact Keeper

> Full stack MERN contact manager with React hooks, context & JWT authentication.

This project was completed by following along a Udemy course conducted by Brad Traversy.

Checkout his [Github](https://github.com/bradtraversy) and the project Udemy course [React Front To Back](https://www.udemy.com/course/modern-react-front-to-back/)

This is the full app. The API can be found [here](https://github.com/bradtraversy/contact_keeper_api) with documented endpoints

## Usage

Install dependencies

```bash
npm install
npm client-install
```

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
```

### Run Server

```bash
npm run dev     # Express & React :3000 & :5000
npm run server  # Express API Only :5000
npm run client  # React Client Only :3000
```
