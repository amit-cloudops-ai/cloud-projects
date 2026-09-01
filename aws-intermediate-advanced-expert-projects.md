# AWS Projects — Intermediate, Advanced & Expert (mzazon/cloud-projects)

Source: https://github.com/mzazon/cloud-projects

## Numbers

- Total projects in repo: 1110
- Total AWS projects: 492
  - beginner: 59
  - intermediate: 153
  - advanced: 178
  - expert: 102
- **Selected (intermediate + advanced + expert): 433**

## 15-project fast-track (do these first, in this order)

Picked because they map directly to what a Cloud/DevOps Engineer interviewer actually probes: containers/EKS, CI/CD, multi-region networking, IAM/security, cost control, and observability — the recurring themes across your target roles.

1. **Deploying Fargate Containers with Application Load Balancer** — *intermediate*, ~60 min
   - Services: ECS, Fargate, ALB, ECR
   - https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/deploying-fargate-containers-alb/deploying-fargate-containers-alb.md
2. **Running Containers with AWS Fargate** — *intermediate*, ~45 min
   - Services: ECS, Fargate, ECR, Application Auto Scaling
   - https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/running-containers-fargate/running-containers-fargate.md
3. **Container CI/CD Pipelines with CodePipeline** — *expert*, ~210 min
   - Services: CodePipeline, CodeDeploy, CodeBuild, ECS
   - https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/container-cicd-pipelines-codepipeline/container-cicd-pipelines-codepipeline.md
4. **EKS Logging and Monitoring with Prometheus** — *advanced*, ~120 min
   - Services: EKS, CloudWatch, AMP, VPC
   - https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/eks-logging-monitoring-prometheus/eks-logging-monitoring-prometheus.md
5. **EKS Multi-Tenant Security with Namespaces** — *expert*, ~180 min
   - Services: EKS, IAM, Kubernetes, VPC
   - https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/eks-multitenant-security/eks-multitenant-security.md
6. **Cost-Optimized EKS Node Groups with Spot and Mixed Instances** — *advanced*, ~120 min
   - Services: eks, ec2, iam, cloudwatch
   - https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/eks-nodegroups-spot-mixed/eks-nodegroups-spot-mixed.md
7. **Kubernetes Operators for AWS Resources** — *advanced*, ~120 min
   - Services: eks, iam, s3, lambda
   - https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/kubernetes-aws-operators/kubernetes-aws-operators.md
8. **Lambda Safe Deployments with Blue-Green and Canary** — *intermediate*, ~60 min
   - Services: lambda, api-gateway, cloudwatch, iam
   - https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/lambda-safe-deployments/lambda-safe-deployments.md
9. **Connecting Multi-Region Networks with Transit Gateway** — *expert*, ~180 min
   - Services: transit-gateway, vpc, cloudwatch, ec2
   - https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/connecting-multi-region-networks/connecting-multi-region-networks.md
10. **Securing Networks with Micro-Segmentation using NACLs and Security Groups** — *expert*, ~180 min
   - Services: VPC, EC2, CloudWatch, IAM
   - https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/securing-networks-with-micro-segmentation/securing-networks-with-micro-segmentation.md
11. **DynamoDB Global Tables for Multi-Region Apps** — *advanced*, ~120 min
   - Services: dynamodb, cloudwatch, iam, lambda
   - https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/dynamodb-global-tables-multiregion/dynamodb-global-tables-multiregion.md
12. **Multi-Region Disaster Recovery with Aurora DSQL** — *advanced*, ~120 min
   - Services: Aurora DSQL, EventBridge, Lambda, CloudWatch
   - https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/multi-region-dr-aurora-dsql/multi-region-dr-aurora-dsql.md
13. **Container Secrets Management with Secrets Manager** — *advanced*, ~150 min
   - Services: Secrets Manager, ECS, EKS, IAM
   - https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/container-secrets-management/container-secrets-management.md
14. **Securing APIs with Lambda Authorizers and API Gateway** — *intermediate*, ~90 min
   - Services: API Gateway, Lambda, IAM, CloudWatch
   - https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/securing-apis-lambda-authorizers/securing-apis-lambda-authorizers.md
15. **Container Observability and Performance Monitoring** — *intermediate*, ~100 min
   - Services: ECS, CloudWatch, X-Ray, Prometheus
   - https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/container-observability-monitoring/container-observability-monitoring.md

## Full checklist by category

### Compute & Infrastructure (110)

