## Exercise 1

PHP 8.3.33 (cli) (built: Jul 28 2026 18:10:28) (ZTS Visual C++ 2019 x64)
Copyright (c) The PHP Group
Zend Engine v4.3.33, Copyright (c) Zend Technologies

Composer version 2.10.3 2026-08-27 13:34:23
PHP version 8.3.33 (C:\xampp\php\php.exe)


## Exercise 5

When a user visits a webpage, their browser sends an HTTP request over the internet to a server. The server processes the request and sends back an HTTP response containing the website’s data and a status code, such as 200 OK or 404 Not Found, to show whether the request was successful. Since HTTP is stateless, the server doesn’t remember the client once the interaction ends, so each visit is treated as a completely new connection.

## Exercise 6

Since web connections are stateless, websites usually use sessions and cookies to keep track of whether a user is logged in. When a user logs in with their credentials, the server creates a unique session ID and sends it to the browser, which stores it as a small text file called a cookie. Whenever the user opens another page, the browser automatically sends the cookie along with the request, allowing the server to find their session, recognize them, and keep them securely logged in.
