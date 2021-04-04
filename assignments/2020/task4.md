# Task #4 - Database

Reading → Coding → Deploy → Code-review

## Reading

1. MongoDB get started: [https://docs.mongodb.com/manual/tutorial/getting-started/](https://docs.mongodb.com/manual/tutorial/getting-started/)
2. Pymongo: [https://api.mongodb.com/python/current/tutorial.html](https://api.mongodb.com/python/current/tutorial.html)
3. Flask pymongo: [https://flask-pymongo.readthedocs.io/en/latest/](https://flask-pymongo.readthedocs.io/en/latest/)

## Coding

### Preparations

1. Install Python programming language **v3.8.2**: [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. Install Flask framework with **pip**: [https://docs.python.org/3/installing/index.html#basic-usage](https://docs.python.org/3/installing/index.html#basic-usage)
3. Install PyMongo and Flask PyMongo with **pip**
4. Install MongoDB: [https://docs.mongodb.com/manual/installation/](https://docs.mongodb.com/manual/installation/)

### Basic part

1. Create web application, which can authenticate user with password:
    - Listen on `localhost:5000`
    - Render authentication form on `http://localhost:5000/`
    - Return static images and files on `http://localhost:5000/static/<image_name>`
    - Has secret page for authenticated users on `http://localhost:5000/cabinet`
2. Valid usernames and passwords should be stored in MongoDB database
3. You are allowed to use any JS or CSS frameworks
4. You are allowed to use only Python programming language and Flask framework
5. You are allowed to use only MongoDB as database

### Optimal part

1. Add registration function to append new users on `http://localhost:5000/register/`
2. You can keep usernames/passwords only in MongoDB

### Challenging part

*(Part for those, who already knows all that stuff)*

1. Implement `password change` feature
2. Fill database with 1 thousand, 1 million, 10 million, ... users with the help of Faker library
3. Add **index** to username and measure how response time is changed depending on the number of users. Results of the research append to the [README.md](http://readme.md) file
4. You can draw a graph

## Deploy

1. Register on GitHub: [https://github.com/](https://github.com/)
2. Join our organization: [https://github.com/itmo-wad/](https://github.com/itmo-wad/)
3. You can create new personal repository or use repository for the previous tasks (but don't remove old files, just append new directories)
4. Commit and push your sources to GitHub. And don't forget to describe shortly what have you done in `README.md` file. Use Markdown format: [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)
5. Also save data from MongoDB as dump or as simple JSON file in the repository

## Code-review

1. Communicate in Telegram chat
2. Help others to complete the assignment
