# Installing kubectl plugins
A plugin is a standalone executable file, whose name begins with kubectl-. To install a plugin, move its executable file to anywhere on your PATH.

# Uses
For using plugin you need use this command kubectl kubeplugin <resourcetype> <namespace>

# Sample
kubectl kubelugin pods argocd
# Answer
pods, argocd, argocd-application-controller-0, 1m, 23Mi
pods, argocd, argocd-applicationset-controller-6c8fbc69b5-d8ng5, 1m, 18Mi
pods, argocd, argocd-dex-server-59bd76d76-zptdb, 1m, 28Mi
