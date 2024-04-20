## ACME PORTAL COMPANY - TECHNICAL DOCUMENTATION
![deployment diagram](./deployments/deployments.png)
---
|           ***PLATFORM***          | ***CONTAINER REGISTRY*** | ***MAVEN REGISTRY*** |  ***Go Registry***  |
| --------------------------------- | ------------------------ | -------------------- | ------------------- |
| Kubernetes (Hosting/Provider TBD) |        Docker Hub        |   GitHub Packages    |   GitHub Packages   |
---

### ***FRONTEND*** (deployment)
```
Go, LabStack Echo, HTMX, Tailwind CSS
```
### ***WATCHTOWER*** (deployment)
```
Java, Spring Boot
```
### ***FOOTBALL*** (deployment)
```
Java, Spring Boot
```
### ***FOOTBALL DATA*** (cronjob)
```
Go
```