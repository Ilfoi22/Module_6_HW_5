# Module_6_HW_5

**UML Diagram 

<img src="D:\Projects\Module_6_HW_5\UML oAuth 2.0.png"/>

1. User login in Client;
2. Client redirect to Authorization Server;
3. Authorization Server redirects User to login and authorization prompt;
4. User authenticates using one of the configured login options, and may see a consent prompt listing the permissions Authorization Server will give to the application;
5. Authorization Server redirects User back to Client with single-use authorization code;
6. Auth0's SDK sends authorization code, application's client ID, and application's credentials, such as client secret or Private Key JWT, to Authorization Server;
7. Authorization Server verifies authorization code, application's client ID, and application's credentials;
8. Authorization Server responds with an ID token and access token (and optionally, a refresh token);
9. Client can use the access token to call an Resource Server to access information about the User;
10. Resource Server responds with requested data.