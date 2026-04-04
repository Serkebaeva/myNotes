aliases:: xmlHttpRequest, XHR, axios-http, fetch api

- [[xmlHttpRequest]]
	- `XMLHttpRequest` (XHR) objects are used to interact with servers. You can retrieve data from a URL without having to do a full page refresh. This enables a Web page to update just part of a page without disrupting what the user is doing.
	- Despite its name, `XMLHttpRequest` can be used to retrieve any type of data, not just XML.
	- If your communication needs to involve receiving event data or message data from a server, consider using `[[server-sent events]]` through the `[[EventSource]]` interface. For full-duplex communication, `[[WebSockets]]` may be a better choice.
	- Over the years we have improved on XMLHttpRequest and these days we use tools [[axios-http]] or [[Fetch]][[API]] to send messages to the backend.