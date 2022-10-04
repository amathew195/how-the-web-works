What is HTTP? This is the protocol, which is basically the language that is being used between browsers and servers.

What is a URL? The URL is the entire link - protocol, hostname, port, resource, query string.

What is DNS? the address book that contains the IP addresses for each hostname.

What is a query string? this is the extra information that we are passing with the request to the server. this could vary based on
if it's a GET or POST request.

What are two HTTP verbs and how are they different?
GET: make a request to get information. This has no side effects. GET requests will post to the query string as well.
POST: make a request to add information to the server. This has side effects.

What is an HTTP request? It's made by the browser to the server. The browser is attempting to get information from
the server. This could be get or post.

What is an HTTP response? It's made by the server to the browser in response to the browser's request. It includes headers,
a the string version of the data the browser requested.

What is an HTTP header? Give a couple examples of request and response headers you have seen. Headers include information when the
browser and server introduce themselves. Examples include - date, OS, Server version, Context-type,

What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
    1. Get the IP address of the hostname from DNS
    2. Make a connection to the IP address
    3. Direct the request to the appropriate port
    4. Use the appropriate protocol to make request
    5. Provide the resource information that browser is requesting
    6. Pass along any additional queries
    7. If no issues surface, browser receives response from server