- [ ] **AI-Powered Infrastructure Code Generation** — *advanced*, ~120 min | Amazon Q Developer, AWS Infrastructure Composer, AWS Lambda, Amazon S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/ai-infrastructure-code-generation/ai-infrastructure-code-generation.md
- [ ] **Amplify Mobile Backend with Authentication and APIs** — *advanced*, ~120 min | amplify, appsync, cognito, dynamodb
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/amplify-mobile-backend/amplify-mobile-backend.md
- [ ] **Automated Processing with S3 Event Triggers** — *advanced*, ~120 min | s3, lambda, sqs, sns
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/s3-event-processing/s3-event-processing.md
- [ ] **Automating Email Processing with SES and Lambda** — *advanced*, ~120 min | ses, lambda, s3, sns
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/automating-email-processing-ses/automating-email-processing-ses.md
- [ ] **Automating Text Analysis Pipelines with Amazon Comprehend** — *advanced*, ~120 min | comprehend, s3, lambda, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/automating-text-analysis-pipelines/automating-text-analysis-pipelines.md
- [ ] **Batch Processing Workloads with AWS Batch** — *advanced*, ~150 min | AWS Batch, EC2, ECR, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/batch-processing-aws-batch/batch-processing-aws-batch.md
- [ ] **Blue-Green Deployments for ECS Applications** — *advanced*, ~120 min | ECS, ALB, CodeDeploy, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/blue-green-deployments-ecs/blue-green-deployments-ecs.md
- [ ] **Business Process Automation with Step Functions** — *advanced*, ~150 min | Step Functions, Lambda, SNS, SQS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/business-process-automation-stepfunctions/business-process-automation-stepfunctions.md
- [ ] **Capturing Database Changes with DynamoDB Streams** — *advanced*, ~120 min | dynamodb, lambda, cloudwatch, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/database-change-streams-dynamodb/database-change-streams-dynamodb.md
- [ ] **Circuit Breaker Patterns with Step Functions** — *advanced*, ~120 min | Step Functions, Lambda, DynamoDB, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/circuit-breaker-patterns-stepfunctions/circuit-breaker-patterns-stepfunctions.md
- [ ] **Configuration Management with Systems Manager** — *advanced*, ~150 min | Systems Manager, EC2, CloudWatch, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/configuration-management-systems-manager/configuration-management-systems-manager.md
- [ ] **Container Resource Optimization with EKS** — *advanced*, ~150 min | EKS, CloudWatch, Cost Explorer, VPA
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/container-resource-optimization-eks/container-resource-optimization-eks.md
- [ ] **Container Secrets Management with Secrets Manager** ⭐ — *advanced*, ~150 min | Secrets Manager, ECS, EKS, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/container-secrets-management/container-secrets-management.md
- [ ] **Container Security Scanning Pipelines** — *advanced*, ~150 min | ECR, Inspector, CodeBuild, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/container-security-pipelines-ecr/container-security-pipelines-ecr.md
- [ ] **Containerized Web Applications with App Runner** — *advanced*, ~120 min | App Runner, RDS, Secrets Manager, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/containerized-web-apps-apprunner/containerized-web-apps-apprunner.md
- [ ] **Cost Optimization Automation with Lambda** — *advanced*, ~120 min | lambda, trusted-advisor, sns, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cost-optimization-automation-lambda/cost-optimization-automation-lambda.md
- [ ] **Cost-Optimized Batch Processing with Spot** — *advanced*, ~120 min | aws-batch, ec2, ecr, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cost-optimized-batch-spot/cost-optimized-batch-spot.md
- [ ] **Cost-Optimized EKS Node Groups with Spot and Mixed Instances** ⭐ — *advanced*, ~120 min | eks, ec2, iam, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/eks-nodegroups-spot-mixed/eks-nodegroups-spot-mixed.md
- [ ] **Creating Progressive Web Apps with Amplify Hosting** — *advanced*, ~120 min | amplify, cloudfront, route53, acm
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/progressive-web-apps-amplify-hosting/progressive-web-apps-amplify-hosting.md
- [ ] **Custom Video Conferencing with Amazon Chime SDK** — *advanced*, ~120 min | chime-sdk, lambda, api-gateway, dynamodb
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/video-conferencing-chime-sdk/video-conferencing-chime-sdk.md
- [ ] **Customer Service Chatbots with Lex** — *advanced*, ~120 min | amazon-lex, aws-lambda, dynamodb, amazon-connect
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/customer-service-chatbots-lex/customer-service-chatbots-lex.md
- [ ] **Developing Progressive Web Applications with AWS Amplify** — *advanced*, ~120 min | amplify, cognito, appsync, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/progressive-web-applications-amplify/progressive-web-applications-amplify.md
- [ ] **Developing Web Apps with Amplify and Lambda** — *advanced*, ~120 min | amplify, lambda, apigateway, cognito
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/developing-web-apps-amplify/developing-web-apps-amplify.md
- [ ] **EC2 Image Building Pipelines with Image Builder** — *advanced*, ~120 min | EC2 Image Builder, EC2, IAM, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/ec2-image-building-pipelines/ec2-image-building-pipelines.md
- [ ] **ECS Service Discovery with Route 53** — *advanced*, ~120 min | ecs, route53, elasticloadbalancing, cloudmap
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/ecs-service-discovery-route53/ecs-service-discovery-route53.md
- [ ] **EKS Logging and Monitoring with Prometheus** ⭐ — *advanced*, ~120 min | EKS, CloudWatch, AMP, VPC
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/eks-logging-monitoring-prometheus/eks-logging-monitoring-prometheus.md
- [ ] **Event Replay with EventBridge Archive** — *advanced*, ~120 min | eventbridge, lambda, s3, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/event-replay-system/event-replay-system.md
- [ ] **Event-Driven Video Processing with MediaConvert** — *advanced*, ~120 min | s3, lambda, mediaconvert, eventbridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/video-processing-mediaconvert/video-processing-mediaconvert.md
- [ ] **Generating Speech with Amazon Polly** — *advanced*, ~120 min | polly, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/generating-speech-amazon-polly/generating-speech-amazon-polly.md
- [ ] **High-Performance GPU Computing Workloads** — *advanced*, ~120 min | ec2, cloudwatch, systems-manager, sns
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/high-performance-gpu-computing/high-performance-gpu-computing.md
- [ ] **Hybrid Kubernetes Monitoring with EKS Hybrid Nodes** — *advanced*, ~150 min | Amazon EKS, AWS Fargate, Amazon CloudWatch, AWS Systems Manager
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/hybrid-kubernetes-monitoring/hybrid-kubernetes-monitoring.md
- [ ] **Implementing Dedicated Hosts for License Compliance** — *advanced*, ~150 min | EC2, License Manager, AWS Config, Systems Manager
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/dedicated-hosts-license-compliance/dedicated-hosts-license-compliance.md
- [ ] **Kubernetes Operators for AWS Resources** ⭐ — *advanced*, ~120 min | eks, iam, s3, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/kubernetes-aws-operators/kubernetes-aws-operators.md
- [ ] **Managing WebSocket APIs with Route and Connection Handling** — *advanced*, ~120 min | api-gateway, lambda, dynamodb, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/websocket-apis-connection-management/websocket-apis-connection-management.md
- [ ] **Microservices Orchestration with EventBridge** — *advanced*, ~120 min | eventbridge, step-functions, lambda, dynamodb
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/microservices-orchestration/microservices-orchestration.md
- [ ] **Mobile App A/B Testing with Pinpoint Analytics** — *advanced*, ~150 min | pinpoint, iam, s3, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/mobile-app-ab-testing-pinpoint/mobile-app-ab-testing-pinpoint.md
- [ ] **Orchestrating Global Event Replication with EventBridge** — *advanced*, ~120 min | eventbridge, lambda, cloudwatch, route53
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/orchestrating-global-event-replication/orchestrating-global-event-replication.md
- [ ] **Orchestrating Notifications with SNS SQS and Lambda** — *advanced*, ~120 min | sns, sqs, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/orchestrating-notifications-sns-sqs/orchestrating-notifications-sns-sqs.md
- [ ] **Pinpoint Mobile Push Notifications** — *advanced*, ~120 min | pinpoint, sns, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/pinpoint-push-notifications/pinpoint-push-notifications.md
- [ ] **Processing Serverless Streams with Kinesis and Lambda** — *advanced*, ~120 min | kinesis, lambda, cloudwatch, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/serverless-stream-processing-kinesis/serverless-stream-processing-kinesis.md
- [ ] **Quantum Computing Pipelines with Braket** — *advanced*, ~150 min | Amazon Braket, AWS Lambda, Amazon S3, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/quantum-computing-braket-lambda/quantum-computing-braket-lambda.md
- [ ] **Real-Time Data Synchronization with AppSync** — *advanced*, ~120 min | AppSync, DynamoDB, Lambda, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/realtime-data-sync-appsync/realtime-data-sync-appsync.md
- [ ] **Scalable HPC Cluster with Auto-Scaling** — *advanced*, ~120 min | ec2, parallelcluster, s3, fsx
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/scalable-hpc-cluster/scalable-hpc-cluster.md
- [ ] **Scalable Webhook Processing with SQS** — *advanced*, ~120 min | api-gateway, sqs, lambda, dynamodb
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/webhook-processing-sqs/webhook-processing-sqs.md
- [ ] **Scientific Computing with Batch Multi-Node** — *advanced*, ~120 min | batch, ec2, ecr, efs
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/scientific-computing-batch-multinode/scientific-computing-batch-multinode.md
- [ ] **Serverless Batch Processing with Fargate** — *advanced*, ~150 min | AWS Batch, Fargate, IAM, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/batch-processing-fargate/batch-processing-fargate.md
- [ ] **Transforming API Requests with VTL Templates** — *advanced*, ~120 min | API Gateway, Lambda, CloudWatch, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/api-transformation-vtl-templates/api-transformation-vtl-templates.md
- [ ] **API Composition with Step Functions** — *expert*, ~180 min | Step Functions, API Gateway, Lambda, DynamoDB
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/api-composition-step-functions/api-composition-step-functions.md
- [ ] **ARM-based Workloads with Graviton Processors** — *expert*, ~180 min | EC2, CloudWatch, Auto Scaling, Application Load Balancer
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/arm-graviton-workloads/arm-graviton-workloads.md
- [ ] **Advanced API Gateway Deployment Strategies** — *expert*, ~180 min | API Gateway, Lambda, CloudWatch, Route 53
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/advanced-api-deployment-strategies/advanced-api-deployment-strategies.md
- [ ] **Application Modernization with App2Container** — *expert*, ~240 min | App2Container, ECS, EKS, ECR
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/application-modernization-app2container/application-modernization-app2container.md
- [ ] **Architecting Global EKS Resilience with Cross-Region Networking** — *expert*, ~240 min | EKS, Transit Gateway, Route 53, VPC Lattice
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/architecting-global-eks-resilience/architecting-global-eks-resilience.md
- [ ] **Asynchronous API Patterns with SQS** — *expert*, ~180 min | API Gateway, SQS, Lambda, DynamoDB
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/async-api-patterns-gateway-sqs/async-api-patterns-gateway-sqs.md
- [ ] **Cost-Effective ECS Clusters with Spot Instances** — *expert*, ~180 min | ECS, EC2, Auto Scaling, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cost-effective-ecs-spot/cost-effective-ecs-spot.md
- [ ] **Custom CloudFormation Resources with Lambda** — *expert*, ~180 min | cloudformation, lambda, iam, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/custom-cloudformation-resources-lambda/custom-cloudformation-resources-lambda.md
- [ ] **Developing APIs with SAM and API Gateway** — *expert*, ~180 min | SAM, API Gateway, Lambda, DynamoDB
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/developing-apis-with-sam/developing-apis-with-sam.md
- [ ] **Developing Offline-First Mobile Applications with Amplify DataStore** — *expert*, ~180 min | amplify, appsync, dynamodb, cognito
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/offline-first-mobile-applications-amplify-datastore/offline-first-mobile-applications-amplify-datastore.md
- [ ] **EKS Ingress with AWS Load Balancer Controller** — *expert*, ~180 min | eks, elbv2, ec2, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/eks-ingress-alb-controller/eks-ingress-alb-controller.md
- [ ] **EKS Microservices with App Mesh Integration** — *expert*, ~180 min | EKS, App Mesh, ECR, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/eks-microservices-mesh/eks-microservices-mesh.md
- [ ] **EKS Microservices with App Mesh Service Mesh** — *expert*, ~180 min | eks, app-mesh, ecr, elastic-load-balancing
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/eks-app-mesh-microservices/eks-app-mesh-microservices.md
- [ ] **EKS Workload Auto Scaling** — *expert*, ~240 min | EKS, Auto Scaling, CloudWatch, EC2
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/eks-workload-auto-scaling/eks-workload-auto-scaling.md
- [ ] **Enterprise GraphQL API Architecture** — *expert*, ~180 min | appsync, dynamodb, lambda, opensearch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/enterprise-graphql-api/enterprise-graphql-api.md
- [ ] **Enterprise Server Migration with Application Migration Service** — *expert*, ~240 min | mgn, ec2, iam, vpc
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/enterprise-server-migration/enterprise-server-migration.md
- [ ] **Fault-Tolerant HPC with Step Functions** — *expert*, ~180 min | step-functions, ec2, batch, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/hpc-workflows/hpc-workflows.md
- [ ] **Implementing Real-Time Chat Applications with AppSync and GraphQL** — *expert*, ~180 min | appsync, dynamodb, cognito
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/real-time-chat-applications-appsync-graphql/real-time-chat-applications-appsync-graphql.md
- [ ] **Real-Time Apps with Amplify and AppSync** — *expert*, ~180 min | amplify, appsync, cognito, dynamodb
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/realtime-apps-amplify/realtime-apps-amplify.md
- [ ] **SageMaker ML Workflows with Step Functions** — *expert*, ~240 min | sagemaker, step-functions, s3, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/sagemaker-ml-workflows/sagemaker-ml-workflows.md
- [ ] **API Throttling and Rate Limiting with API Gateway and Lambda** — *intermediate*, ~60 min | API Gateway, CloudWatch, Lambda, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/api-throttling-rate-limiting/api-throttling-rate-limiting.md
- [ ] **Automated Data Analysis with Bedrock AgentCore Runtime** — *intermediate*, ~50 min | Bedrock AgentCore, Lambda, S3, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/automated-data-analysis-bedrock-agentcore/automated-data-analysis-bedrock-agentcore.md
- [ ] **Automated Report Generation with EventBridge Scheduler** — *intermediate*, ~60 min | EventBridge Scheduler, S3, Lambda, SES
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/automated-report-generation-eventbridge/automated-report-generation-eventbridge.md
- [ ] **Building Collaborative Task Management with Aurora DSQL** — *intermediate*, ~90 min | Aurora DSQL, EventBridge, Lambda, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/collaborative-task-management-aurora-dsql/collaborative-task-management-aurora-dsql.md
- [ ] **Business Task Scheduling with EventBridge** — *intermediate*, ~90 min | EventBridge Scheduler, Lambda, SNS, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/business-task-scheduling-eventbridge/business-task-scheduling-eventbridge.md
- [ ] **Container Health Checks and Self-Healing** — *intermediate*, ~85 min | ECS, CloudWatch, Lambda, Auto Scaling
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/container-health-checks-healing/container-health-checks-healing.md
- [ ] **Container Observability and Performance Monitoring** ⭐ — *intermediate*, ~100 min | ECS, CloudWatch, X-Ray, Prometheus
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/container-observability-monitoring/container-observability-monitoring.md
- [ ] **Container Registry Replication with ECR** — *intermediate*, ~70 min | ECR, Lambda, CloudWatch, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/container-registry-replication-ecr/container-registry-replication-ecr.md
- [ ] **Converting Text to Speech with Polly** — *intermediate*, ~60 min | polly, s3, lambda, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/converting-text-speech-polly/converting-text-speech-polly.md
- [ ] **Creating Contact Forms with SES and Lambda** — *intermediate*, ~60 min | SES, Lambda, API Gateway
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/creating-contact-forms-ses/creating-contact-forms-ses.md
- [ ] **Creating No-Code AI Applications with PartyRock and S3** — *intermediate*, ~60 min | PartyRock, S3, CloudFront
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/no-code-ai-applications-partyrock-s3/no-code-ai-applications-partyrock-s3.md
- [ ] **Dead Letter Queue Processing with SQS** — *intermediate*, ~45 min | SQS, Lambda, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/dead-letter-queue-sqs-lambda/dead-letter-queue-sqs-lambda.md
- [ ] **Delivering Scheduled Reports with App Runner and SES** — *intermediate*, ~90 min | App Runner, SES, EventBridge Scheduler, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/delivering-reports-with-app-runner/delivering-reports-with-app-runner.md
- [ ] **Deploying Fargate Containers with Application Load Balancer** ⭐ — *intermediate*, ~60 min | ECS, Fargate, ALB, ECR
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/deploying-fargate-containers-alb/deploying-fargate-containers-alb.md
- [ ] **Document Auto-Summarization with Bedrock** — *intermediate*, ~45 min | Bedrock, Lambda, S3, Textract
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/document-auto-summarization/document-auto-summarization.md
- [ ] **Document Processing Pipelines with Textract** — *intermediate*, ~90 min | textract, step-functions, s3, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/document-processing-textract-pipelines/document-processing-textract-pipelines.md
- [ ] **Dynamic Configuration with Parameter Store** — *intermediate*, ~90 min | Systems Manager Parameter Store, Lambda, CloudWatch, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/dynamic-configuration-parameter-store/dynamic-configuration-parameter-store.md
- [ ] **EC2 Fleet Management with Spot Instances** — *intermediate*, ~60 min | EC2, Spot Fleet, CloudWatch, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/ec2-fleet-management-spot/ec2-fleet-management-spot.md
- [ ] **EC2 Hibernate for Cost Optimization** — *intermediate*, ~45 min | ec2, cloudwatch, sns
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/ec2-hibernate-cost-optimization/ec2-hibernate-cost-optimization.md
- [ ] **ECS Task Environment Variable Management** — *intermediate*, ~90 min | ECS, Systems Manager, S3, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/ecs-task-environment-variables/ecs-task-environment-variables.md
- [ ] **EKS Monitoring with CloudWatch Container Insights** — *intermediate*, ~45 min | eks, cloudwatch, sns
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/eks-monitoring-cloudwatch-insights/eks-monitoring-cloudwatch-insights.md
- [ ] **Email Marketing Campaigns with SES** — *intermediate*, ~60 min | amazon-ses, amazon-sns, amazon-s3, amazon-cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/email-marketing-campaigns-ses/email-marketing-campaigns-ses.md
- [ ] **Email Notification Automation with SES** — *intermediate*, ~90 min | SES, Lambda, EventBridge, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/email-notification-automation-ses/email-notification-automation-ses.md
- [ ] **Enterprise API Integration with AgentCore Gateway and Step Functions** — *intermediate*, ~45 min | Amazon Bedrock AgentCore Gateway, Step Functions, Lambda, API Gateway
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/api-integration-agentcore-gateway/api-integration-agentcore-gateway.md
- [ ] **Event-Driven Architecture with EventBridge** — *intermediate*, ~45 min | eventbridge, lambda, sns, sqs
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/eventbridge-architecture/eventbridge-architecture.md
- [ ] **Event-Driven Microservices with EventBridge Routing** — *intermediate*, ~90 min | eventbridge, lambda, sqs, sns
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/eventbridge-microservices/eventbridge-microservices.md
- [ ] **Implementing Predictive Scaling for EC2 with Auto Scaling and Machine Learning** — *intermediate*, ~60 min | autoscaling, cloudwatch, ec2, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/predictive-scaling-ec2-autoscaling-ml/predictive-scaling-ec2-autoscaling-ml.md
- [ ] **Interactive Business Process Automation with Bedrock AgentCore and EventBridge** — *intermediate*, ~45 min | Bedrock, EventBridge, Lambda, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/business-process-automation-agentcore-eventbridge/business-process-automation-agentcore-eventbridge.md
- [ ] **Lambda Safe Deployments with Blue-Green and Canary** ⭐ — *intermediate*, ~60 min | lambda, api-gateway, cloudwatch, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/lambda-safe-deployments/lambda-safe-deployments.md
- [ ] **Mixed Instance Auto Scaling Groups** — *intermediate*, ~60 min | EC2, Auto Scaling, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/mixed-instance-auto-scaling/mixed-instance-auto-scaling.md
- [ ] **Optimizing HPC Workloads with AWS Batch and Spot Instances** — *intermediate*, ~90 min | AWS Batch, EC2 Spot Instances, CloudWatch, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/optimizing-hpc-workloads-batch-spot/optimizing-hpc-workloads-batch-spot.md
- [ ] **Performance Monitoring AI Agents with AgentCore and CloudWatch** — *intermediate*, ~45 min | Bedrock AgentCore, CloudWatch, Lambda, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/performance-monitoring-agentcore-cloudwatch/performance-monitoring-agentcore-cloudwatch.md
- [ ] **Processing Event-Driven Streams with Kinesis and Lambda** — *intermediate*, ~90 min | Kinesis, Lambda, DynamoDB, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/event-driven-stream-processing/event-driven-stream-processing.md
- [ ] **Running Containers with AWS Fargate** ⭐ — *intermediate*, ~45 min | ECS, Fargate, ECR, Application Auto Scaling
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/running-containers-fargate/running-containers-fargate.md
- [ ] **SNS Message Fan-out with Multiple SQS Queues** — *intermediate*, ~45 min | sns, sqs, iam, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/sns-message-fanout/sns-message-fanout.md
- [ ] **Scheduling Notifications with EventBridge and SNS** — *intermediate*, ~60 min | EventBridge Scheduler, SNS, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/scheduling-notifications-eventbridge/scheduling-notifications-eventbridge.md
- [ ] **Secure EC2 Management with Systems Manager** — *intermediate*, ~45 min | EC2, Systems Manager, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/ec2-secure-management-ssm/ec2-secure-management-ssm.md
- [ ] **Securing APIs with Lambda Authorizers and API Gateway** ⭐ — *intermediate*, ~90 min | API Gateway, Lambda, IAM, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/securing-apis-lambda-authorizers/securing-apis-lambda-authorizers.md
- [ ] **Self-Managed Kubernetes Integration with VPC Lattice IP Targets** — *intermediate*, ~45 min | VPC Lattice, EC2, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/kubernetes-integration-lattice-ip/kubernetes-integration-lattice-ip.md
- [ ] **Serverless GraphQL APIs with AppSync and Scheduler** — *intermediate*, ~90 min | AWS AppSync, EventBridge Scheduler, DynamoDB, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/serverless-graphql-apis/serverless-graphql-apis.md
- [ ] **Standardized Service Deployment with VPC Lattice and Service Catalog** — *intermediate*, ~45 min | VPC Lattice, Service Catalog, CloudFormation, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/standardized-service-deployment-lattice-catalog/standardized-service-deployment-lattice-catalog.md
- [ ] **Step Functions Microservices Orchestration** — *intermediate*, ~90 min | Step Functions, Lambda, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/step-functions-orchestration/step-functions-orchestration.md
- [ ] **URL Shortener Service with Lambda** — *intermediate*, ~90 min | Lambda, DynamoDB, API Gateway, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/url-shortener-lambda-dynamodb/url-shortener-lambda-dynamodb.md

