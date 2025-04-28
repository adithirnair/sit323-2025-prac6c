# SIT323/737 - 6.1C - Interacting with Kubernetes

This repository contains the files for SIT323/737 Task 6.1C.  
It demonstrates how to deploy a Dockerized Node.js app into a Kubernetes cluster and interact with it via port-forwarding.

---

## Project Structure
- `Dockerfile` — Defines the Node.js application container.
- `app.js` — Simple Express server responding on port 3000.
- `package.json` — Node.js project configuration.
- `deployment.yaml` — Kubernetes deployment for the Node.js application.
- `service.yaml` — Kubernetes service to expose the app.

---

## Steps to Deploy and Interact

1. **Start Minikube:**
   ```bash
   minikube start
