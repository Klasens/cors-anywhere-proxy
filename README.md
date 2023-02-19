# CORS Anywhere

This is a Node.js reverse proxy that adds CORS headers to the proxied request. This allows web applications to bypass the same-origin policy and access resources from remote servers.

###Features
- Simple and lightweight
- No external dependencies
- Configurable CORS headers
- Supports HTTPS
- Easily deployable to Heroku or any other platform
- How It Works
- When a request is made to the proxy server, it adds the specified CORS headers to the request and sends it to the remote server. The response from the remote server is then modified to include the CORS headers, and sent back to the client.

###Usage
To use this proxy in your web application, simply prepend the URL of the remote server with the URL of the proxy server. For example:

https://your-proxy-server.com/https://remote-server.com/api/data

This will send a request to the remote server, with the specified CORS headers added by the proxy server.
