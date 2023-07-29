eksctl create iamidentitymapping \
 --cluster eks-cluster-fargate \
 --region=us-west-2 \
 --arn arn:aws:iam::035612810169:role/AwsResilienceHubAssessmentEKSAccessRole \
 --group resilience-hub-eks-access-group \
 --username AwsResilienceHubAssessmentEKSAccessRole
