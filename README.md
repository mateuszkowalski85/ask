# ASK Helm Repo

![ASK-Logo](images/ask-logo.png)

This respository is a component of **[ASK](https://www.praqma.com/products/ask/) Atlassian Software in Kubernetes**. 
The charts are built with circleci and pushed into a public ASK helm repository.

To configure the repository on your machine:

```
helm repo add ask https://praqma-helm-repo.s3.amazonaws.com/
helm repo update
helm search ask
```

Then, you can install charts from that repo:

```
helm install ask/jira
```

