# argocd-deploy

i)	Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes.

ii)	Argo cd is preferred because Application definitions, configurations, and environments should be declarative and version controlled. Application deployment and lifecycle management should be automated, auditable, and easy to understand.

![image](https://github.com/Gaurav098766/argocd-deploy/assets/97042529/e69ad652-bea6-49e1-9fc0-5083f4c36d2b)

iv)	Argo CD is implemented as a kubernetes controller which continuously monitors running applications and compares the current, live state against the desired target state (as specified in the Git repo). A deployed application whose live state deviates from the target state is considered OutOfSync. Argo CD reports & visualizes the differences, while providing facilities to automatically or manually sync the live state back to the desired target state. Any modifications made to the desired target state in the Git repo can be automatically applied and reflected in the specified target environments.
