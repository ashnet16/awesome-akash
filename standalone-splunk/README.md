# Deploying Splunk on Akash

This repository contains the deployment configurations for a standalone splunk installation on Akash. This splunk installation is running a single splunk instance within a docker container. 



# Networking


## Ingress

In this deployment, we are allowing traffic ingress from the web to port 8080 (unencrypted) to Splunk Web.



## Egress

No outbound traffic allowed at the moment.



# Next Steps

In future iterations of this project we will explore configuring SSL for Web andforwarding data using a universal forwarder. In addition, we will explore a distributed splunk deployment in a different project within  a different folder.
