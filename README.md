# appbase-oauth2

A secure realtime blogging app using appbase.io and an ACL based security middleware. Uses socket.io for server-client presence and subscription counts and OAUTH2 for client authentication

## Instructions to run

```
git clone https://github.com/azizulhakim/appbase-oauth2
```

Update the ```config/credentials.js``` file with your facebook, twitter, appbase and mongodb credentials and follow next instructions


```
npm install
bower install
node data_init.js
node index.js
```

Server will start running at [http://localhost:3000/](http://localhost:3000/)
