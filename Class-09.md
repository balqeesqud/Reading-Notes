# Class 09

## Review: High-level HTTP

   1.  What are the five steps in the HTTP Request Lifecycle?
       - Local Processing
       - Resolve an IP
       - Establish a TCP Connection
       - Send an HTTP Request
       - Tearing Down and Cleaning Up
       
   2.  What are the two things the client needs before it can make an HTTP Request?
       - URL (Uniform Resource Locator).
       - IP Address (Resolved via DNS).
       
   3.  Explain the four way handshake and what it does.
       The four-way handshake is a process that occurs during the termination of a Transmission Control Protocol 
       (TCP) connection. It's used to ensure a graceful and orderly closure of the connection between a client and 
       a server. The purpose of the four-way handshake is to confirm to both parties that they are ready to terminate 
       the connection and to make sure that all pending data has been received and acknowledged.
 
   **handshake works**
      1. Client Sends FIN (Finish) Packet.
      2. Server Responds with ACK (Acknowledgment) Packet.
      3. Server Sends FIN Packet.
      4. Client Responds with ACK Packet.


## Java HTTP Request example 

   1. True or False: When making an HTTP request, you MUST follow any redirect returned by the request. 
      Back up your answer.
      True. When making an HTTP request, you should follow any redirect returned by the request. Redirects 
      are responses from the server that instruct the client to go to a different URL to fulfill the request. 
     
   2. Which built-in Java class can be used to perform an HTTP request?
      `HttpURLConnection` class

   3. What HTTP status codes represent a successful response? A redirect? A client error?
      - Successful Response (2xx): (200)OK
      - Redirection (3xx): 
        1. 301 Moved Permanently.
        2. 302 Found (or 303 See Other).
        3. 304 Not Modified.
        4. 307 Temporary Redirect.

      - Client Error (4xx):
        1. 400 Bad Request.
        2. 403 Forbidden.
        3. 404 Not Found.
        4. 405 Method Not Allowed. 
        5. 406 Not Acceptable.


