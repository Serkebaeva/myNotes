aliases:: http, https, url, web

- The HTTP **`Host`** [request header](https://developer.mozilla.org/en-US/docs/Glossary/Request_header) specifies the host and port number of the server to which the request is being sent.
- If no port is included, the default port for the service requested is implied (e.g., `443` for an HTTPS URL, and `80` for an HTTP URL).
- A `Host` header field must be sent in all HTTP/1.1 request messages. A [`400 Bad Request`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Status/400) status code may be sent to any HTTP/1.1 request message that lacks or contains more than one `Host` header field.