### Databases & Analytics (89)

- [ ] **Analytics-Optimized S3 Tables Storage** — *advanced*, ~120 min | S3 Tables, Amazon Athena, AWS Glue, Amazon QuickSight
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/analytics-optimized-s3-tables/analytics-optimized-s3-tables.md
- [ ] **Analyzing Operational Data with CloudWatch Insights** — *advanced*, ~120 min | cloudwatch, lambda, sns, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/operational-analytics-cloudwatch-insights/operational-analytics-cloudwatch-insights.md
- [ ] **Analyzing Time-Series Data with Timestream** — *advanced*, ~120 min | timestream, lambda, iot-core, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/analyzing-timeseries-data-timestream/analyzing-timeseries-data-timestream.md
- [ ] **Architecting Distributed Database Applications with Aurora DSQL** — *advanced*, ~120 min | Aurora DSQL, Lambda, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/architecting-distributed-database-applications/architecting-distributed-database-applications.md
- [ ] **Aurora Migration with Minimal Downtime** — *advanced*, ~120 min | dms, aurora, route53, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/aurora-migration-minimal-downtime/aurora-migration-minimal-downtime.md
- [ ] **Bedrock Multi-Agent AI Workflows with AgentCore** — *advanced*, ~120 min | Amazon Bedrock, Amazon EventBridge, AWS Lambda, DynamoDB
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/bedrock-multi-agent-ai/bedrock-multi-agent-ai.md
- [ ] **Business Intelligence Solutions with QuickSight** — *advanced*, ~120 min | QuickSight, S3, Athena, Redshift
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/business-intelligence-solutions-quicksight/business-intelligence-solutions-quicksight.md
- [ ] **Carbon Footprint Analytics with QuickSight** — *advanced*, ~120 min | AWS Customer Carbon Footprint Tool, Amazon QuickSight, AWS Cost Explorer, AWS Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/carbon-footprint-analytics/carbon-footprint-analytics.md
- [ ] **CloudWatch Log Analytics with Insights** — *advanced*, ~120 min | CloudWatch Logs, Lambda, SNS, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cloudwatch-log-analytics/cloudwatch-log-analytics.md
- [ ] **Cost-Optimized Analytics with S3 Tiering** — *advanced*, ~120 min | S3, Athena, Glue, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cost-optimized-analytics-s3/cost-optimized-analytics-s3.md
- [ ] **Data Catalog Governance with AWS Glue** — *advanced*, ~120 min | glue, lake-formation, cloudtrail, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-catalog-governance-glue/data-catalog-governance-glue.md
- [ ] **Data Governance Pipelines with DataZone** — *advanced*, ~120 min | DataZone, Config, EventBridge, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-governance-datazone-config/data-governance-datazone-config.md
- [ ] **Data Lake Architectures with S3 and Glue** — *advanced*, ~120 min | S3, Glue, Athena, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-lake-s3-glue-athena/data-lake-s3-glue-athena.md
- [ ] **Data Pipeline Orchestration with Glue Workflows** — *advanced*, ~120 min | glue, s3, iam, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-pipeline-orchestration-glue/data-pipeline-orchestration-glue.md
- [ ] **Data Quality Monitoring with DataBrew** — *advanced*, ~120 min | glue-databrew, s3, cloudwatch, eventbridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-quality-monitoring-databrew/data-quality-monitoring-databrew.md
- [ ] **Data Quality Pipelines with DataBrew** — *advanced*, ~120 min | AWS Glue DataBrew, Amazon EventBridge, Amazon S3, AWS Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-quality-pipelines-databrew/data-quality-pipelines-databrew.md
- [ ] **Data Warehousing Solutions with Redshift** — *advanced*, ~120 min | redshift, s3, iam, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-warehousing-redshift/data-warehousing-redshift.md
- [ ] **Database Backup and Recovery with RDS** — *advanced*, ~120 min | rds, backup, kms, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/database-backup-recovery-rds/database-backup-recovery-rds.md
- [ ] **Database Monitoring Dashboards with CloudWatch** — *advanced*, ~120 min | cloudwatch, rds, sns, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/database-monitoring-cloudwatch/database-monitoring-cloudwatch.md
- [ ] **Database Performance Monitoring with RDS Insights** — *advanced*, ~120 min | rds, cloudwatch, lambda, sns
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/database-performance-monitoring-rds/database-performance-monitoring-rds.md
- [ ] **Database Performance Tuning with Parameters** — *advanced*, ~120 min | rds, cloudwatch, performance-insights, ec2
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/database-performance-tuning-parameters/database-performance-tuning-parameters.md
- [ ] **Database Query Caching with ElastiCache** — *advanced*, ~120 min | elasticache, rds, vpc, ec2
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/database-query-caching-elasticache/database-query-caching-elasticache.md
- [ ] **Detecting Real-time Anomalies with Kinesis Data Analytics** — *advanced*, ~120 min | kinesis-data-streams, managed-service-for-apache-flink, cloudwatch, sns
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/real-time-anomaly-detection-kinesis-flink/real-time-anomaly-detection-kinesis-flink.md
- [ ] **Developing Distributed Serverless Applications with Aurora DSQL** — *advanced*, ~120 min | Aurora DSQL, Lambda, API Gateway, Route 53
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/developing-distributed-serverless-applications/developing-distributed-serverless-applications.md
- [ ] **Document Processing Pipelines with Textract and Step Functions** — *advanced*, ~120 min | Textract, Step Functions, S3, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/document-processing-textract-stepfunctions/document-processing-textract-stepfunctions.md
- [ ] **DynamoDB Global Tables for Multi-Region Apps** ⭐ — *advanced*, ~120 min | dynamodb, cloudwatch, iam, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/dynamodb-global-tables-multiregion/dynamodb-global-tables-multiregion.md
- [ ] **ETL Pipelines with Glue Data Catalog** — *advanced*, ~120 min | glue, s3, athena, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/glue-etl-catalog/glue-etl-catalog.md
- [ ] **Establishing Database High Availability with Multi-AZ Deployments** — *advanced*, ~120 min | rds, vpc, cloudwatch, systems-manager
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/establishing-database-high-availability/establishing-database-high-availability.md
- [ ] **IoT Dashboard Visualization with QuickSight** — *advanced*, ~120 min | iot-core, kinesis, s3, quicksight
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iot-dashboard-visualization/iot-dashboard-visualization.md
- [ ] **Monitoring Data Quality with Deequ on EMR** — *advanced*, ~120 min | emr, s3, cloudwatch, sns
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-quality-monitoring-deequ/data-quality-monitoring-deequ.md
- [ ] **Multi-Region Disaster Recovery with Aurora DSQL** ⭐ — *advanced*, ~120 min | Aurora DSQL, EventBridge, Lambda, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/multi-region-dr-aurora-dsql/multi-region-dr-aurora-dsql.md
- [ ] **OpenSearch Data Ingestion Pipelines** — *advanced*, ~120 min | OpenSearch Ingestion, EventBridge Scheduler, S3, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-ingestion-opensearch-eventbridge/data-ingestion-opensearch-eventbridge.md
- [ ] **Privacy-Preserving Analytics with Clean Rooms** — *advanced*, ~120 min | Clean Rooms, QuickSight, S3, Glue
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/privacy-preserving-analytics-cleanrooms/privacy-preserving-analytics-cleanrooms.md
- [ ] **Processing Data with AWS Glue and Lambda** — *advanced*, ~150 min | AWS Glue, Lambda, S3, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/processing-data-glue-lambda/processing-data-glue-lambda.md
- [ ] **Processing Streaming Data with Kinesis Data Firehose** — *advanced*, ~120 min | Kinesis, Lambda, S3, OpenSearch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/streaming-data-processing-firehose/streaming-data-processing-firehose.md
- [ ] **Querying Data Across Sources with Athena** — *advanced*, ~120 min | athena, lambda, s3, rds
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/querying-data-across-sources-with-athena/querying-data-across-sources-with-athena.md
- [ ] **Simulating Cities with SimSpace Weaver and IoT** — *advanced*, ~120 min | SimSpace Weaver, IoT Core, DynamoDB, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/simulating-cities-simspace-weaver/simulating-cities-simspace-weaver.md
- [ ] **Streaming Analytics with Kinesis and Lambda** — *advanced*, ~120 min | kinesis, lambda, dynamodb, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/streaming-analytics-kinesis-lambda/streaming-analytics-kinesis-lambda.md
- [ ] **Streaming Data Enrichment with Kinesis and Lambda** — *advanced*, ~120 min | kinesis, lambda, dynamodb, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-enrichment-kinesis-lambda/data-enrichment-kinesis-lambda.md
- [ ] **Synchronizing Real-time Data with AWS AppSync** — *advanced*, ~120 min | appsync, dynamodb, iam, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/real-time-sync-appsync/real-time-sync-appsync.md
- [ ] **ACID-Compliant Distributed Databases with Amazon QLDB** — *expert*, ~240 min | QLDB, IAM, S3, Kinesis
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/acid-compliant-distributed-databases/acid-compliant-distributed-databases.md
- [ ] **ACID-Compliant Ledger Database with QLDB** — *expert*, ~210 min | QLDB, IAM, S3, Kinesis
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/acid-compliant-ledger-qldb/acid-compliant-ledger-qldb.md
- [ ] **Analyzing Streaming Data with EMR on EKS and Flink** — *expert*, ~180 min | EMR, EKS, Kinesis, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/streaming-analytics-emr-eks-flink/streaming-analytics-emr-eks-flink.md
- [ ] **Aurora Serverless Cost Optimization Patterns** — *expert*, ~180 min | Aurora Serverless v2, CloudWatch, RDS, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/aurora-serverless-cost-optimization/aurora-serverless-cost-optimization.md
- [ ] **Cross-Account Data Sharing with Data Exchange** — *expert*, ~180 min | Data Exchange, S3, IAM, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cross-account-data-sharing-exchange/cross-account-data-sharing-exchange.md
- [ ] **Data Lake Architectures with Lake Formation** — *expert*, ~180 min | s3, lakeformation, glue, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-lake-s3-lakeformation/data-lake-s3-lakeformation.md
- [ ] **Data Lake Fine-Grained Access Control with Lake Formation** — *expert*, ~180 min | Lake Formation, Glue, IAM, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-lake-fine-grained-access/data-lake-fine-grained-access.md
- [ ] **Data Lake Governance with Lake Formation** — *expert*, ~240 min | Lake Formation, DataZone, S3, Glue
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-lake-governance-formation/data-lake-governance-formation.md
- [ ] **Data Lake Ingestion Pipelines with Glue** — *expert*, ~240 min | AWS Glue, S3, IAM, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-lake-ingestion-glue/data-lake-ingestion-glue.md
- [ ] **Data Visualization Pipelines with QuickSight** — *expert*, ~180 min | QuickSight, S3, Athena, Glue
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-visualization-quicksight-s3/data-visualization-quicksight-s3.md
- [ ] **Database Disaster Recovery with Read Replicas** — *expert*, ~240 min | RDS, CloudWatch, SNS, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/database-dr-cross-region/database-dr-cross-region.md
- [ ] **Database Migration Strategies with DMS** — *expert*, ~180 min | dms, rds, vpc, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/database-migration-strategies-dms/database-migration-strategies-dms.md
- [ ] **Database Migration with AWS DMS** — *expert*, ~180 min | dms, rds, vpc, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/database-migration-dms/database-migration-dms.md
- [ ] **Database Migration with Schema Conversion Tool** — *expert*, ~180 min | dms, sct, rds, ec2
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/database-migration-sct-dms/database-migration-sct-dms.md
- [ ] **Deploying Global Database Replication with Aurora Global Database** — *expert*, ~240 min | aurora, rds, cloudwatch, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/deploying-global-database-replication/deploying-global-database-replication.md
- [ ] **DynamoDB Global Tables with Streaming** — *expert*, ~180 min | DynamoDB, Kinesis Data Streams, Lambda, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/dynamodb-global-streaming/dynamodb-global-streaming.md
- [ ] **Enabling Operational Analytics with Amazon Redshift Spectrum** — *expert*, ~180 min | Redshift, S3, Glue, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/operational-analytics-amazon-redshift-spectrum/operational-analytics-amazon-redshift-spectrum.md
- [ ] **Financial Analytics Dashboard with QuickSight** — *expert*, ~300 min | QuickSight, Cost Explorer, S3, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/financial-analytics-dashboard-quicksight/financial-analytics-dashboard-quicksight.md
- [ ] **Graph-Based Recommendation Engine** — *expert*, ~180 min | neptune, vpc, ec2, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/graph-based-recommendation-system/graph-based-recommendation-system.md
- [ ] **Implementing Enterprise Search with OpenSearch Service** — *expert*, ~240 min | OpenSearch Service, Lambda, S3, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/implementing-enterprise-search-with-opensearch/implementing-enterprise-search-with-opensearch.md
- [ ] **Implementing Real-Time Analytics with Amazon Kinesis Data Streams** — *expert*, ~180 min | kinesis, lambda, cloudwatch, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/real-time-analytics-kinesis-data-streams/real-time-analytics-kinesis-data-streams.md
- [ ] **Multi-AZ PostgreSQL Cluster** — *expert*, ~180 min | rds, cloudwatch, sns, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/multi-az-postgresql-cluster/multi-az-postgresql-cluster.md
- [ ] **Oracle to PostgreSQL Migration with DMS** — *expert*, ~300 min | DMS, RDS, Aurora PostgreSQL, Schema Conversion Tool
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/oracle-postgresql-migration-dms/oracle-postgresql-migration-dms.md
- [ ] **Processing IoT Analytics with Kinesis and Flink** — *expert*, ~180 min | kinesis, kinesisanalyticsv2, lambda, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iot-analytics-kinesis-flink/iot-analytics-kinesis-flink.md
- [ ] **RDS Multi-Region Failover Strategy** — *expert*, ~240 min | RDS, Route 53, CloudWatch, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/rds-multi-region-failover/rds-multi-region-failover.md
- [ ] **Redshift Analytics Workload Isolation** — *expert*, ~180 min | Redshift, CloudWatch, IAM, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/redshift-workload-isolation/redshift-workload-isolation.md
- [ ] **SageMaker AutoML for Time Series Forecasting** — *expert*, ~180 min | sagemaker, s3, iam, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/sagemaker-automl-forecasting/sagemaker-automl-forecasting.md
- [ ] **Serverless Data Lake Architecture** — *expert*, ~300 min | Lambda, Glue, EventBridge, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/serverless-data-lake-architecture/serverless-data-lake-architecture.md
- [ ] **Streaming Clickstream Analytics with Kinesis Data Streams** — *expert*, ~180 min | Kinesis Data Streams, Lambda, DynamoDB, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/streaming-clickstream-analytics-kinesis/streaming-clickstream-analytics-kinesis.md
- [ ] **Analytics-Ready S3 Tables Storage** — *intermediate*, ~75 min | S3, S3 Tables, Athena, Glue
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/analytics-ready-s3-tables/analytics-ready-s3-tables.md
- [ ] **Architecting NoSQL Databases with DynamoDB Global Tables** — *intermediate*, ~90 min | DynamoDB, IAM, CloudWatch, KMS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/nosql-database-architectures-dynamodb-global-tables/nosql-database-architectures-dynamodb-global-tables.md
- [ ] **Building Real-time Analytics Dashboards with Kinesis Analytics and QuickSight** — *intermediate*, ~90 min | Kinesis Data Streams, Managed Service for Apache Flink, QuickSight, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/real-time-analytics-dashboards-kinesis-quicksight/real-time-analytics-dashboards-kinesis-quicksight.md
- [ ] **Business Intelligence Dashboards with QuickSight** — *intermediate*, ~90 min | QuickSight, S3, IAM, RDS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/business-intelligence-quicksight-dashboards/business-intelligence-quicksight-dashboards.md
- [ ] **Computer Vision Applications with Rekognition** — *intermediate*, ~75 min | Rekognition, S3, Lambda, Kinesis
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/computer-vision-rekognition-apps/computer-vision-rekognition-apps.md
- [ ] **Computer Vision Solutions with Rekognition** — *intermediate*, ~75 min | Rekognition, S3, Lambda, DynamoDB
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/computer-vision-solutions-rekognition/computer-vision-solutions-rekognition.md
- [ ] **Database Connection Pooling with RDS Proxy** — *intermediate*, ~90 min | rds-proxy, rds, lambda, secrets-manager
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/database-connection-pooling-rds/database-connection-pooling-rds.md
- [ ] **Database Scaling with Aurora Serverless** — *intermediate*, ~60 min | rds, aurora, cloudwatch, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/database-scaling-aurora-serverless/database-scaling-aurora-serverless.md
- [ ] **Global E-commerce with Distributed SQL** — *intermediate*, ~90 min | Aurora DSQL, API Gateway, Lambda, CloudFront
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/distributed-sql-ecommerce-platform/distributed-sql-ecommerce-platform.md
- [ ] **HIPAA-Compliant Healthcare Analytics** — *intermediate*, ~90 min | HealthLake, Lambda, S3, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/hipaa-compliant-healthcare-analytics/hipaa-compliant-healthcare-analytics.md
- [ ] **Intelligent Web Scraping with AgentCore Browser and Code Interpreter** — *intermediate*, ~60 min | Bedrock AgentCore, Lambda, S3, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/intelligent-web-scraping-browser-codeinterpreter/intelligent-web-scraping-browser-codeinterpreter.md
- [ ] **Interactive Data Analytics with Bedrock AgentCore Code Interpreter** — *intermediate*, ~45 min | Bedrock, S3, Lambda, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/interactive-data-analytics-bedrock-codeinterpreter/interactive-data-analytics-bedrock-codeinterpreter.md
- [ ] **IoT Telemetry Analytics with Kinesis and Timestream** — *intermediate*, ~90 min | IoT Core, Kinesis, Timestream, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iot-telemetry-analytics/iot-telemetry-analytics.md
- [ ] **Optimizing Amazon Redshift Performance** — *intermediate*, ~90 min | redshift, cloudwatch, sns, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/redshift-performance-optimization/redshift-performance-optimization.md
- [ ] **RDS Disaster Recovery Solutions** — *intermediate*, ~90 min | RDS, EventBridge, SNS, Lambda, +1 more
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/disaster-recovery-rds/disaster-recovery-rds.md
- [ ] **Real-Time Stream Enrichment with Kinesis and EventBridge** — *intermediate*, ~90 min | Kinesis Data Streams, EventBridge Pipes, Lambda, DynamoDB
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/real-time-stream-enrichment/real-time-stream-enrichment.md
- [ ] **Serverless Medical Image Processing with HealthImaging** — *intermediate*, ~90 min | AWS HealthImaging, Step Functions, Lambda, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/serverless-medical-image-processing/serverless-medical-image-processing.md
- [ ] **Service Performance Cost Analytics with VPC Lattice and CloudWatch Insights** — *intermediate*, ~45 min | VPC Lattice, CloudWatch Insights, Cost Explorer, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/service-performance-cost-analytics-lattice-insights/service-performance-cost-analytics-lattice-insights.md
- [ ] **Streaming ETL with Kinesis Data Firehose** — *intermediate*, ~90 min | kinesis-firehose, lambda, s3, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/streaming-etl-firehose/streaming-etl-firehose.md
- [ ] **Transforming Data with Kinesis Data Firehose** — *intermediate*, ~45 min | Kinesis Data Firehose, Lambda, S3, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-transformation-firehose/data-transformation-firehose.md

