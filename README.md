Status Code:

200 OK: The request has been successfully processed and the server is returning the requested resource.

201 Created: The request has been fulfilled and a new resource has been created as a result.

204 No Content: The request was successful, but there is no response body (typically used for operations that don't return data, like a successful deletion)

301 Moved Permanently: The requested resource has been permanently moved to a different URL

302 Found: The HTTP status code 302 indicates that the requested resource has been temporarily moved to a different URL.When a server sends a response with a 302 status code, it typically includes a Location

header find that specifies the new temporary URL where the client should redirect to.

304 Not Modified:The client version of the requested resource is still valid, so the server sends this status code to indicate that the client can use its cached copy.

400 Bad Request: The server cannot understand or process the client's request dur to invalid syntax or other client-side issues.

401 Unauthorized: The client needs to provide authentication credentials to access the requested resource.

403 Forbidden: The clident is authenticated, but it does not have permission to access the requested resource.

500 Internal Server Error: A generic error message indicating that something went wrong on the server and the server could not handle the request.

502 Bad Gateway: The server acting as a gateway or proxy received an invalid response from an upstream server.

503 Service Unavailable:The server is currently unable to handle the request due to temporary overloading or maintenance.


Main are--->
404 NOT FOUND
502 BAD GATEWAY
401 UNAUTHORIZED
200 SUCCESSFUL
403 FORBIDDEN
400 BAD REQUEST

The responseEntity class is part of the Spring Framework and is commonly used in Spring Boot application to customize the HTTP response.

It provides methods for setting the response status,header and body.You can use it to return different types of data in your controller methods such as JSON,XML or HTML

You can use generic with ResponseEntity to specify the type of data you are returning
