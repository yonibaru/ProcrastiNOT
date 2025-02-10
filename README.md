## TO RUN THE SERVER:
1. create a new file called 'config.ts' inside the 'server' directory
2. Paste the following code:
```
export const MONGO_URI = "<YOUR_MONGODB_URL>";
export const JWT_SECRET = process.env.JWT_SECRET || "defaultsecret";
export const SERVER_PORT = 3000;
```
Replace ```<YOUR_MONGODB_URL>``` with your mongodb url.

## RUNNING THE SERVER

```npx ts-node server.ts```

