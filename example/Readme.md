## Example

---

CRD's given in this example, `nginx-prod-crd.yaml` & `nginx-staging-crd.yaml` can be used as a reference to deploy two ArgoCD applications from the repo.

#### Steps

        kubectl apply -f nginx-staging-crd.yaml
        kubectl apply -f nginx-prod-crd.yaml
