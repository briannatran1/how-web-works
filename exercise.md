Part 1: In your own terms, define the following terms:

1. What is HTTP?
It's a protocol that stands for 'Hypertext Transfer Protocol.' It prompts the browser to let it know that you're communicating with it.

2. What is a URL?
It stands for uniform resource locator. It contains data about the request you want to make. It will always contain a protocol, hostname, port, resource,
and query string.

3. What is DNS?
It is the domain name server. It translates URLs to IP address.

4. What is a query string?
It is extra information you would like to put in the request, such as search terms, info from forms, etc. Allows you to pass key-value pairs into the URL to receive extra data.

5. What are two HTTP verbs and how are they different?
GET => Can be done multiple times (repeated). It doesn't change server data. Data is sent in a query string. Get some data from the server.

POST => Never meant to be repeated. It changes server data. Data is sent in a body of the request. Send some data to the server.

6. What is an HTTP request?
It includes the url that you want and HTTP methods (GET and POST).

An HTTP request is a request from a client to a server which follows the HTTP protocol (eg a request for HTML from news.google.com)

7. What is an HTTP response?
A response from a server to a client which follows the HTTP protocol. Status codes are in the response.

8. What is an HTTP header? Give a couple examples of request and response headers you have seen.
Metadata where it's always included. Similar to metagaming => not thinking about data itself but what's in it.

Headers provide additional information about the request or the response.

Request Headers => host, user-agent, accept, cookie, cache-control
Response Headers => content-type, last-modified, set-cookie, cache-control

9. What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
    - DNS turns URL to IP address
    - Browser makes a request to that IP address, including headers
    - Server sends a response (with a status code)
    - Browser makes a DOM from that HTML, and finds any other resources
    - Browser makes separate HTTP requests for those resources and receives response  from server for each.


