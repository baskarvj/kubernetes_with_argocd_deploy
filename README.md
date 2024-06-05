# cicd_with_AKS

* github pipeline and argocd must be in different repository otherwise we will face looping pipeline run, pipeline will trigger for each arcd deploy,

* install helm before running argocd
~~~
curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3
chmod 700 get_helm.sh
./get_helm.sh
~~~


### Config repo 
https://gitlab.com/nanuchi/argocd-app-config

### argocd installation reference link
https://argo-cd.readthedocs.io/en/stable/getting_started/#1-install-argo-cd

### Login to ArgoCD
https://argo-cd.readthedocs.io/en/stable/getting_started/#4-login-using-the-cli

### argocd configuration reference link
https://argo-cd.readthedocs.io/en/stable/operator-manual/declarative-setup/

