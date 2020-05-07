# Task #6 - Docker

Coding → Deploy → Code-review

## Coding

### Preparations

1. Install Python programming language **v3.8.2**: [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. Install Docker: [https://docs.python.org/3/installing/index.html#basic-usage](https://www.docker.com/products/docker-desktop)
3. Install Docker-compose: [https://docs.docker.com/compose/install/](https://docs.docker.com/compose/install/)

### What you already have after task #5

1. Flask web application, which can authenticate user with password:
    - Listen on `localhost:5000`
    - Render authentication form on `http://localhost:5000/`
    - Return static images and files on `http://localhost:5000/static/<image_name>`
    - Has secret page for authenticated users on `http://localhost:5000/cabinet`
2. Valid usernames and passwords are stored in MongoDB database
3. Image upload function in cabinet `http://localhost:5000/cabinet/`
4. Images are being saved to `upload` folder

### Basic part

1. Create `docker-compose.yml` and `Dockerfile` to run your application in Docker
2. Move your sources to `src` directory. Don't forget to create `requirements.txt` file
3. In `docker-compose.yml` there are gonna be two containers named: `mongodb`, `flask-simple`

### Optimal part

1. Add persistent volume for MongoDB
2. Mount `upload` directory to `upload` directory inside `flask-simple` container

### Challenging part

1. Add Nginx which will proxy requests to flask application
2. Add Redis cache for uploaded images

## Deploy

1. Register on GitHub: [https://github.com/](https://github.com/)
2. Join our organization: [https://github.com/itmo-wad/](https://github.com/itmo-wad/)
3. You can create new personal repository or use repository for the previous tasks (but don't remove old files, just append new directories)
4. Commit and push your sources to GitHub. And don't forget to describe shortly what have you done in `README.md` file. Use Markdown format: [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)

## Code-review

1. Communicate in Telegram chat
2. Help others to complete the assignment