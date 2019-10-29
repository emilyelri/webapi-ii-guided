# Routing Notes

[ client ] == makes a request to an == [ api ] == sends a response back to the client

what is the interface for a web api? ==> 
- URI (Uniform Resource Identifier),
- URL (Universal Resource Locator),
- Endpoint,
- HTTP === network protocol, a set rules for communication

REST(ish)

- everything is a 'Resource'
- single URI per resource. ex: 'http://web23.com/channels', 'http://web23.com/users'
- use HTTP METHODS to perform operations on resources.
- hypermedia(at this level we are fully REST)

|Non REST|REST|
|:--|:--|
|/listAllChannels|GET /channels|
|/createChannel| POST/channels|
|/updateChannel|PUT /channels|
|/delete Channel|DELETE /channels|
|/channel?id=123|GET /channels/123|