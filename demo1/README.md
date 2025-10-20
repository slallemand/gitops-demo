*Demo1* : 
HTTPD deployement using pure kubernetes manifests in git 
- console gitops 
- application creation
	- New App
	- whatever-demo1
	- default
	- Auto-Create Namespace
	- https://github.com/slallemand/gitops-demo.git
	- Path : demo1
	- https://kubernetes.default.svc
	- ns : whatever-demo1

Replicas modification in OCP console then in git

=> delete application

create the application using yaml file
https://github.com/slallemand/gitops-demo/blob/main/Application-demo1.yaml

If I need another apache httpd server, I need to recreate another subdir / repo with same code !
