# Aprendendo Kubernetes 
 - Alura
 - Kubernetõ

## Comandos
### Minikube
	- SEMPRE iniciar o minikube ao ligar o pc
	- minikube start --vm-driver=virtualbox 
	- minikube status
### Kubectl
	- Criando pods por command line
		- kubectl run <nome do pod> --image=<imagem do container>
		
	- Criando pods por yamls
		- kubectl apply -f <nome do arquvio yaml>
		
	- Comandos do Kubectl
		- kubectl get pods
			- utilizando o argumento --watch é possível ver as atualizações
		- kubectl describe pod <nome do pod> or kubectl describe pod -o wide (ver o ip)
		- kubectl delete pod <nome do pod> or kubectl delete -f <file yaml>
		- kubectl edit pod <nome do pod>
		- kubectl exec -it <nome do pod> -- <comando>(normalmente bash) (Igual no docker)