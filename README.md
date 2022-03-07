# Typin Tech

## Description

This is a tech blog that allows users to log in, create a  post, leave comments and view posts from other users. As a logged in user you can also edit a post or delete a post. Additionally, the website knows if you are logged in by way of express sessions, and a logout button will appear in the nav when a user is logged in. After an hour, a user is automatically logged out as their session will expire.

## Table of Contents

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Tests](#tests)
- [License](#license)

## Installation

To run this project locally do the following:
- Clone the Repo
- run `npm install`
- Build the DB using mysql. 
    - Run `mysql -u root -p`
    - Run `source db/schema.sql`
- Exit Mysql, run seeds (optional)
    - Run `npm run seeds`

## Usage

The site is located on heroku at this URL: https://mysterious-river-71927.herokuapp.com/

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:


![Login](/public/assets/img/typin-tech-1.png)

![Homepage](/public/assets/img/typin-tech-2.png)


## Credits

- [bcrypt](https://www.npmjs.com/package/bcrypt)
- [connect-session-sequelize](https://www.npmjs.com/package/connect-session-sequelize)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [express](https://expressjs.com/)
- [handlebars](https://handlebarsjs.com/)
- [jest](https://jestjs.io/)
- [mysql2](https://www.mysql.com/)
- [sequelize](https://sequelize.org/)

## Tests

You can run Jest tests on the handlebars helpers by running the following:

`npm run test`

## License

MIT License

Copyright (c) [2022] [Emily Dokken]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
