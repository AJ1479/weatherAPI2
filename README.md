# weatherAPI2

Extension of weatherAPI with an EJS dashboard to display weather information about a city, written in Node.js.



## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`API_KEY`

## Deployment

To deploy this project, first install packages using 

```bash
  npm i
```

Then start the server with 

```bash
  npm start
```

## API Reference

#### Login

```
  GET /
```

Returns the dashboard

```
  POST /
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `city` | `string` | city to get weather information |
