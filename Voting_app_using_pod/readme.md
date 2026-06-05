This is the voting application using k8s pods. 
To execute this files use below command.

kubectl apply -f .  # All the files should be in one directoery bez this will wxecutes all the yml files in PWD.

kubectl get pod     # Will list the pods
kubectl get service  # will list the service with the ports exposed
kubectl get node -o wide  # Will show the node with the IP.