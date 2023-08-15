Part 1: In your own terms, define the following terms:

1. What is HTTP?
It's a protocol that stands for 'Hypertext Transfer Protocol.' It prompts the browser to let it know that you're communicating with it.

2. What is a URL?
It stands for uniform resource locator. It contains data about the request you want to make. It will always contain a protocol, hostname, port, resource,
and query string.

3. What is DNS?
It is the domain name server. It translates hostname to IP address.

4. What is a query string?
It is extra information you would like to put in the request, such as search terms, info from forms, etc.

5. What are two HTTP verbs and how are they different?
GET => Can be done multiple times (repeated). It doesn't change server data. Data is sent in a query string.

POST => Never meant to be repeated. It changes server data. Data is sent in a body of the request.

6. What is an HTTP request?
It includes the url that you want and HTTP methods (GET and POST).

7. What is an HTTP response?
It fetches information that you want. Status codes are in the response.

8. What is an HTTP header? Give a couple examples of request and response headers you have seen.
Metadata where it's always included. Similar to metagaming => not thinking about data itself but what's in it.

Headers => date, language, cookies, hostname

9. What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
    - DNS turns url to IP address
    - Recognizes HTTP protocol => http
    - Connects to port 80 since it's http
    - Requests resource => /some/page.html


