# Ejercicio7
Detalle ejercicio 7 curso de Kubernetes

// Crear el configmap

kubectl -n arba create configmap -f configmap-env.yaml


// Aplicar el deploy

kubectl -n arba apply -f deployment.yaml
