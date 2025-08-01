## The NodeJS Todo Sample Application using MongoDB

The app is a simple CRUD (Create, read, update, delete) Todo application made with NodeJS and MongoDB.

## How to run?

### Node version

- NodeJS v20.16.0

## Common setup

Copy `.env.sample` to create a `.env` that will be the environment variable for the application. Edit the `.env` file with the correct values.

| Variable Name | Description             | Example       |
|---------------|-------------------------|---------------|
| `DB_URL`      | Database host address   | `127.0.0.1`   |
| `DB_NAME`     | Name of the database    | `test`        |


```bash
cp .env.sample .env
```
Install node dependencies

```bash
npm install
```

To run express server locally, run the following:

```bash
npm run start
```

App should be accessible here: [http://localhost:3000](http://localhost:3000).

## Build the application ready for production

Step 1: Install the npm packages

```bash
npm install
```

Step 2: Build the application by running this command

```bash
npm run build-prod
```

Step 3: Run the output build

```bash
npm run serve
```

> NOTE: Before running the application make sure that you have a MongoDB VM or container running locally to avoid errors.
