 kubectl apply -f nginx-deployment.yml
 
 kubectl apply -f nginx-service.yml
 
 kubectl port-forward svc/nginx-service 8080:80 --address=0.0.0.0 &
