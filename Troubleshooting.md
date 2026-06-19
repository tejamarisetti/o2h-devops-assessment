# Troubleshooting Scenarios
## Scenario 1

Problem:
Docker container exits immediately after startup.
### Possible Reasons

- Application crash
- Wrong CMD command
- Missing dependencies
- Port mismatch
- Application process completed
### Debugging Commands

```bash
docker ps -a
docker logs <container-id>
docker inspect <container-id>
docker run -it o2h-app bash
```
## Scenario 2

Problem:
Application works locally but not on the server.
### Things to Check

- Port number
- Firewall settings
- Docker container status
- Network configuration
- Application logs
- Server connectivity
### Commands

```bash
docker ps
docker logs <container-id>
curl localhost:3000
ping <server-ip>
```
