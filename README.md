# jwt-with-token-handling
i seperate as two server, first for read data, second for authentication.

to test this example:
1. first run both server.
2. login
3. copy the accessToken to GET /posts
4. copy the refreshToken to POST /token and POST /logout
5. try GET /posts (token will be expired)
6. get new Token by using POST /token
7. logout

thanks
