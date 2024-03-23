## Demo Repo for Karpenter 
1. Creating an EKS cluster with required IAM , Service ACC
2. Install karpenter using HELM
3. Create your required NodePool and EC2NodeClass
4. Scale up your deployment
    `kubectl logs -f -n "${KARPENTER_NAMESPACE}" -l app.kubernetes.io/name=karpenter -c controller`
