# HTTP response status codes

## Successful responses
* 200 OK
    * The request has succeeded. The meaning a success varies depending on the HTTP method:
    GET: The resource has been fetched and is transmitted in the message body.
    HEAD: The entity headers are in the message body.
    POST: The resource describing the result of the action is transmitted in the message body.
    TRACE: The message body contains the request message as received by the server
## Rediraction messages
* 302 Found
    * This response code means that URI of requested has been changed temporarily. New changes in the URI might be made
    in the future. Therefore, this same URI should be used by the client in future request.
* 304 Not Modified
    * This is used for cachingpurposes. It is telling to client that response has not been modified. So client
    can continue to use same cached version of response.

## Client error response
* 403 Forbidden
    * Client does not have access rights to the content so server is rejecting to give proper response.
* 404 Not found
    * Server can not find requested resource. This response code probable is most famous one due to its frequency to occur in web.

## Server error responses
* 502 Bad Gateway
    * This error response means that the server, while workingas a gateway to get a response needed to handle the
    request, got an invalid response.