### Networking & Content Delivery (42)

- [ ] **CloudFront Cache Invalidation Strategies** — *advanced*, ~120 min | CloudFront, Lambda, S3, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cloudfront-cache-invalidation-strategies/cloudfront-cache-invalidation-strategies.md
- [ ] **Content Delivery Networks with CloudFront S3** — *advanced*, ~150 min | CloudFront, S3, Route 53, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cdn-cloudfront-s3/cdn-cloudfront-s3.md
- [ ] **DNS-Based Load Balancing with Route 53** — *advanced*, ~120 min | route53, ec2, elb
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/dns-load-balancing-route53/dns-load-balancing-route53.md
- [ ] **Dedicated Hybrid Cloud Connectivity** — *advanced*, ~120 min | direct-connect, vpc, transit-gateway, route-53
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/dedicated-network-connectivity/dedicated-network-connectivity.md
- [ ] **Hosting Websites with S3 CloudFront and Route 53** — *advanced*, ~120 min | s3, cloudfront, route53, acm
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/hosting-websites-s3-cloudfront/hosting-websites-s3-cloudfront.md
- [ ] **Intelligent Global Traffic Routing with Route53 and CloudFront** — *advanced*, ~120 min | route53, cloudfront, alb, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/intelligent-traffic-routing/intelligent-traffic-routing.md
- [ ] **Low-Latency Edge Applications with Wavelength** — *advanced*, ~150 min | AWS Wavelength, Amazon CloudFront, Amazon EC2, Amazon Route 53
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/low-latency-edge-wavelength/low-latency-edge-wavelength.md
- [ ] **Managing Enterprise VPC Architectures with Transit Gateway** — *advanced*, ~120 min | transit-gateway, vpc, route-53, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/managing-enterprise-vpc-architectures/managing-enterprise-vpc-architectures.md
- [ ] **Monitoring Network Traffic with VPC Flow Logs** — *advanced*, ~120 min | vpc, cloudwatch, s3, athena
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/network-monitoring-vpc-flow-logs/network-monitoring-vpc-flow-logs.md
- [ ] **Site-to-Site VPN Connections with AWS** — *advanced*, ~120 min | VPN, VPC, EC2, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/site-to-site-vpn/site-to-site-vpn.md
- [ ] **Virtual Desktop Infrastructure with WorkSpaces** — *advanced*, ~120 min | workspaces, ds, vpc, ec2
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/workforce-productivity-workspaces/workforce-productivity-workspaces.md
- [ ] **Auto Scaling with Load Balancers** — *expert*, ~180 min | Application Load Balancer, Auto Scaling, EC2, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/auto-scaling-alb-target-groups/auto-scaling-alb-target-groups.md
- [ ] **Connecting Multi-Region Networks with Transit Gateway** ⭐ — *expert*, ~180 min | transit-gateway, vpc, cloudwatch, ec2
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/connecting-multi-region-networks/connecting-multi-region-networks.md
- [ ] **Content Delivery Networks with CloudFront** — *expert*, ~200 min | CloudFront, S3, Lambda, WAF
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/content-delivery-networks-cloudfront/content-delivery-networks-cloudfront.md
- [ ] **Designing Advanced VPC Peering with Complex Routing Scenarios** — *expert*, ~240 min | VPC, Route Tables, Route 53, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/designing-advanced-vpc-peering/designing-advanced-vpc-peering.md
- [ ] **Securing Networks with Micro-Segmentation using NACLs and Security Groups** ⭐ — *expert*, ~180 min | VPC, EC2, CloudWatch, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/securing-networks-with-micro-segmentation/securing-networks-with-micro-segmentation.md
- [ ] **Zero Trust Network with VPC Endpoints** — *expert*, ~180 min | VPC, PrivateLink, Route53, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/zero-trust-vpc-privatelink/zero-trust-vpc-privatelink.md
- [ ] **API Gateway with Custom Domain Names** — *intermediate*, ~90 min | API Gateway, Route 53, ACM, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/api-gateway-custom-domains/api-gateway-custom-domains.md
- [ ] **Advanced Request Routing with VPC Lattice and ALB** — *intermediate*, ~45 min | VPC Lattice, Application Load Balancer, EC2
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/advanced-request-routing-lattice-alb/advanced-request-routing-lattice-alb.md
- [ ] **Application Health Monitoring with VPC Lattice and CloudWatch** — *intermediate*, ~45 min | VPC Lattice, CloudWatch, Lambda, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/application-health-monitoring-lattice-cloudwatch/application-health-monitoring-lattice-cloudwatch.md
- [ ] **Automated Service Lifecycle with VPC Lattice and EventBridge** — *intermediate*, ~45 min | VPC Lattice, EventBridge, Lambda, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/automated-service-lifecycle-lattice-eventbridge/automated-service-lifecycle-lattice-eventbridge.md
- [ ] **Blue-Green Deployments with VPC Lattice and Lambda** — *intermediate*, ~45 min | VPC Lattice, Lambda, CloudWatch, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/blue-green-deployments-lattice-lambda/blue-green-deployments-lattice-lambda.md
- [ ] **Building Global Active-Active Architecture with AWS Global Accelerator** — *intermediate*, ~90 min | GlobalAccelerator, DynamoDB, Lambda, ApplicationLoadBalancer
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/building-global-active-active-architecture/building-global-active-active-architecture.md
- [ ] **CDN with CloudFront Origin Access Controls** — *intermediate*, ~75 min | CloudFront, S3, WAF, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cdn-cloudfront-origin-access/cdn-cloudfront-origin-access.md
- [ ] **Canary Deployments with VPC Lattice and Lambda** — *intermediate*, ~45 min | VPC Lattice, Lambda, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/canary-deployments-lattice-lambda/canary-deployments-lattice-lambda.md
- [ ] **CloudFront Real-Time Monitoring and Analytics** — *intermediate*, ~90 min | CloudFront, Kinesis, Lambda, OpenSearch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cloudfront-realtime-monitoring/cloudfront-realtime-monitoring.md
- [ ] **Cross-Account Database Sharing with VPC Lattice and RDS** — *intermediate*, ~45 min | VPC Lattice, RDS, IAM, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cross-account-database-sharing-lattice-rds/cross-account-database-sharing-lattice-rds.md
- [ ] **Cross-Account Service Discovery with VPC Lattice and ECS** — *intermediate*, ~45 min | VPC Lattice, ECS, EventBridge, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cross-account-service-discovery-lattice-ecs/cross-account-service-discovery-lattice-ecs.md
- [ ] **Cross-Region Service Failover with VPC Lattice and Route53** — *intermediate*, ~90 min | VPC Lattice, Route53, Lambda, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cross-region-service-failover-lattice-route53/cross-region-service-failover-lattice-route53.md
- [ ] **Distributed Service Tracing with VPC Lattice and X-Ray** — *intermediate*, ~45 min | VPC Lattice, X-Ray, Lambda, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/distributed-service-tracing-lattice-xray/distributed-service-tracing-lattice-xray.md
- [ ] **Distributed Session Management with MemoryDB** — *intermediate*, ~90 min | MemoryDB, Application Load Balancer, ECS, Systems Manager
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/session-management-memorydb-alb/session-management-memorydb-alb.md
- [ ] **Elastic Load Balancing with ALB and NLB** — *intermediate*, ~60 min | alb, nlb, ec2, target, +1 more
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/elastic-load-balancing-alb-nlb/elastic-load-balancing-alb-nlb.md
- [ ] **Enterprise Oracle Database Connectivity with VPC Lattice and S3** — *intermediate*, ~50 min | VPC Lattice, Oracle Database@AWS, S3, Redshift
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/enterprise-oracle-connectivity-lattice-s3/enterprise-oracle-connectivity-lattice-s3.md
- [ ] **Multi-Tenant Resource Sharing with VPC Lattice and RAM** — *intermediate*, ~45 min | VPC Lattice, AWS RAM, RDS, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/multi-tenant-resource-sharing-lattice-ram/multi-tenant-resource-sharing-lattice-ram.md
- [ ] **Multi-Tier Content Caching with CloudFront and ElastiCache** — *intermediate*, ~90 min | CloudFront, ElastiCache, Lambda, API Gateway
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/content-caching-cloudfront-elasticache/content-caching-cloudfront-elasticache.md
- [ ] **Network Troubleshooting VPC Lattice with Network Insights** — *intermediate*, ~50 min | VPC Lattice, VPC Reachability Analyzer, CloudWatch, Systems Manager
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/network-troubleshooting-lattice-insights/network-troubleshooting-lattice-insights.md
- [ ] **Private API Integration with VPC Lattice and EventBridge** — *intermediate*, ~50 min | VPC Lattice, EventBridge, Step Functions, API Gateway
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/private-api-integration-lattice-eventbridge/private-api-integration-lattice-eventbridge.md
- [ ] **Secure Database Access with VPC Lattice and RDS** — *intermediate*, ~45 min | VPC Lattice, RDS, CloudWatch, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/secure-database-access-lattice-gateway/secure-database-access-lattice-gateway.md
- [ ] **Service Mesh Cost Analytics with VPC Lattice and Cost Explorer** — *intermediate*, ~45 min | VPC Lattice, Cost Explorer, CloudWatch, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/service-mesh-cost-analytics-lattice-explorer/service-mesh-cost-analytics-lattice-explorer.md
- [ ] **TCP Resource Connectivity with VPC Lattice and CloudWatch** — *intermediate*, ~45 min | VPC Lattice, RDS, CloudWatch, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/tcp-resource-connectivity-lattice-cloudwatch/tcp-resource-connectivity-lattice-cloudwatch.md
- [ ] **Traffic Analytics with VPC Lattice and OpenSearch** — *intermediate*, ~60 min | VPC Lattice, OpenSearch, Kinesis, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/traffic-analytics-lattice-opensearch/traffic-analytics-lattice-opensearch.md
- [ ] **gRPC Microservices with VPC Lattice and CloudWatch** — *intermediate*, ~45 min | VPC Lattice, CloudWatch, EC2
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/grpc-microservices-lattice-cloudwatch/grpc-microservices-lattice-cloudwatch.md

