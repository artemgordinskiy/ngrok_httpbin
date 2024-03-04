# ngrok_httpbin
Start ngrok + httpbin for debugging webhooks

## How to
1. Start ngrok and httpbin:
```
docker compose up
```
2. Grab the URL printed out by the ngrok container, e.g. `https://sdp-42-42-42-42.ngrok-free.app`
3. Open `localhost:4040` to monitor the requests
