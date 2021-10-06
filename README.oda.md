# ODA Canvas

## Deploy a SigScale RIM cluster as an ODA Canvas Component
	kubectl apply -f oda-component

## Delete the RIM Component
	kubectl delete -f oda-component
	kubectl delete pvc im-data-im-{0,1,2}

