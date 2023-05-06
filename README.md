## deploy-contact-app

# Mini-Project: 

In this mini-project, you are given a simple application that needs to be updated to use webpack, service workers, and IndexedDB. In addition, it must have PWA functionality in order to work properly. Once you have updated the application with these new features, you will deploy it to Heroku. Heroku is not new to you, but you will need to add a handful of special scripts so that it knows to deploy your bundled application.
The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

To build this contact cards, you will start with an existing application and implement methods for getting and storing data to an IndexedDB database. You will use a package called idb, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

You will deploy this full-stack application to Heroku using the Heroku Deployment Guide on The Full-Stack BlogLinks to an external site

## Screenshots

The following image shows the application's contact card rendered:
![Screenshot 2023-05-05 121701](https://user-images.githubusercontent.com/109435666/236634009-4861e176-d5eb-4017-94e9-a29a91375060.png)

The following image shows the application's registered service worker:
![Screenshot 2023-05-06 113756](https://user-images.githubusercontent.com/109435666/236634016-dea952c6-85c3-44c4-972d-1c62252fb746.png)

The following image shows the application's IndexedDB storage:
![Screenshot 2023-05-06 113847](https://user-images.githubusercontent.com/109435666/236634022-09431ae7-60cf-406f-8ba7-4926bf4a3729.png)

## User Story

Work with your group to resolve the following issues:

* As a user, I want to be able to install the web application as a PWA.

* As a user, I want to be able to add and remove my contact cards.

* As a developer, I want all my scripts to run from the root directory `package.json`.

* As a developer, I want to be able to run `npm run start` in the command line and have both my client and server start.

* As a developer, I want to be able to run `npm run start:prod` in the command line to run our build script and start our server.

* As a developer, I want to be able to run `npm run server` in the command line and have just our server start without the client.

* As a developer, I want to be able to run `npm run build` in the command line and have our client run the webpack build script.

* As a developer, I want to be able to run `npm run install` in the command line and have all of the client's dependencies installed.

* As a developer, I want to be able to run `npm run client` in the command line and have just our client start without the server.

## Acceptance Criteria

The mini-project is complete when the following criteria are met:

* The application uses webpack for bundling.

* The application uses a service worker to cache static assets.

* The application uses IndexedDB GET, ADD, and DELETE methods.

* The application uses object store for async/await.

* The application uses CSS loaders.

* Scripts are placed in the root and client directory's `package.json`.

* `npm run start` starts both the client and server.

* `npm run start:prod` runs the `build` script and starts the server.

* `npm run server` starts just the server and not the client.

* `npm run build` runs the webpack build script in the client.

* `npm run install` installs the dependencies for the client.

* `npm run client` starts the client without the server.

* The web application can be installed from the web address provided by Heroku.

* The web application is deployed using Heroku.

---
