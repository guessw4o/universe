1. Download and install VirtualBox
https://download.virtualbox.org/virtualbox/7.0.0/VirtualBox-7.0.0-153978-Win.exe

2. Download and add PATH to files
https://storage.googleapis.com/kubernetes-release/release/v1.25.0/bin/windows/amd64/kubectl.exe
https://github.com/kubernetes/minikube/releases/download/v1.27.0/minikube-windows-amd64.exe
https://get.helm.sh/helm-canary-windows-amd64.zip


3. minikube start
4. helm install universe universe/ --namespace unitest --create-namespace
5. kubectl port-forward -n unitest service/grafana 80
6. 127.0.0.1:80