### Security & Identity (41)

- [ ] **Authenticating Users with Cognito User Pools** — *advanced*, ~120 min | cognito, iam, ses, sns
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/authenticating-users-cognito/authenticating-users-cognito.md
- [ ] **Automated Security Response with EventBridge** — *advanced*, ~120 min | eventbridge, lambda, security-hub, sns
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/security-automation/security-automation.md
- [ ] **Container Vulnerability Scanning with ECR** — *advanced*, ~150 min | ECR, Inspector, CloudWatch, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/container-vulnerability-scanning-ecr/container-vulnerability-scanning-ecr.md
- [ ] **Cross-Account Compliance Monitoring with Security Hub** — *advanced*, ~120 min | Systems Manager, Security Hub, CloudTrail, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/multi-account-compliance-monitoring/multi-account-compliance-monitoring.md
- [ ] **Cross-Account IAM Role Federation** — *advanced*, ~120 min | IAM, STS, CloudTrail, Organizations
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cross-account-iam-federation/cross-account-iam-federation.md
- [ ] **Data Encryption at Rest and in Transit** — *advanced*, ~120 min | kms, s3, rds, certificate-manager
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-encryption-rest-transit/data-encryption-rest-transit.md
- [ ] **Database Security with Encryption and IAM** — *advanced*, ~120 min | rds, kms, iam, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/database-security-encryption-iam/database-security-encryption-iam.md
- [ ] **Enterprise Authentication with Amplify and Identity Providers** — *advanced*, ~120 min | Amplify, Cognito, IAM, CloudFormation
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/enterprise-auth-amplify-idp/enterprise-auth-amplify-idp.md
- [ ] **Enterprise KMS Envelope Encryption** — *advanced*, ~120 min | kms, s3, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/enterprise-kms-envelope-encryption/enterprise-kms-envelope-encryption.md
- [ ] **Fine-Grained API Authorization with Verified Permissions** — *advanced*, ~120 min | verified-permissions, api-gateway, cognito, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/fine-grained-api-auth-verified/fine-grained-api-auth-verified.md
- [ ] **Fine-Grained Access Control with IAM** — *advanced*, ~120 min | iam, s3, cloudwatch, sts
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iam-access-control/iam-access-control.md
- [ ] **Governing Costs with Strategic Resource Tagging** — *advanced*, ~120 min | Config, Cost Explorer, Resource Groups, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/governing-costs-with-tagging/governing-costs-with-tagging.md
- [ ] **IoT Certificate Security with X.509 Authentication** — *advanced*, ~120 min | iot-core, iot-device-defender, iam, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iot-certificate-security/iot-certificate-security.md
- [ ] **Managing Secrets with Automated Rotation** — *advanced*, ~120 min | Secrets Manager, Lambda, IAM, KMS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/managing-secrets-with-rotation/managing-secrets-with-rotation.md
- [ ] **Multi-Account Resource Discovery Automation** — *advanced*, ~120 min | Resource Explorer, Config, EventBridge, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/multi-account-resource-discovery/multi-account-resource-discovery.md
- [ ] **Responding to Incidents with Security Hub** — *advanced*, ~150 min | Security Hub, EventBridge, Lambda, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/responding-to-incidents-with-security-hub/responding-to-incidents-with-security-hub.md
- [ ] **SSO with External Identity Providers** — *advanced*, ~120 min | IAM Identity Center, Organizations, CloudTrail, Identity Store
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/sso-external-identity-providers/sso-external-identity-providers.md
- [ ] **WAF Rate Limiting for Web Application Protection** — *advanced*, ~120 min | waf, cloudfront, application-load-balancer, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/waf-rate-limiting-rules/waf-rate-limiting-rules.md
- [ ] **Web Application Security with WAF Rules** — *advanced*, ~120 min | waf, cloudfront, alb, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/waf-rules-web-application-security/waf-rules-web-application-security.md
- [ ] **Centralized Identity Federation with IAM Identity Center** — *expert*, ~180 min | iam, identity-center, organizations, cloudtrail
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/centralized-identity-federation/centralized-identity-federation.md
- [ ] **Decentralized Identity Management with Blockchain** — *expert*, ~240 min | managed-blockchain, qldb, iam, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/decentralized-identity-blockchain/decentralized-identity-blockchain.md
- [ ] **EKS Multi-Tenant Security with Namespaces** ⭐ — *expert*, ~180 min | EKS, IAM, Kubernetes, VPC
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/eks-multitenant-security/eks-multitenant-security.md
- [ ] **Security Incident Response Automation** — *expert*, ~240 min | Security Hub, EventBridge, Lambda, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/security-incident-response-automation/security-incident-response-automation.md
- [ ] **Security Scanning Automation with Inspector** — *expert*, ~180 min | Inspector, Security Hub, EC2, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/security-scanning-automation-inspector/security-scanning-automation-inspector.md
- [ ] **Zero Trust Security Architecture with AWS** — *expert*, ~240 min | iam, identity, center, security, +3 more
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/zero-trust-security-architecture-aws/zero-trust-security-architecture-aws.md
- [ ] **API Security with WAF and Gateway** — *intermediate*, ~45 min | WAF, API Gateway, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/api-security-waf-gateway/api-security-waf-gateway.md
- [ ] **Accessing Instances with Session Manager** — *intermediate*, ~60 min | Systems Manager, EC2, IAM, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/accessing-instances-with-session-manager/accessing-instances-with-session-manager.md
- [ ] **Automated DNS Security Monitoring** — *intermediate*, ~90 min | Route 53 Resolver, CloudWatch, Lambda, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/dns-security-monitoring/dns-security-monitoring.md
- [ ] **Compliance Monitoring with AWS Config** — *intermediate*, ~85 min | Config, Lambda, SNS, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/compliance-monitoring-config/compliance-monitoring-config.md
- [ ] **Cross-Account Data Access with Lake Formation** — *intermediate*, ~90 min | Lake Formation, Glue, IAM, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cross-account-data-access-lakeformation/cross-account-data-access-lakeformation.md
- [ ] **Enterprise Identity Federation with Bedrock AgentCore** — *intermediate*, ~45 min | Bedrock, Cognito, IAM, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/enterprise-identity-federation-bedrock-agentcore/enterprise-identity-federation-bedrock-agentcore.md
- [ ] **Intelligent Cloud Threat Detection with GuardDuty** — *intermediate*, ~45 min | guardduty, eventbridge, sns, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/intelligent-threat-detection/intelligent-threat-detection.md
- [ ] **IoT Security Monitoring with Device Defender** — *intermediate*, ~90 min | iot, sns, cloudwatch, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iot-security-monitoring/iot-security-monitoring.md
- [ ] **Microservice Authorization with VPC Lattice and IAM** — *intermediate*, ~45 min | VPC Lattice, IAM, Lambda, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/microservice-authorization-lattice-iam/microservice-authorization-lattice-iam.md
- [ ] **SaaS Security Monitoring with AppFabric** — *intermediate*, ~90 min | AppFabric, EventBridge, Lambda, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/saas-security-monitoring-appfabric/saas-security-monitoring-appfabric.md
- [ ] **Secure Content Delivery with CloudFront WAF** — *intermediate*, ~90 min | CloudFront, WAF, S3, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/content-delivery-cloudfront-waf/content-delivery-cloudfront-waf.md
- [ ] **Secure SSH Access with EC2 Instance Connect** — *intermediate*, ~45 min | ec2, iam, cloudtrail
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/ec2-instance-connect-ssh/ec2-instance-connect-ssh.md
- [ ] **Securing Websites with SSL Certificates** — *intermediate*, ~45 min | Certificate Manager, CloudFront, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/securing-websites-with-ssl-certificates/securing-websites-with-ssl-certificates.md
- [ ] **Security Compliance Auditing with VPC Lattice and GuardDuty** — *intermediate*, ~45 min | VPC Lattice, GuardDuty, CloudWatch, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/security-compliance-auditing-lattice-guardduty/security-compliance-auditing-lattice-guardduty.md
- [ ] **Strengthening Authentication Security with IAM and MFA Devices** — *intermediate*, ~45 min | IAM, CloudTrail, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/strengthening-authentication-security/strengthening-authentication-security.md
- [ ] **Unified Identity Management System** — *intermediate*, ~90 min | Directory Service, WorkSpaces, RDS, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/unified-identity-management/unified-identity-management.md

