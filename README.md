# cicd_with_AKS

* github pipeline and argocd must be in different repository otherwise we will face looping pipeline run, pipeline will trigger for each arcd deploy,

* install helm before running argocd
curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3
chmod 700 get_helm.sh
./get_helm.sh
