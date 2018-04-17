# Create React Express App
This is what it should look like 

### This image is in issues
 ![image](https://user-images.githubusercontent.com/25730453/38841582-1c513d44-41b3-11e8-8c70-682091ea4341.png)

I hope you are able to follow this easily.  I am purposely putting more time into the read me pages 

This setup allows for a Node/Express/React app which can be easily deployed to Heroku.

The front-end React app will auto-reload as it's updated via webpack dev server, and the backend Express app will auto-reload independently with nodemon.

## Starting the app locally

Start by installing front and backend dependencies. While in this directory, run the following commands:

```
yarn install
cd client
yarn install
cd ..
``

After both installations complete, run the following command in your terminal:

```
yarn start
```

 This app should be running on <http://localhost:3000>. The Express server should intercept any AJAX requests from the client.

## Deployment (Heroku)



1. Build the React app for production by running the following command:

```
yarn build
```

2. Add and commit all changes to git

3. Push to Heroku

Your application should be deployed to Heroku
