### commands to install keycloak CRDs
```zsh

#CRDs

kubectl apply -f https://raw.githubusercontent.com/keycloak/keycloak-k8s-resources/23.0.4/kubernetes/keycloaks.k8s.keycloak.org-v1.yml

kubectl apply -f https://raw.githubusercontent.com/keycloak/keycloak-k8s-resources/23.0.4/kubernetes/keycloakrealmimports.k8s.keycloak.org-v1.yml

#keycloak Operator (to automate deployment)

kubectl apply -f https://raw.githubusercontent.com/keycloak/keycloak-k8s-resources/23.0.4/kubernetes/kubernetes.yml


```
# quote-demo