### Storage & Data Management (33)

- [ ] **Backup and Archive Strategies with S3 Glacier** — *advanced*, ~120 min | S3, Glacier, IAM, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/backup-archive-s3-glacier-policies/backup-archive-s3-glacier-policies.md
- [ ] **Contact Center Solutions with Amazon Connect** — *advanced*, ~120 min | connect, s3, cloudwatch, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/contact-center-solutions-connect/contact-center-solutions-connect.md
- [ ] **DataSync Data Transfer Automation** — *advanced*, ~120 min | datasync, s3, iam, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/datasync-transfer-automation/datasync-transfer-automation.md
- [ ] **Distributed File Systems with EFS** — *advanced*, ~120 min | efs, ec2, vpc
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/distributed-filesystems-efs/distributed-filesystems-efs.md
- [ ] **EFS Mounting Strategies and Optimization** — *advanced*, ~120 min | efs, ec2, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/efs-mounting-strategies/efs-mounting-strategies.md
- [ ] **Enterprise Migration Assessment and Planning** — *advanced*, ~120 min | application-discovery-service, migration-hub, s3, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/enterprise-migration-assessment/enterprise-migration-assessment.md
- [ ] **Establishing Global Data Replication with S3 Cross-Region Replication** — *advanced*, ~120 min | s3, kms, iam, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/establishing-global-data-replication/establishing-global-data-replication.md
- [ ] **High-Throughput Shared Storage System** — *advanced*, ~120 min | fsx, ec2, s3, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/high-throughput-shared-storage/high-throughput-shared-storage.md
- [ ] **Monitoring S3 Access with CloudTrail and EventBridge** — *advanced*, ~120 min | s3, cloudtrail, cloudwatch, eventbridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/monitoring-s3-access-with-cloudtrail/monitoring-s3-access-with-cloudtrail.md
- [ ] **Replicating S3 Data Across Regions with Encryption** — *advanced*, ~120 min | s3, kms, iam, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/replicating-s3-data-across-regions/replicating-s3-data-across-regions.md
- [ ] **S3 Cross-Region Disaster Recovery** — *advanced*, ~120 min | s3, iam, cloudtrail, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/disaster-recovery-s3-replication/disaster-recovery-s3-replication.md
- [ ] **Seamless Hybrid Cloud Storage** — *advanced*, ~120 min | storage-gateway, s3, cloudwatch, kms
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/seamless-hybrid-storage/seamless-hybrid-storage.md
- [ ] **Application Discovery and Migration Assessment** — *expert*, ~180 min | Application Discovery Service, Migration Hub, S3, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/application-discovery-assessment/application-discovery-assessment.md
- [ ] **S3 Disaster Recovery Solutions** — *expert*, ~180 min | S3, CloudWatch, CloudTrail, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/disaster-recovery-solutions-s3/disaster-recovery-solutions-s3.md
- [ ] **Archiving Data with S3 Intelligent Tiering** — *intermediate*, ~90 min | s3, cloudwatch, cloudtrail
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/archiving-data-s3-intelligent-tiering/archiving-data-s3-intelligent-tiering.md
- [ ] **Automated Data Archiving with S3 Glacier** — *intermediate*, ~60 min | S3, Glacier, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-archiving-s3-glacier/data-archiving-s3-glacier.md
- [ ] **Automating Backups with S3 Lifecycle Policies** — *intermediate*, ~45 min | S3, EventBridge, Lambda, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/automating-backups-with-s3-lifecycle/automating-backups-with-s3-lifecycle.md
- [ ] **Automating File Processing with S3 Event Notifications** — *intermediate*, ~60 min | s3, lambda, sqs, sns
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/automating-file-processing-with-s3-events/automating-file-processing-with-s3-events.md
- [ ] **Automating Multi-Region Backup Strategies using AWS Backup** — *intermediate*, ~90 min | AWS Backup, EventBridge, IAM, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/automating-multi-region-backup-strategies-aws-backup/automating-multi-region-backup-strategies-aws-backup.md
- [ ] **Backup Strategies with S3 and Glacier** — *intermediate*, ~90 min | S3, Glacier, Lambda, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/backup-strategies-s3-glacier/backup-strategies-s3-glacier.md
- [ ] **Building File Portals with Transfer Family** — *intermediate*, ~90 min | Transfer Family, S3, IAM Identity Center, Access Grants
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/building-file-portals-with-transfer-family/building-file-portals-with-transfer-family.md
- [ ] **Data Archiving Solutions with S3 Lifecycle** — *intermediate*, ~60 min | s3, cloudwatch, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/data-archiving-s3-lifecycle/data-archiving-s3-lifecycle.md
- [ ] **EFS Performance Optimization and Monitoring** — *intermediate*, ~75 min | efs, cloudwatch, vpc, ec2
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/efs-performance-optimization/efs-performance-optimization.md
- [ ] **File Lifecycle Management with FSx** — *intermediate*, ~90 min | FSx, Lambda, CloudWatch, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/file-lifecycle-management-fsx/file-lifecycle-management-fsx.md
- [ ] **File System Sync with DataSync and EFS** — *intermediate*, ~60 min | datasync, efs, s3, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/file-sync-datasync/file-sync-datasync.md
- [ ] **Implementing Cross-Region Backup Automation with AWS Backup** — *intermediate*, ~60 min | AWS Backup, EventBridge, IAM, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/implementing-cross-region-backup-automation/implementing-cross-region-backup-automation.md
- [ ] **Managing Files with Web Interfaces** — *intermediate*, ~90 min | AWS Transfer Family, S3, IAM Identity Center, S3 Access Grants
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/managing-files-with-web-interfaces/managing-files-with-web-interfaces.md
- [ ] **Optimizing Large File Uploads with S3 Multipart Strategies** — *intermediate*, ~45 min | s3, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/optimizing-large-file-uploads/optimizing-large-file-uploads.md
- [ ] **Optimizing Storage Costs with S3 Storage Classes** — *intermediate*, ~90 min | s3, cloudwatch, budgets, cost-explorer
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/optimizing-storage-costs-s3/optimizing-storage-costs-s3.md
- [ ] **Optimizing Storage with S3 Analytics and Reporting** — *intermediate*, ~90 min | s3, athena, quicksight, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/optimizing-storage-with-s3-analytics/optimizing-storage-with-s3-analytics.md
- [ ] **S3 Automated Tiering and Lifecycle Management** — *intermediate*, ~45 min | s3, cloudwatch, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/s3-automated-tiering/s3-automated-tiering.md
- [ ] **Serving Static Content with S3 and CloudFront** — *intermediate*, ~45 min | s3, cloudfront, acm, route53
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/serving-static-content-s3/serving-static-content-s3.md
- [ ] **Sharing Files Securely with Web Portals** — *intermediate*, ~90 min | AWS Transfer Family, S3, IAM Identity Center, CloudTrail
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/sharing-files-securely-with-web-portals/sharing-files-securely-with-web-portals.md

### AI & Machine Learning (33)

