# Setting up Wordpress in Kubernetes

## Pre-requisites
1. Install an Ingress (Nginx, HaProxy, Kong, Azure Application Gateway, AWS Application Load Balancer/Network Load Balancer)

2. Clone this repository

3. Run the `kubectl apply -f .`

4. The Wordpress and MySQL will successfully deploy

## How to Access your new Wordpress

Use the URL configured on the `hosts` for your Ingress controller to access the Wordpress website
