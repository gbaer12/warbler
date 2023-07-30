Look over the code in app.py related to authentication.

How is the logged in user being kept track of?

the user is assigned to g.user

What is Flask’s g object?

g is an object for storing data during the application context of a running flask webb app.

What is the purpose of add_user_to_g?

add_user_to_g sets the g object as the logged in user.

What does @app.before_request mean?

the before_request decorator allows us to execute a function before any request.