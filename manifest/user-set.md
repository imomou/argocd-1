argocd proj role add-policy default create-sync --action get --permission allow --object "*"
argocd proj role add-policy default create-sync --action create --permission allow --object "*"
argocd proj role add-policy default create-sync --action sync --permission allow --object "*"
argocd proj role add-policy default create-sync --action update --permission allow --object "*"
argocd proj role add-policy default create-sync --action delete --permission allow --object "*"

# confirm

argocd proj role get default create-sync