# Todo.. (2023 ~ N)

- 앞으로 해야하고 할것들 정리

<details>
<summary> [2023년] Backend 개발자에서 Devops로 전환 </summary>
<div markdown="1">

- CI / CD Pipeline

  - [x] Terraform
  - [x] Github
  - [x] Jenkins
  - [x] Push The ECR
  - [x] Trigger EventBridge
  - [x] Deploy ECS
  - [x] Deploy (Blue / Green)
  - [x] Rollback (ECS)
  - [x] Kubernetis theory

- CDN

  - [x] Download use S3
  - [x] Download use CloudFront from S3
  - [x] Deploy Static Page use CloudFront (Terraform)

- DevSecOps + Network

  - [x] Region 간 통신 Best Practice (VPC Peering, transit gateway)

- SNS

  - [x] Cloud Watch
  - [x] SNS
  - [x] Lambda
  - [x] Slack Webhooks
  - [x] EventBridge + Lambda + Slack Notification
  - [x] 간단하게 프로젝트로 만들어보기 (만능 슬랙봇)

- Service

  - [x] Docker
  - [x] ECS
  - [x] Kinesis
  - [x] Kinesis DataStream + Kinesis Firehoes + S3

- Lanaguage & lib

  - [x] Golang
  - [x] Cobra (CLI)

- Todo Repository

  - [x] golang-eb-ecs
  - [x] ecs-master
  - [x] cicd-pipeline
  - [x] simple-sns-slack

- Infra Project
  - [x] Teleport (서버 접근제어)

</div>
</details>

<details>
<summary> [2024년] Devops Engineering을 제대로... </summary>
<div markdown="1">

- 전년도에 못한 Todo

  - [x] ECS For CiCD FullSet (ECS + Jenkins + CodeDeploy + Best Practice)
  - [x] ECS For Kinesis Pipeline (firelens + firehoes + s3)
  - [x] NatGateway에 대해서 공부하기...
  - [x] Elastic Search (EFK, ELK)
  - [ ] ES Deep Dive(Elastic Agent, APM, Fleet-Manager)
  - [x] LogStash 깊게 공부해보기
  - [x] Prometheus (node-export, black-box)
  - [ ] MQTT Protocol (RealTime Chatting Service)
  - [ ] Chat Service (API Gateway + Lambda + DynamoDB)
  - [ ] zookeeper from Service Discovery
  - [ ] <a href="https://kafka.apache.org/documentation/#introduction">Kafka 문서 정독하기</a>
  - [ ] <a href="https://debezium.io/documentation/reference/stable/connectors/mysql.html">Debizium 문서 정독하기 </a>
  - [ ] NLB 알고리즘 공부해보기 (Hash, IP ...)
  - [ ] Fluentbit, Logstash를 비교하기 이전에 -> 로그유실이 없는 DataPipeline 작업을 위한 Best Practice

