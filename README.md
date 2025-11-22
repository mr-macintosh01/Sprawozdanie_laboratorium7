# Sprawozdanie_laboratorium7

### 1. <code>kubectl get ns</code>

<img width="478" height="283" alt="image" src="https://github.com/user-attachments/assets/0c367bf8-7ffc-4ce5-90b4-d0bcffc05e75" />

### 2. <code>kubectl apply -f remoteweb-pod-svc.yaml</code>

<img width="710" height="77" alt="image" src="https://github.com/user-attachments/assets/4db056d0-bd4c-457c-a7ee-7233c57aff86" />

### 3. <code>kubectl get pods -n remote</code>

<img width="456" height="77" alt="image" src="https://github.com/user-attachments/assets/bf913506-beb8-40bd-967f-4f7f4fe27eef" />

### 4. <code>kubectl get svc -n remote</code>

<img width="733" height="82" alt="image" src="https://github.com/user-attachments/assets/2f73e547-2bcf-4315-801a-9716dd47539b" />

### 5. <code>kubectl get pods</code>

<img width="509" height="100" alt="image" src="https://github.com/user-attachments/assets/8b38d2f6-c615-456d-a3c5-34f3fe87b6fd" />

### 6. <code>kubectl exec -it testpod -- wget --spider --timeout=1 http://remoteweb-svc.remote/</code>

<img width="908" height="67" alt="image" src="https://github.com/user-attachments/assets/50d99094-ea26-480e-a1ae-b356584e83b4" />

### 7. <code>kubectl exec -it testpod -- wget -S --timeout=1 -O - http://remoteweb-svc.remote.svc.cluster.local/ || true</code>

<img width="1148" height="239" alt="image" src="https://github.com/user-attachments/assets/8106c5cf-1bf4-4b8f-88fc-d29227b699f7" />

### 8. <code>minikube ip</code>

<img width="296" height="51" alt="image" src="https://github.com/user-attachments/assets/d313932a-1b6c-4080-a9d6-e8382c654618" />

### 9. <code>curl -I http://192.168.49.2:31999/</code>

<img width="944" height="58" alt="image" src="https://github.com/user-attachments/assets/341dd967-47fe-4729-98ea-8d5a3a35c9e6" />

### 10. <code>minikube profile list</code>

<img width="1042" height="138" alt="image" src="https://github.com/user-attachments/assets/095f4848-e44c-4e8e-a9db-0888aa40eb4c" />

###11. <code>minikube service remoteweb-svc -n remote --url</code>
<img width="877" height="109" alt="image" src="https://github.com/user-attachments/assets/aa5dbe34-60f7-4d2a-ab32-068b36c7e3d7" />
<img width="1919" height="1029" alt="image" src="https://github.com/user-attachments/assets/a1736d5c-a693-4d17-ad01-a0113c3ce73a" />


