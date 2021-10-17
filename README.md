# Poros-k8s-studyGroup
# Basic Command
kubectl get all
kubectl exec -it pod/{Nama_POD} bin/bash
kubectl port-forward service/landing-p 8090:81 (open web in localhost browser)


#lv1:
kubectl apply -f LandingPage.yaml

#lv2:
kubectl apply -f configmap.yaml
kubectl apply -f LandingPage.yaml
