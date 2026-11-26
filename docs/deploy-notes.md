# Deployment notes

- Application: device-registry
- Port: 9000 (uvicorn), published as 8080 by the proxy
- Heartbeat timeout: 120 seconds
- Health check path: /health
- Allowed cities: pune, mumbai, delhi
