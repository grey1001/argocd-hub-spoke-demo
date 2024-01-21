Install ArgoCD using Helm or any other preferred method.

Download the ArgoCD CLI from the ArgoCD website and install it on your local machine if not already installed.

Run the command argocd login and provide your username and password when prompted.

To add your clusters, use the command argocd cluster add "cluster context name" --server "ip:port".

Verify the clusters added to ArgoCD by running either argocd cluster list from the CLI or checking the clusters in the ArgoCD graphical user interface (GUI).

In ArgoCD, create an application and select the destination cluster from the available options.

If you need to set up multiple destinations within a single application, utilize "ArgoCD Application Sets" for efficient management.