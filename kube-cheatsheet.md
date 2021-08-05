### Kubernetes commands essential ####

**Create an NGINX Pod**

``
kubectl run nginx --image=nginx
``

**Generate POD Manifest YAML file (-o yaml). Don’t create it(–dry-run)**

``
kubectl run nginx --image=nginx --dry-run=client -o yaml
``

**Create a deployment**

``
kubectl create deployment --image=nginx nginx
``

**Generate Deployment YAML file (-o yaml). Don’t create it(–dry-run)**

``
kubectl create deployment --image=nginx nginx --dry-run=client -o yaml
``

**Generate Deployment YAML file (-o yaml). Don’t create it(–dry-run)**

``
kubectl create deployment --image=nginx nginx --dry-run=client -o yaml > nginx-deployment.yaml
``