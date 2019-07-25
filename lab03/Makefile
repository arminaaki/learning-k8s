deploy:
	kubectl apply -f namespace.yaml
	kubectl apply -f deployment.yaml
	kubectl apply -f service.yaml

clean:
	kubectl delete deployment webserver
	kubectl delete svc webserver
	kubectl delete namespace lab02
