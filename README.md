# kubernetes

### 도커허브에 이미지 올리기
### docker-desktop or minikube 환경에서 app - redis - postgresql 연동
### yaml sample 여러개 만들기

### 터미널 들어가기
kubectl exec -it [파드명] -- /bin/bash

kubectl exec [파드명] -- curl -s 10.42.0.26
kubectl exec [파드명] -- whoami

### curl
kubectl run curl -it --rm --generator=run-pod/v1 --image curlimages/curl -n <namespace> -- sh

kubectl run curl -it --rm --generator=run-pod/v1 --image curlimages/curl -- sh

### link
https://kimmj.github.io/kubernetes/port-targetport-nodeport-in-kubernetes/