- Engineering

  - [ ] AWS Data Pipeline (Kinesis, EMR, Glue)
  - [ ] Glue 기반한 DataFlow 구성해보기 (EC2 - APIGateway - Kinesis DataStream - Kinesis Firehoes - S3 - AWS Glue) - S3 데이터 저장 (Bronze Data, Silver Data, Golden Data 고려
  - [x] Airflow
  - [ ] Deep Dive Data Engineering (Spark, Flink, Apache Beam)
  - [ ] snowflake
  - [ ] DataHub (Linkedin Opensource)

- CDN

  - [ ] CloudFlare

- Langauge

  - [x] Golang Deep Dive
  - [x] go cobra를 사용해서 CLI 만들기

- DevSecOps

  - [x] WAF , WAF 자동화, 특정 IP를 Temp형태로 제어
  - [ ] AWS Security Hub
  - [ ] SOAR (보안 오케스트레이션, 자동화)
  - [ ] Consoleme 공부하기
  - [x] ABAC (Attribute-Based Access Control) 공부해보기 + IAM
  - [x] Cloud Trail + Event Bridge + SNS + AWS Chatbot + Slack

- Infra

  - [x] ECS(A) + APIGateway + SQS + ECS(B) -> EDA Architecture
  - <a href="https://github.com/zkfmapf123/api-gateway-pubsub-pattern"> API-Gateway SQS Pub/Sub Pattern </a>
  - [x] Golang + Lambda + DynamoDB
  - [x] ECS Fargate + Sonarcube + Clair or Scout + EFK (ES + Fluentd + Kibana) + VPC Lattic
  - [x] Kubernetes, k8s
  - [ ] EKS + Github Action + Helm (GitOps)
  - [ ] EKS + Github Action + Helm + Istio (Zero Trust)
  - [x] 여러 인스턴스에 널려진 Container들의 정보를 한곳에서 보고싶음.. (Noamd나 Portrainer 들은 각 인스턴스에서만 동작함 -> 별롬)
  - [x] CloudWatch + Kinesis Firehoes + S3 + Athena / Kinesis Fiehoes 와 Event Bridge + Lambda 중에 어떤것이 더 효율적인가? (Lambda가 효율적이긴 함...)
  - [x] AWS Config를 활용하여 인프라관리 Lambda
  - [x] Lambda CLI
  - [x] CloudNative 공부하기 - ClickStream
  - [x] CloudNative 공부하기 - Cognito 와 다른 리소스 연결
  - [x] CloudNative 공부하기 - Amplify Gen2
  - [x] CodeBuild + Action Runner 제대로 구성하기

- Certificate

  - [ ] AWS Associate
  - [ ] Certified Kubernetes Administrator (CKA)

- Side-Project
  - [ ] 나만의 AWS Architecture 구상도
  - [ ] AWS Architecture 블로그만들기

</div>
</details>

<details>
<summary> [2025년] Devops 전문가 되기 </summary>
<div markdown="1">

- SaaS Pipeline

  - [x] ArgoCD
  - [x] Helm
  - [x] Attlantis
  - [x] BackStage
  - [ ] Istio
  - [x] LGTM Stack (Loki, Grafana, Tempo, Mimir) 
  - [ ] ES Deep Dive(Elastic Agent, APM, Fleet-Manager)
  - [ ] <a href="https://kafka.apache.org/documentation/#introduction">Kafka 문서 정독하기</a>
  - [ ] <a href="https://debezium.io/documentation/reference/stable/connectors/mysql.html">Debizium 문서 정독하기 </a>

- Data Engineering

  - [x] apache Beam (Golang)

- DevSecOps

  - [ ] AWS Security Hub
  - [x] SOAR (보안 오케스트레이션, 자동화)
  - [x] CloudTrail, Inspector, Config 통합 및 공부해보기
  - [x] 보안 도구 공부해보기 (prowler)

- Infra

  - [ ] Kubernetes 깊게 공부하기
  - [ ] ClickStream 공부하기
  - [x] Kafka pub/sub
  - [x] Kafak CDC / outbox (Connect)
  - [x] Kafak Stream / KsQL
  - [ ] Kafka on K8s

- SRE

  - [x] SRE 공부하기
  - [ ] SLO, SLI, SLA 지표의 대한 공부
  - [x] Platform Engineering 공부해보기

- Certificate

  - [ ] AWS Associate
  - [ ] Certified Kubernetes Administrator (CKA)
 
- Side Project

  - [ ] <a href="https://github.com/zkfmapf123/mcp-aws-athena">MCP-AWS-Athena (mcp 서버를 활용한 athena 질의) </a>
  - [ ] Datadog NEXT - Express (dd-tracer 전체 pipeline)
  - [ ] <a href="https://github.com/zkfmapf123/resource-diagram">AWS Diagram Pipeline</a>

- Kubernetes
  - [ ] EKS
  - [ ] ArgoCD
  - [ ] ArgoCD Rollout
  - [ ] ArgoCD Notification
  - [ ] ArgoCD Image Updater
  - [ ] HPA / AutoScaler
  - [ ] Karpenter
  - [ ] LGTM Stack in EKS

</div>
</details>
