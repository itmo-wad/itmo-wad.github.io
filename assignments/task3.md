# Task #3 - Authentication

Reading → Coding → Deploy → Code-review

## Reading

1. Flask Sessions: [https://flask.palletsprojects.com/en/1.1.x/quickstart/#sessions](https://flask.palletsprojects.com/en/1.1.x/quickstart/#sessions)
2. Flask cookies: [https://flask.palletsprojects.com/en/1.1.x/quickstart/#cookies](https://flask.palletsprojects.com/en/1.1.x/quickstart/#cookies)
3. Flask login: [https://flask-login.readthedocs.io/en/latest/](https://flask-login.readthedocs.io/en/latest/)

## Coding

### Preparations

1. Install Python programming language **v3.8.2**: [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. Install Flask framework with **pip**: [https://docs.python.org/3/installing/index.html#basic-usage](https://docs.python.org/3/installing/index.html#basic-usage)

### Basic part

1. Create web application, which can authenticate user with password:
    - Listen on `localhost:5000`
    - Render authentication form on `http://localhost:5000/`
    - Return static images and files on `http://localhost:5000/static/<image_name>`
    - Has secret page for authenticated users on `http://localhost:5000/cabinet`
2. You are allowed to use any JS or CSS frameworks
3. You are allowed to use only Python programming language and Flask framework
4. You can hardcode pre-defined usernames and passwords inside your application

### Optimal part

1. Add registration function to append new users on `http://localhost:5000/register/`
2. Allow users logout `http://localhost:5000/logout`
3. You can keep usernames/passwords in global storage

### Challenging part

*(Part for those, who already knows all that stuff)*

1. Implement session storage based on files in `sessions` directory
2. Files should be encoded in **JSON** format
3. Session cookies should be signed with **HMAC** or any other digest method

## Deploy

1. Register on GitHub: [https://github.com/](https://github.com/)
2. Join our organization: [https://github.com/itmo-wad/](https://github.com/itmo-wad/)
3. You can create new personal repository or use repository for the previous tasks (but don't remove old files, just append new directories)
4. Commit and push your sources to GitHub. And don't forget to describe shortly what have you done in `README.md` file. Use Markdown format: [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)
5. *(optional)* Deploy you sources on Heroku or somewhere else and add link to the server to `README.md`

## Code-review

1. Communicate in Telegram chat
2. Help others to complete the assignment