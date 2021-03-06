# Homework #2

Reading → Coding → Deploy → Code-review

## Reading

1. Python Flask big tutorial

     1.1 [https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
     
     1.2. [https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-ii-templates](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-ii-templates)
2. HTML forms: [https://www.w3schools.com/html/html_forms.asp](https://www.w3schools.com/html/html_forms.asp)
3. Markdown: [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)

## Coding

### Preparations

1. Install Python programming language **v3.8.2**: [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. Install Flask framework with **pip**: [https://docs.python.org/3/installing/index.html#basic-usage](https://docs.python.org/3/installing/index.html#basic-usage)

### Basic part

1. Create web application, which can host your image gallery:

    1.1. Listen on `localhost:5000`
    
    1.2. Render HTML document on `http://localhost:5000/`
    
    1.3. Show static images on `http://localhost:5000/img/<image_name>`
    
    1.4. Your external CSS and JS files should be returned on `http://localhost:5000/static/<js/css filename>`
    
2. You are allowed to use any JS or CSS frameworks
3. You are allowed to use only Python programming language and Flask framework

### Optimal part

1. Create web application, which emulates a chat with a human:

    1.1. Web page with messages log
    
    1.2. Input for writing new message
    
    1.3. Button for sending message to the server
    
    1.4. Sample HTML form:
```
        <form method="POST" action="<http://localhost:5000/>">
            <textarea name="messages">{{ messages }}</textarea>
            <input type="text" name="new_message">
            <input type="submit">
        </form>
```        

2. After the button click message should be sent to the server with `HTTP POST` to `http://localhost:5000/`:

     2.1. It is okay to send also all messages if you don't know how to keep them on the server.

     2.2. It is also okay to keep them in the global variable
3. Robot should answer on a message according to the predefined set of rules

     3.1. Rules can be hardcoded as bases on the occurencies of different words

     3.2. There should be at least 10 rules describing typical conversation topics:
        
        3.2.1. current weather
        
        3.2.2. hello/greetings
        
        3.2.3. ...

### Challenging part

*(Part for those, who already knows all that stuff)*

1. Dialog should be kept on the server (global variable or text file)
2. Robot should add new messages independently from user (every second new message)

    2.1. It can be done with another python script
    
    2.2. Or it can be done with separate Thread
3. Message updates should be delivered to the user's page with the help of three methods (you can create three endpoints for this)

    3.1. polling new messages every 1 second
    
    3.2. long polling new messages
    
    3.3. (optionally) through websockets

## Deploy

1. Register on GitHub: [https://github.com/](https://github.com/)
2. Join our organization: [https://github.com/itmo-wad/](https://github.com/itmo-wad/)
3. Create a **new** personal repository for the second homework
4. Commit and push your sources to GitHub. And don't forget to describe shortly what have you done in `README.md` file. Use Markdown format: [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)
5. *(optional)* Deploy you sources on Heroku or somewhere else and add link to the server to `README.md`

## Code-review

1. Communicate in Telegram chat
2. Help others to complete the assignment
