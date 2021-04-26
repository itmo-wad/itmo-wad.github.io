# Homework #5

Coding → Deploy → Code-review

## Coding

### Preparations

1. Install Python programming language **v3.8.2**: [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. Install Flask framework with **pip**: [https://docs.python.org/3/installing/index.html#basic-usage](https://docs.python.org/3/installing/index.html#basic-usage)
3. Install PyMongo and Flask PyMongo with **pip**
4. Install MongoDB: [https://docs.mongodb.com/manual/installation/](https://docs.mongodb.com/manual/installation/)

### What you already have after task #4

1. Flask web application, which can authenticate user with password:
    1.1. Listen on `localhost:5000`
    
    1.2. Render authentication form on `http://localhost:5000/`
    
    1.3. Return static images and files on `http://localhost:5000/static/<image_name>`
    
    1.4. Has secret page for authenticated users on `http://localhost:5000/cabinet`
    
2. Valid usernames and passwords are stored in MongoDB database

### Basic part

1. Add image upload function in cabinet  `http://localhost:5000/cabinet/`
2. Image should be saved to `upload` folder

### Optimal part

1. Add file extension checks
2. Add function that returns uploaded image `http://localhost:5000/upload/<image_name>.png`
3. Show user's avatar in `cabinet` (you can store link to the file in cookie or database)

### Challenging part

1. Store the whole file in MongoDB

## Deploy

1. Register on GitHub: [https://github.com/](https://github.com/)
2. Join our organization: [https://github.com/itmo-wad/](https://github.com/itmo-wad/)
3. You can create new personal repository or use repository for the previous tasks (but don't remove old files, just append new directories)
4. Commit and push your sources to GitHub. And don't forget to describe shortly what have you done in `README.md` file. Use Markdown format: [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)

## Code-review

1. Communicate in Telegram chat
2. Help others to complete the assignment