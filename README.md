# Firebase Playground

A serverless firebase playground application with the following   

## Getting started

Firebase CLI is a toolset for managing Firebase projects. Before setting up the Firebase CLI, make sure you have [configured a Firebase project](https://firebase.google.com/docs/guides/).


### Setup firebase tools

```shell
$ npm install -g firebase-tools
```

### Create a project 

Please visit https://console.firebase.google.com to create a new project.

Check that your project has been successfully created:

```shell
$ firebase list
```

### Log the CLI into Firebase 

```shell
$ firebase login
```

### Initialize a Firebase project

```shell
$ firebase init
```

* Select the desired firebase services, such as Firestore, Functions, Hosting, Storage...
* Select an existing Firebase project or create a new one
* Select the appropriate configurations (default options are provided)

### Deploy Firebase application

```shell
$ firebase deploy
```

### Serve and test your Firebase project locally

```shell
$ firebase serve --only hosting
```