- [ ] **AI Content Moderation with Bedrock and EventBridge** — *advanced*, ~120 min | Amazon Bedrock, Amazon EventBridge, AWS Lambda, Amazon S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/content-moderation-bedrock-eventbridge/content-moderation-bedrock-eventbridge.md
- [ ] **Blockchain Audit Trails for Compliance** — *advanced*, ~120 min | QLDB, CloudTrail, IAM, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/blockchain-audit-trails-qldb/blockchain-audit-trails-qldb.md
- [ ] **Chatbot Development with Amazon Lex** — *advanced*, ~120 min | Lex, Lambda, DynamoDB, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/chatbot-development-lex/chatbot-development-lex.md
- [ ] **Document Analysis Solutions with Amazon Textract** — *advanced*, ~120 min | textract, step-functions, s3, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/document-analysis-textract/document-analysis-textract.md
- [ ] **Document Analysis Solutions with Textract** — *advanced*, ~120 min | textract, lambda, s3, sns
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/document-analysis-solutions-textract/document-analysis-solutions-textract.md
- [ ] **Document QA System with Bedrock and Kendra** — *advanced*, ~120 min | Bedrock, Kendra, S3, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/document-qa-system/document-qa-system.md
- [ ] **Extracting Insights from Text with Amazon Comprehend** — *advanced*, ~120 min | amazon comprehend, aws lambda, amazon s3, amazon eventbridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/extracting-insights-from-text/extracting-insights-from-text.md
- [ ] **Fraud Detection with Amazon Fraud Detector** — *advanced*, ~120 min | fraud-detector, s3, iam, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/fraud-detection/fraud-detection.md
- [ ] **Intelligent Content Moderation with Bedrock** — *advanced*, ~120 min | Amazon Bedrock, Amazon EventBridge, AWS Lambda, Amazon S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/intelligent-content-moderation-bedrock/intelligent-content-moderation-bedrock.md
- [ ] **Real-Time Edge AI Inference with IoT Greengrass and ONNX** — *advanced*, ~120 min | IoT Greengrass, EventBridge, S3, IoT Core
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/real-time-edge-ai-inference/real-time-edge-ai-inference.md
- [ ] **SageMaker Model Endpoints for ML Inference** — *advanced*, ~120 min | sagemaker, ecr, cloudwatch, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/sagemaker-model-endpoints/sagemaker-model-endpoints.md
- [ ] **Smart Contract Development on Ethereum with Managed Blockchain** — *advanced*, ~120 min | managed-blockchain, lambda, api-gateway, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/ethereum-smart-contracts/ethereum-smart-contracts.md
- [ ] **Transcribing Speech with Amazon Transcribe** — *advanced*, ~120 min | transcribe, s3, iam, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/transcribing-speech-amazon-transcribe/transcribing-speech-amazon-transcribe.md
- [ ] **Analyzing Video Streams with Rekognition and Kinesis** — *expert*, ~180 min | rekognition, kinesis-video-streams, lambda, dynamodb
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/video-analytics-rekognition-kinesis/video-analytics-rekognition-kinesis.md
- [ ] **AutoML Solutions with SageMaker Autopilot** — *expert*, ~180 min | SageMaker, S3, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/automl-sagemaker-autopilot/automl-sagemaker-autopilot.md
- [ ] **Blockchain Supply Chain Tracking Systems** — *expert*, ~180 min | Managed Blockchain, IoT Core, Lambda, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/blockchain-supply-chain-tracking/blockchain-supply-chain-tracking.md
- [ ] **Blockchain-Based Voting Systems** — *expert*, ~180 min | Managed Blockchain, IAM, Cognito, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/blockchain-voting-systems/blockchain-voting-systems.md
- [ ] **Building Advanced Recommendation Systems with Amazon Personalize** — *expert*, ~180 min | amazon-personalize, s3, lambda, eventbridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/advanced-recommendation-systems-personalize/advanced-recommendation-systems-personalize.md
- [ ] **Building Recommendation Systems with Amazon Personalize** — *expert*, ~180 min | Personalize, API Gateway, Lambda, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/recommendation-systems-personalize/recommendation-systems-personalize.md
- [ ] **Cross-Organization Data Sharing with Blockchain** — *expert*, ~240 min | managed-blockchain, lambda, eventbridge, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cross-org-data-sharing-blockchain/cross-org-data-sharing-blockchain.md
- [ ] **Custom Entity Recognition with Comprehend** — *expert*, ~240 min | comprehend, s3, lambda, stepfunctions
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/custom-entity-recognition-comprehend/custom-entity-recognition-comprehend.md
- [ ] **Detecting Fraud with Amazon Fraud Detector** — *expert*, ~180 min | frauddetector, kinesis, lambda, dynamodb
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/fraud-detection-amazon-fraud-detector/fraud-detection-amazon-fraud-detector.md
- [ ] **End-to-End MLOps with SageMaker Pipelines** — *expert*, ~180 min | sagemaker, codecommit, s3, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/mlops-sagemaker-pipelines/mlops-sagemaker-pipelines.md
- [ ] **Enterprise Blockchain Network** — *expert*, ~240 min | managed-blockchain, vpc, ec2, cloudformation
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/enterprise-blockchain-network/enterprise-blockchain-network.md
- [ ] **Establishing Private Blockchain Networks with Amazon Managed Blockchain** — *expert*, ~180 min | managed-blockchain, vpc, iam, ec2
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/private-blockchain-networks-managed-blockchain/private-blockchain-networks-managed-blockchain.md
- [ ] **Optimizing Personalized Recommendations with A/B Testing** — *expert*, ~240 min | Personalize, API Gateway, Lambda, DynamoDB
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/personalized-recommendations-ab-testing/personalized-recommendations-ab-testing.md
- [ ] **Processing Multilingual Voice Content with Transcribe and Polly** — *expert*, ~180 min | transcribe, polly, translate, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/processing-multilingual-voice-content/processing-multilingual-voice-content.md
- [ ] **SageMaker MLOps Pipeline with CodePipeline** — *expert*, ~180 min | sagemaker, codepipeline, codebuild, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/sagemaker-mlops-pipeline/sagemaker-mlops-pipeline.md
- [ ] **SageMaker Model Monitoring and Drift Detection** — *expert*, ~180 min | sagemaker, cloudwatch, s3, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/sagemaker-model-monitoring/sagemaker-model-monitoring.md
- [ ] **Automated Document Extraction with Textract** — *intermediate*, ~60 min | textract, s3, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/automated-document-extraction/automated-document-extraction.md
- [ ] **Automated Image Analysis with ML** — *intermediate*, ~45 min | Amazon Rekognition, Amazon S3, AWS CLI
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/automated-image-analysis/automated-image-analysis.md
- [ ] **Conversational AI Applications with Bedrock** — *intermediate*, ~90 min | Bedrock, Lambda, API Gateway, DynamoDB
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/conversational-ai-bedrock-claude/conversational-ai-bedrock-claude.md
- [ ] **Multi-Agent Knowledge Management with Bedrock AgentCore and Q Business** — *intermediate*, ~45 min | Bedrock AgentCore, Q Business, S3, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/multi-agent-knowledge-management-agentcore-q/multi-agent-knowledge-management-agentcore-q.md

### Application Development & Deployment (32)

- [ ] **Automated Application Migration Workflows** — *advanced*, ~120 min | AWS Application Migration Service, Migration Hub Orchestrator, CloudFormation, Systems Manager
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/automated-migration-workflows-mgn/automated-migration-workflows-mgn.md
- [ ] **CloudFormation Nested Stacks Management** — *advanced*, ~150 min | CloudFormation, S3, IAM, VPC
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cloudformation-nested-stacks/cloudformation-nested-stacks.md
- [ ] **Developer Environments with Cloud9** — *advanced*, ~150 min | Cloud9, EC2, IAM, CodeCommit
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/developer-environments-cloud9/developer-environments-cloud9.md
- [ ] **GitOps with CodeCommit and CodeBuild** — *advanced*, ~120 min | codecommit, codebuild, codepipeline, ecr
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/gitops-codecommit/gitops-codecommit.md
- [ ] **Infrastructure Deployment Pipelines with CDK** — *advanced*, ~120 min | CDK, CodePipeline, CodeBuild, CodeCommit
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/infrastructure-deployment-pipelines/infrastructure-deployment-pipelines.md
- [ ] **Infrastructure Testing with TaskCat and CloudFormation** — *advanced*, ~120 min | cloudformation, taskcat, s3, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/infrastructure-testing-taskcat/infrastructure-testing-taskcat.md
- [ ] **Infrastructure as Code with Terraform** — *advanced*, ~120 min | EC2, S3, DynamoDB, ALB
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/infrastructure-as-code-terraform/infrastructure-as-code-terraform.md
- [ ] **Monitoring Application Resilience with AWS Resilience Hub and EventBridge** — *advanced*, ~120 min | AWS Resilience Hub, Amazon EventBridge, Systems Manager, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/proactive-resilience-monitoring-resiliencehub-eventbridge/proactive-resilience-monitoring-resiliencehub-eventbridge.md
- [ ] **Visual Serverless Applications with Infrastructure Composer** — *advanced*, ~120 min | Application Composer, CodeCatalyst, Lambda, CloudFormation
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/visual-serverless-apps-composer/visual-serverless-apps-composer.md
- [ ] **Advanced Blue-Green Deployments with CodeDeploy** — *expert*, ~300 min | CodeDeploy, ECS, Lambda, ALB
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/advanced-blue-green-deployments/advanced-blue-green-deployments.md
- [ ] **Advanced CodeBuild Pipelines with Caching** — *expert*, ~240 min | CodeBuild, S3, ECR, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/advanced-codebuild-pipelines/advanced-codebuild-pipelines.md
- [ ] **Artifact Management with CodeArtifact** — *expert*, ~180 min | CodeArtifact, IAM, KMS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/artifact-management-codeartifact/artifact-management-codeartifact.md
- [ ] **CloudFormation StackSets Multi-Account Management** — *expert*, ~210 min | CloudFormation, Organizations, IAM, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cloudformation-stacksets-multi-account/cloudformation-stacksets-multi-account.md
- [ ] **Container CI/CD Pipelines with CodePipeline** ⭐ — *expert*, ~210 min | CodePipeline, CodeDeploy, CodeBuild, ECS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/container-cicd-pipelines-codepipeline/container-cicd-pipelines-codepipeline.md
- [ ] **Continuous Deployment with CodeDeploy** — *expert*, ~180 min | codedeploy, codecommit, codebuild, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/continuous-deployment-codedeploy/continuous-deployment-codedeploy.md
- [ ] **GitOps for EKS with ArgoCD** — *expert*, ~180 min | EKS, ArgoCD, CodeCommit, ALB
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/gitops-eks-argocd/gitops-eks-argocd.md
- [ ] **Infrastructure Testing Strategies for IaC** — *expert*, ~240 min | CloudFormation, CodeBuild, CodePipeline, CDK
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iac-testing-strategies/iac-testing-strategies.md
- [ ] **Orchestrating Multi-Branch CI/CD Automation with CodePipeline** — *expert*, ~180 min | codepipeline, codecommit, codebuild, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/orchestrating-multi-branch-cicd-automation/orchestrating-multi-branch-cicd-automation.md
- [ ] **Automated Chaos Engineering with Fault Injection Service** — *intermediate*, ~90 min | AWS Fault Injection Service, EventBridge, CloudWatch, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/chaos-engineering-resilience-testing/chaos-engineering-resilience-testing.md
- [ ] **Cloud Development Workflows with CloudShell** — *intermediate*, ~60 min | CloudShell, CodeCommit, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cloud-dev-workflows-cloudshell/cloud-dev-workflows-cloudshell.md
- [ ] **Code Quality Gates with CodeBuild** — *intermediate*, ~75 min | CodeBuild, Systems Manager, SNS, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/code-quality-gates-codebuild/code-quality-gates-codebuild.md
- [ ] **Code Review Automation with CodeGuru** — *intermediate*, ~90 min | CodeGuru, CodeCommit, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/code-review-automation-codeguru/code-review-automation-codeguru.md
- [ ] **CodeCommit Git Workflows and Policies** — *intermediate*, ~80 min | CodeCommit, Lambda, EventBridge, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/codecommit-git-workflows/codecommit-git-workflows.md
- [ ] **Cost-Aware Resource Lifecycle with MemoryDB** — *intermediate*, ~90 min | EventBridge Scheduler, MemoryDB for Redis, Lambda, Cost Explorer
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cost-aware-lifecycle-memorydb/cost-aware-lifecycle-memorydb.md
- [ ] **Development Environment Provisioning with WorkSpaces** — *intermediate*, ~90 min | WorkSpaces, Systems Manager, Lambda, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/dev-environment-workspaces-provisioning/dev-environment-workspaces-provisioning.md
- [ ] **Feature Flags with AWS AppConfig** — *intermediate*, ~90 min | AppConfig, Lambda, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/feature-flags-appconfig/feature-flags-appconfig.md
- [ ] **Feature Flags with CloudWatch Evidently** — *intermediate*, ~60 min | cloudwatch-evidently, lambda, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/feature-flags-evidently/feature-flags-evidently.md
- [ ] **Infrastructure Automation with AWS Proton and CDK** — *intermediate*, ~90 min | proton, cdk, ecs, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/infrastructure-automation-proton/infrastructure-automation-proton.md
- [ ] **Infrastructure Automation with CloudShell PowerShell** — *intermediate*, ~90 min | CloudShell, Systems Manager, Lambda, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/infrastructure-automation-cloudshell/infrastructure-automation-cloudshell.md
- [ ] **Infrastructure Automation with Proton and CDK** — *intermediate*, ~90 min | Proton, CDK, CodePipeline, CloudFormation
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/infrastructure-automation-proton-cdk/infrastructure-automation-proton-cdk.md
- [ ] **Infrastructure Policy Validation with CloudFormation Guard** — *intermediate*, ~90 min | CloudFormation Guard, CloudFormation, S3, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/infrastructure-policy-validation/infrastructure-policy-validation.md
- [ ] **Organizing Resources with Groups and Automated Management** — *intermediate*, ~75 min | Resource Groups, Systems Manager, CloudWatch, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/organizing-resources-with-groups/organizing-resources-with-groups.md

