This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

This projecft is based on the tutorial series:
https://medium.com/@_rchaves_/building-microfrontends-part-i-creating-small-apps-710d709b48b7

## Available Scripts

In the project directory, you can run:

### To run the app with webpack dev server
Run the following command:
`npm start`

### To run the app using Express
Build the application with:
`npm run build`

Transpile the frontend code with:
`npm run transpile`

Start the Express server with:
`npm run start:prod`

## To run in a docker container
First build the docker image by:
`docker build . -t micro-demo-header`

Then run a docker container using this image
`docker run -t -i -p 8080:8080 micro-demo-header`