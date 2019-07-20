sse-pubsub demo
===============

The **sse-pubsub** package is...
>`a simple NodeJS module to generate Server-Sent-Events streams with a publish/subscribe interface and simple integration with either Node's built in HTTP library or any framework that exposes it, eg. ExpressJS.`

This Glitch project is simply the `more detailed demo` from the /demo/ directory distributed with the **sse-pubsub** module:

* The server creates two SSE channels and then recursively publishes some random data on those channels.
* The client page connects to the server's two SSE channels and outputs the events to the log containers as they are received.

More information on the **sse-pubsub** package can be found [here](https://www.npmjs.com/package/sse-pubsub).

If you are curious about Server Sent Events (SSE), check out the interesting article, [Server-sent events with Fastly](https://www.fastly.com/blog/server-sent-events-fastly), that introduced me to the **sse-pubsub** package.

Enjoy.