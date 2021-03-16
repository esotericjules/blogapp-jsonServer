### SetUp
1. created a project directory
2. initialized package.json using `npm init` .
3. installed jsonServer and ngrok
4. Created scripts inside package.json `"db": "json-server -w db.json -p 3005",
    "tunnel": "ngrok http 3005"1`
5. Created a db.json. 
6. use `npm run db` and `npm run tunnel` to start up server and ngrok connection.
7. Use the json server CRUD methods to create, edit, delete blogposts in the blog app.



