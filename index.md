# Live DEMO

Want give it a try? There is a simple demo of our implementation:

1. Connect to the WebSocket at

        bitsocket-demo.bitrich.info:8080

2. Send any JSON payload with following data to subscribing a channel:

    <!-- language: lang-json -->
    
        {"event":"addChannel", "channel":"CHANNEL_NAME"}

3. Then send data to the REST endpoint:

        bitsocket-demo.bitrich.info/publish/CHANNEL_NAME

> Note: This is only demo deployment with a lot checks turned off. It is running on low cost server. **But it handles more than [5000 concurent](performance.md) users.**

## Why use it?

- performance in the first place
- no need for 3rd party provider
- securely operated on your own servers
- don't mess up with WebSocket implementation
- highly scalable solution using Docker
- did we mention the performance?

## What will you get?

- licence for commercial usage
- documentation how to build, deploy and run the server
- support for your implementation and operation
- source code
- streaming API for the public data (private trading is in development)
- we implement your exchange in [xchange-stream](https://github.com/bitrich-info/xchange-stream) client library.

## What it cost?

Contact us at [info@bitrich.info](mailto:info@bitrich.info). We'll find right price for everyone.
