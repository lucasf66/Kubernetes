# Aprendendo Kubernetes 
 - Alura

## Comandos
- Minikube
    - minikube start --vm-driver=virtualbox
    - minikube status
- Kubectl
    - kubectl apply -f <nome do arquvio yaml>
    - kubectl get pods
        - utilizando o argumento --watch é possível ver as atualizações
    - kubectl describe pod <nome do pod>