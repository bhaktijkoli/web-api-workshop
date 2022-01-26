# Web API(Application Programming Interface)
A way 2 software communicate with each other over a network.

## Protocols
- ### Network Layer / Thrid Layer
    - IP (Internet Protocol)

- ### Transport Layer
    - TCP (Transmission Dontrol Protocol)
    - UDP (User Datagram protocol)

- ## Application Layer
    - HTTP (Hypertext transfer protocol) 80
    - HTTPS (Hypertext transfer protocol secure) 443
    - WS (Websocket) 80
    - WSS (Websocket secure) 443
    - FTP (File Transfer Protocol) 21
    - DNS (Domain Name System) 53

## Port
Endpoint to communicate with a software.

## DNS(Domain Name System)
Resolves a name to IP address

## URL (Uniform Resource Locater)
https://wwww.nodejs.org:443/en/docs?search=api
- https -> Scheme/Protocol
- wwww.nodejs.org -> Domain
    - org -> Top Level Domain (TLD)
    - nodejs -> Main Domain
    - wwww -> Sub Domain
- 443 -> Port
- /en/docs -> Path
    - en -> Folder
    - docs -> Folder
- search=api => URL Parameters / Query

## Data Formats / Content-Type
- Text => text/plain
- HTML(Hypertext Markup Language) => text/html
- XML (Extensible Markup Langauge) => application/xml
    ```
        <xml>
            <user>
                <name>Bhaktij Koli</name>
                <email>hello@bhaktijkoli.com</email>
            </user>
        </xml>
    ```
- JSON(JavaScript Object Notation) => application/json
    ```
    {
        "name" "Bhaktij Koli",
        "email: "hello@bhaktijkoli.com"
    }
    ```
- Multimedia (File, Image, etc)


## API Architectures
- ### SOAP (Simple Object Access Protocol)
    - Limited to XML
    - Strict
- ### REST API(Representational state transfer)
    - XLL, JSON, text, html, images, videos, files
- ### Websockets
    - Event Driven (Eg: socket.io)
    - Pub/Sub (Eg: IOT) 
- ### RPC(Remote Procedure Call)
    - GRPC(Google Remote Procedure Call)
- ### GraphQL
    - Apollo
    - Helix
    - Yoga
    - AWS Amplify

## RESUT API/RESTFul API
- ### HTTP Request
    - URL
    - Method
    - Headers
    - Body
- ### HTTP Response
    - Status Code
    - Headers
    - Body

### HTTP Methods
- GET (Fetch Data)(No Request Body)
- POST (Create Data)
- PUT (Update Data by replacing it)
- DELETE (Delete Data)
- PATCH (Update/Repair Data without replacing it)
----
- HEAD (Fetch Headers)(No Response Body)
- CONNECT (Eastablish Connection)(No Request Body)
- OPTIONS (To check for available options)(No Request Body)
- TRACE (Trace)

### HTTP Headers
To add additional info or to describe to the request
- Accept
- Authorization
- Content-Type
- Cookie
- Origin
- Custom Headers (start with X)
- X-Powered-By

### HTTP Status Codes
- Sucessful Response
    - 200 (OK)
- Redirect Response
    - 301
- Client Error Response
    - 400 (Bad Request)
    - 401 (Not Authenticated)
    - 403 (Forbiden)
    - 404 (Not Found)
    - 405 (Not Authorized)
- Server Error Response
    - 500 (Internal Server Error)

[Learn More](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)

## Cookie
    - Maintain client side
## Session
    - Maitain server side

## CORS (Cross Origin Resource Sharing)
Access-Control-Allow-Origin: '*'
Access-Control-Allow-Methods: 'GET,POST',
Access-Control-Allow-Headers:
