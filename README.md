## Folder Structure

realtime-project/

├── Chart.yaml

├── values.yaml (ENV-BASED CONFIG)

├── templates/

│   ├── namespace.yaml

│   ├── configmap.yaml

│   ├── secret.yaml

│   ├── deployment.yaml (BACKEND)

│   ├── service.yaml

│   ├── ingress.yaml (WebSocket Enabled)

│   ├── hpa.yaml

│   ├── serviceaccount.yaml

│   ├── pdb.yaml

│   └── redis.yaml
