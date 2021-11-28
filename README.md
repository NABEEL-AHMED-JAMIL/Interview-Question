# Interview-Question
Repo for interview question to target the Big Org like (Google | AWS | EPAM | J.P morgan chase)

#### Q:- What is AWS Fargate?
```
AWS Fargate (Run containers directly, without any EC2 instances)
Fargate is a serverless environment for running containers that allows users to completely remove the need to own,
run, and manage the lifecycle of a compute infrastructure. 
AWS Fargate is compatible with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS).
```
#### Q:- What is AWS Lambda?
```
AWS Lambda charges you per invocation and duration of each invocation
whereas AWS Fargate charges you for the vCPU and memory resources of your containerized applications use per second.
```
#### Q:- DevOps tools example?
```
git, kubernetes, docker, jenkin, aws.
```

### Q:- Jenkin Seed-job?
```
You can see we already have one job called seed-job automatically available. This job is responsible for creating any other jobs that we need.
```

### Q:- How you design message and event-driven architectures?
```
1: Kafka|Zookeper ->
	Point to Point Messaging System
	Publish-Subscribe Messaging System 
2: AWS-SQS
```

### Q:- Introducing Agile processes to the existing team CI/CD process?
```
1) Plan
2) Design
3) Develop
4) Test
5) Deploy
6) Review
7) Launch
```

### Q:- Different b.w collections/streams? -> imp questin
```
Java Collections focus on how to store data elements for efficient access/Java streams focus on aggregate operations on data elements from a data source.
Streams are not reusable. A stream cannot be reused after calling a terminal operation.
To perform a computation on the same elements from the same data source, we have to recreate the stream pipeline.
A stream may throw an IllegalStateException in case of reusing.
```

### Q:- Different b/w Iterator and ListIterator?
```
Iterator traverses the elements in the forward direction only whereas ListIterator traverses the elements into forward and backward direction.
```

