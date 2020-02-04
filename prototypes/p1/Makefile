help:
	echo "help..."

copy_config:
	cp ~/.kube/config ./k8s_config/config
	cp ~/.minikube/ca.crt ./k8s_config/ca.crt
	cp ~/.minikube/client.crt ./k8s_config/client.crt
	cp ~/.minikube/client.key ./k8s_config/client.key
	sed -i 's/\/home\/whes\/.minikube/./g' ./k8s_config/config