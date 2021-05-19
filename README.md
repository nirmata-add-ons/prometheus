# Prometheus

This README documents the Prometheus integration as Nirmata add-on on Kubernetes clusters.

### What is the Prometheus?

Prometheus is an open-source system monitoring and alerting toolkit

### How do I get set up?
1. Clone this repository or add its contents to your own private Git repository.
2. Create a Nirmata catalog application with a Git upstream and select the Prometheus repository. You can optionally select the kustomization.
3. Edit the catalog application and select an add-on category (e.g. Logging). This is required to select the application as an add-on.
4. Update a Cluster Type, or create a new one, and select the Prometheus add-on application in the "Add-Ons" section. Ensure that the namespace you use is "**nirmata-monitoring**" and environment is "nirmata-monitoring-< cluster-name >"
5. Create clusters using the cluster type. 
6. If the addon is to be added to a running cluster, create an environment with the namespace "**nirmata-monitoring**" and choose this environment while deploying the application
7. Verify that the application is running in Nirmata. 
8. Access the Grafana dashboard on the exposed port, the deployment holds the credentials to access the application.

### Validated Nirmata and Kubernetes versions

Prometheus Version - 
Nirmata Version - Cloud Edition - 
Kuvernetes Version - 

### Who do I talk to?
For issues, contact support@nirmata.com
