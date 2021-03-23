# prometheus as a Nirmata add-on service

This README provides steps to install Prometheus for Kubernetes cluster as Nirmata add-on.

What is  Prometheus?
Prometheus is an open-source systems monitoring and alerting toolkit
 
How do I get set up?
Use the yaml available in the repo and import it into your default-add-on catalog in Nirmata.
Go to your cluster in Nirmata, select add-on tab and choose deploy add-on from the catalog.
Ensure that the namespace you use is "nirmata-monitoring" and environment is "nirmata-monitoring-<cluster-name>"
Deploy the application and confrim that it is running. 

Issues?
For issues, please reach out to support@nirmata.com
