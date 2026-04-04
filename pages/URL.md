aliases:: [[address]] [[references]] [[link]] [[links]] [[hyperlink]]

- **Components of a URL**
	- A URL is a [[web]] [[address]] plus a protocol: for example, if you open a new tab in your browser, type in `developer. mozilla.org` into the address bar, and press `Enter`/`Return`, you will be redirected to a URL like the following:
		- https://developer.mozilla.org/en-US/
	- The main parts of the  URL are:
		- `[[https]]`
			- The protocol being used to send the request. In this case, we are using HTTPS, which is a secure version of [[HTTP]] that stops bad people from reading your data while it is being transported. On the modern web, pretty much every server uses HTTPS, so if you don't include it explicitly, the browser assumes that it what you are using and adds it for you.
		- `developer.mozilla.org`
			- The **domain name** [[DNS]] of the URL, which represents the top-level location of the server you are connecting to. In this case, the web address you typed in is equal to the domain name, but this is not always the case - you could choose to type in a more complicated web address. Note that the `developer` part is a [[subdomain]] (distinct content area) of Mozilla's mozilla.org domain. There are other subdomains on Mozilla's site that host distinct content - see **support.mozilla.org** and **bugzilla.mozilla.org** , f.e.
		- `/en-US/`
			- The [[path]] to the resource on the server that you are accessing. MDN keeps all its US English content in a folder called en-US, which is what this URL is pointing to.
			- If you have your browser set up to prefer English content by default, then this is the URL you will be redirected to when you type in **developer.mozilla.org.** If you have your browser set up to prefer a different language that MDN supports, such as French, you will be redirected to a different URL, such as https://developer.mozilla.org/fr/ instead. This isn't available to every website by default; the MDN developers have set MDN up like this to allow people to easily access the language they prefer.
		-
		-