### Monitoring & Management (18)

- [ ] **Application Performance Monitoring Automation** — *advanced*, ~120 min | CloudWatch, EventBridge, Lambda, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/app-performance-monitoring-cloudwatch/app-performance-monitoring-cloudwatch.md
- [ ] **Auto-Remediation with Config and Lambda** — *advanced*, ~120 min | Config, Lambda, IAM, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/auto-remediation-config-lambda/auto-remediation-config-lambda.md
- [ ] **Automated Backup Solutions with AWS Backup** — *advanced*, ~120 min | AWS Backup, CloudWatch, IAM, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/automated-backup-solutions/automated-backup-solutions.md
- [ ] **Automated Carbon Footprint Optimization** — *advanced*, ~120 min | Cost Explorer, EventBridge, Lambda, DynamoDB
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/carbon-footprint-optimization/carbon-footprint-optimization.md
- [ ] **Automated Patching with Systems Manager** — *advanced*, ~120 min | Systems Manager, EC2, CloudWatch, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/automated-patching-systems-manager/automated-patching-systems-manager.md
- [ ] **Cost Allocation and Chargeback Systems** — *advanced*, ~120 min | organizations, cost-explorer, budgets, lambda, +1 more
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cost-allocation-chargeback-systems/cost-allocation-chargeback-systems.md
- [ ] **Infrastructure Monitoring with CloudTrail and Config** — *advanced*, ~120 min | cloudtrail, config, systems-manager
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/infrastructure-monitoring-governance/infrastructure-monitoring-governance.md
- [ ] **Business Continuity Testing with Systems Manager** — *expert*, ~180 min | Systems Manager, CloudFormation, EventBridge, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/business-continuity-testing-systems/business-continuity-testing-systems.md
- [ ] **Cross-Region Disaster Recovery Automation** — *expert*, ~180 min | elastic-disaster-recovery, lambda, cloudwatch, systems-manager
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cross-region-dr-automation/cross-region-dr-automation.md
- [ ] **Multi-Service Monitoring Dashboards** — *expert*, ~180 min | CloudWatch, Lambda, ECS, RDS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/multi-service-monitoring-dashboards/multi-service-monitoring-dashboards.md
- [ ] **Organizations Multi-Account Governance with SCPs** — *expert*, ~180 min | Organizations, IAM, CloudTrail, Budgets
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/organizations-governance/organizations-governance.md
- [ ] **VMware Cloud Migration with VMware Cloud on AWS** — *expert*, ~180 min | VMware Cloud on AWS, AWS Application Migration Service, AWS Direct Connect, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/vmware-cloud-migration/vmware-cloud-migration.md
- [ ] **Basic Log Monitoring with CloudWatch** — *intermediate*, ~60 min | CloudWatch, SNS, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/basic-log-monitoring-cloudwatch/basic-log-monitoring-cloudwatch.md
- [ ] **Centralized Logging with OpenSearch Service** — *intermediate*, ~55 min | OpenSearch Service, CloudWatch, Lambda, Kinesis
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/centralized-logging-opensearch/centralized-logging-opensearch.md
- [ ] **Cost Optimization Workflows with Budgets** — *intermediate*, ~90 min | Cost Optimization Hub, AWS Budgets, SNS, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cost-optimization-workflows-budgets/cost-optimization-workflows-budgets.md
- [ ] **Intelligent Cost Anomaly Detection** — *intermediate*, ~90 min | CloudWatch, Lambda, SNS, Cost Explorer
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/intelligent-cost-anomaly-detection/intelligent-cost-anomaly-detection.md
- [ ] **Optimizing Costs with Automated Savings Plans** — *intermediate*, ~60 min | cost-explorer, savings-plans, lambda, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/optimizing-costs-with-savings-plans/optimizing-costs-with-savings-plans.md
- [ ] **Website Uptime Monitoring with Route 53** — *intermediate*, ~60 min | Route 53, CloudWatch, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/website-uptime-monitoring/website-uptime-monitoring.md

### IoT & Edge Computing (14)

- [ ] **Edge Computing with IoT Greengrass and Lambda** — *advanced*, ~120 min | iot-core, greengrass, lambda, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/edge-computing-iot-greengrass/edge-computing-iot-greengrass.md
- [ ] **Industrial IoT Data Collection with SiteWise** — *advanced*, ~120 min | iot-sitewise, iot-core, timestream, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/industrial-iot-data-collection/industrial-iot-data-collection.md
- [ ] **IoT Device Lifecycle Management with AWS IoT Core** — *advanced*, ~120 min | iot-core, iot-device-management, cloudwatch, iot-jobs
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iot-device-lifecycle/iot-device-lifecycle.md
- [ ] **IoT Device Provisioning and Certificate Management** — *advanced*, ~120 min | iot-core, lambda, dynamodb, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iot-device-provisioning/iot-device-provisioning.md
- [ ] **IoT Event Processing with Rules Engine** — *advanced*, ~120 min | iot-core, lambda, dynamodb, sns
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iot-event-processing/iot-event-processing.md
- [ ] **IoT Fleet Monitoring with Device Defender** — *advanced*, ~120 min | iot-core, iot-device-defender, cloudwatch, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iot-fleet-monitoring/iot-fleet-monitoring.md
- [ ] **IoT Over-the-Air Updates with Device Management** — *advanced*, ~120 min | iot-core, iot-device-management, s3, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iot-ota-updates/iot-ota-updates.md
- [ ] **Sustainable Manufacturing Monitoring with IoT SiteWise** — *advanced*, ~120 min | IoT SiteWise, CloudWatch, Lambda, QuickSight
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/sustainable-manufacturing-monitoring/sustainable-manufacturing-monitoring.md
- [ ] **Vehicle Telemetry Analytics with IoT FleetWise** — *advanced*, ~120 min | AWS IoT FleetWise, Amazon Timestream, Amazon Managed Grafana, S3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/vehicle-telemetry-analytics/vehicle-telemetry-analytics.md
- [ ] **IoT Device Shadow Synchronization** — *expert*, ~180 min | IoT Core, Device Shadow, Lambda, DynamoDB
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iot-device-shadow-sync/iot-device-shadow-sync.md
- [ ] **IoT Firmware Updates with Device Management Jobs** — *expert*, ~180 min | iot, lambda, s3, signer
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iot-firmware-updates/iot-firmware-updates.md
- [ ] **IoT Data Ingestion with IoT Core** — *intermediate*, ~60 min | IoT Core, Lambda, DynamoDB, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iot-data-ingestion/iot-data-ingestion.md
- [ ] **IoT Device Registry with IoT Core** — *intermediate*, ~60 min | iot-core, iot-device-management, lambda, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iot-device-registry/iot-device-registry.md
- [ ] **IoT Device Shadows for State Management** — *intermediate*, ~60 min | iot-core, device-shadows, lambda, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/iot-device-shadows/iot-device-shadows.md

### Integration & Messaging (11)

- [ ] **Automating Reserved Instance Management** — *advanced*, ~120 min | cost-explorer, lambda, eventbridge, sns
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/reserved-instance-automation/reserved-instance-automation.md
- [ ] **Business File Processing with Transfer Family** — *advanced*, ~120 min | transfer-family, step-functions, lambda, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/business-file-processing-transfer/business-file-processing-transfer.md
- [ ] **CQRS and Event Sourcing with EventBridge** — *advanced*, ~120 min | eventbridge, dynamodb, lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cqrs-event-sourcing-eventbridge/cqrs-event-sourcing-eventbridge.md
- [ ] **Distributed Tracing with X-Ray and EventBridge** — *advanced*, ~120 min | x-ray, eventbridge, lambda, api-gateway
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/distributed-tracing-xray-eventbridge/distributed-tracing-xray-eventbridge.md
- [ ] **Distributed Transaction Processing with SQS** — *advanced*, ~120 min | sqs, dynamodb, lambda, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/distributed-transactions-sqs-dynamodb/distributed-transactions-sqs-dynamodb.md
- [ ] **Event Sourcing with EventBridge and DynamoDB** — *advanced*, ~120 min | eventbridge, dynamodb, lambda, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/event-sourcing/event-sourcing.md
- [ ] **Orchestrating Distributed Transactions with Saga Patterns** — *advanced*, ~120 min | Step Functions, Lambda, DynamoDB, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/orchestrating-distributed-transactions-with-sagas/orchestrating-distributed-transactions-with-sagas.md
- [ ] **Processing Ordered Messages with SQS FIFO and Dead Letter Queues** — *advanced*, ~120 min | sqs, lambda, cloudwatch, dynamodb
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/ordered-message-processing-sqs-fifo-dlq/ordered-message-processing-sqs-fifo-dlq.md
- [ ] **Cost Governance Automation with Config** — *expert*, ~180 min | Config, Lambda, SNS, EventBridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cost-governance-automation-config/cost-governance-automation-config.md
- [ ] **Budget Alerts and Automated Cost Actions** — *intermediate*, ~60 min | AWS Budgets, SNS, Lambda, CloudWatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/budget-alerts-automated-actions/budget-alerts-automated-actions.md
- [ ] **Cost Anomaly Detection with Machine Learning** — *intermediate*, ~60 min | cost-anomaly-detection, sns, cloudwatch, eventbridge
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/cost-anomaly-detection/cost-anomaly-detection.md

### Media & Content (10)

- [ ] **Live Video Streaming Platform with MediaLive** — *advanced*, ~120 min | medialive, mediapackage, cloudfront, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/video-streaming-medialive/video-streaming-medialive.md
- [ ] **Scalable Live Streaming with Elemental MediaLive** — *advanced*, ~120 min | medialive, mediapackage, cloudfront, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/scalable-live-streaming/scalable-live-streaming.md
- [ ] **Video-on-Demand Platform with MediaStore** — *advanced*, ~120 min | mediastore, cloudfront, s3, iam
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/video-on-demand-mediastore/video-on-demand-mediastore.md
- [ ] **Adaptive Bitrate Video Streaming with CloudFront** — *expert*, ~180 min | MediaConvert, S3, CloudFront, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/adaptive-video-streaming-cloudfront/adaptive-video-streaming-cloudfront.md
- [ ] **Audio Processing Pipelines with MediaConvert** — *expert*, ~180 min | MediaConvert, S3, Lambda, IAM
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/audio-processing-mediaconvert/audio-processing-mediaconvert.md
- [ ] **Automated Video Content Analysis with Rekognition** — *expert*, ~180 min | rekognition, stepfunctions, lambda, s3
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/video-content-analysis-rekognition/video-content-analysis-rekognition.md
- [ ] **Live Event Broadcasting with Elemental MediaConnect** — *expert*, ~180 min | mediaconnect, medialive, mediapackage, cloudwatch
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/live-event-broadcasting/live-event-broadcasting.md
- [ ] **Video DRM Protection with MediaPackage** — *expert*, ~180 min | mediapackage, medialive, secrets, manager, +2 more
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/video-drm-protection-mediapackage/video-drm-protection-mediapackage.md
- [ ] **Video Workflow Orchestration with Step Functions** — *expert*, ~240 min | Step Functions, MediaConvert, S3, Lambda
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/video-workflow-orchestration-stepfunctions/video-workflow-orchestration-stepfunctions.md
- [ ] **Orchestrating Media Workflows with MediaConnect and Step Functions** — *intermediate*, ~90 min | AWS Elemental MediaConnect, AWS Step Functions, CloudWatch, SNS
  https://github.com/mzazon/awesome-cloud-projects/tree/main/aws/orchestrating-media-workflows-mediaconnect-stepfunctions/orchestrating-media-workflows-mediaconnect-stepfunctions.md
