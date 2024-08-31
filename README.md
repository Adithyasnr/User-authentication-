# User-authentication-
This project is about creating a landing login page for user authentication. I've used Flask frame work and JWT token based server authentication by inculcating neat and efficient code completely using Python   


A)Flask App with JWT Authentication: A basic Flask application demonstrating JWT-based authentication.


B)Routes:
i)/: Home route, checks user session status.
ii)/public: Publicly accessible route.
ii)/auth: Protected route, requires a valid JWT token.
iv)/login: Login route, validates user credentials and generates a JWT token.



C)
JWT Handling: Uses a secret key to encode and decode tokens, protecting specific routes with a token_required decorator.
Session Management: Utilizes Flask's session for tracking login state
