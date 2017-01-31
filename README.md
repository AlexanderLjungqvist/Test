# Vulnerability search engine 

An automated vulnerability search engine compatible for changes and adaption to any project.

## Getting Started

In order to have this project up and running, just clone the repository to get the code. Then a few lines of installing dependencies will be prompted, in order to run the project.

### Prerequisites

To run the project the following **commands** are a necessity:

```
npm install unfluff --save
```

## The Project

## Integrating your own sources

Altering the sources for the project is made as simple as possible to have the user create his own version of the engine.
There are **three possible** ways, either beneath the class CVE, Newspapers or Forums in the file "index.html". Then just add your source as the snippet instructs you to do. The code is located at around row 50.
```
<input  type="checkbox" value="Your source" ng-model="sources['Your source']">   Name of your source

```
However, this project uses Unfluff as a package hence the problems for Unfluff are inherited to this project. See more [here](https://github.com/ageitgey/node-unfluff#what-is-broken).

**If** you want to add your own API and not sure how to do, don't hesitate to email us at har12gry@student.lu.se, and guidance will be provided.


## Deployment

In order to deploy the project, which is completely fine with the creators, basically all that needs to be done is the upload to your own web server. Have you not done this before? then we **recommend** the tutorial DigitalOcean has provided for uploading a NodeJS application. Please see [here](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-node-js-application-for-production-on-ubuntu-16-04)

## Built With

* [Unfluff](http://www.dropwizard.io/1.0.2/docs/) - An automatic web page content extractor for Node.js!
* [Bootstrap](http://getbootstrap.com/) - Bootstrap design
* [ExpressJS](https://maven.apache.org/) - Server Framework
* [MySQL-node](https://www.npmjs.com/package/mysql) - Database 
* [AngularJS](https://angularjs.org/) -  Front end 
* [NodeJS](https://nodejs.org/en/) - The core of the project.


## Authors

* **Gustav Ryrlén ** - *Project development* - [Gustav](https://github.com/PurpleBooth)
* **Jacob Hegelund ** - *Project development* - [Jacob](https://github.com/PurpleBooth)
* **Alexander Ljungqvist ** - *Project development* - [Alexander](https://github.com/PurpleBooth)

## License

Free for all.

## Acknowledgments

* Extra acknowledgments to unfluff for creating a smooth engine.
* Google for providing an API.
* Twitter for providing an API.

