# AYCHDate
AYCHDate is platform for professionals of all kinds. Joining AYCHDate network, professionals can share ideas, seek help and also deliver solutions to other professionals in a stramlined way.

## Table of Contents

1. <a href="#site">Link to Site</a>
2. <a href="#tech-used">Tech Used</a>
3. <a href="#features">Main Features</a>
4. <a href="#how-to-use">How To Use</a>
5. <a href="#api-endpoints">API endpoints</a>
6. <a href="#author">Author</a>
7. <a href="#license">License</a>

## Link to Site

https://aychdate.github.io/

## Tech Used

- [Nodejs](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [MongoDB](https://mongoosejs.com/)
- [Bootstrap](https://getbootstrap.com/)
- [React](https://reactjs.org/)

## Main Features

* Display Professionals Profiles
* Register a user
* Create a user profile
* Add education and professional qualifications
* Add professional experiences
* Create and delete posts
* View Posts Feed
* Comment and Like Posts


## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Nodejs](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/aychdate/aychdate.github.io/)
# Install dependencies
$ npm install

# Run the app
$ npm run dev
```
## API endpoints
```
POST Request -> localhost:3000/api/users/register
POST Request -> localhost:3000/api/users/login
POST Request -> localhost:3000/api/profile
GET Request -> localhost:3000/api/profile/all
GET Request -> localhost:3000/api/profile/handle
GET Request -> localhost:3000/api/posts
```

## Author
AYCHDeveloper.

## License
The AGPL-3.0+.

