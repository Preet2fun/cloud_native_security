# kubectl exec -it pod/customer-5446d96c8b-95t6d -n yaobank -c customer -- /bin/bash
-c is container name (customer)
pod/customer-5446d96c8b-95t6d is pod name

# to add service account label to any pod use below command
kubectl label serviceaccount -n yaobank customer internet-egress=allowed