```bash
Kubectl run --image=nginx:1.7.9 --replicas=2 --port=80 --labels="app=nginx,env=prod" nginx-prod
```
```bash
kubectl run redis --image=redis123 --dry-run=client -o yaml > redis.yaml
```
```bash
kubectl get pods 
```
```bash
kubectl get pods -l app=nginx
```
```bash
kubectl describe pods nginx-prod-7b4c8b5c6f-7z5zr
```
```bash
kubectl apply -f pods-config.yml
```
```bash
kubectl delete pods nginx-prod-7b4c8b5c6f-7z5zr
```
