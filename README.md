# Como desenvolver aplicações serverless em Java para Amazon Web Services 

This source code repository is related to this [book](http://leanpub.com/amazonwebservice_en) on how to develop serverless **Java** applications using [AWS Lambda](https://aws.amazon.com/lambda/), as well as **Java** applications using **Spring Boot** to run on **Amazon Web Services** using **Docker** container and [AWS ECS](https://aws.amazon.com/ecs/).

This will be a simple example of a serverless application using functions with [AWS Lambda](https://aws.amazon.com/lambda/), demonstrating how to execute it through an event published in an **SNS**.

To learn these and other application development concepts using Amazon Web Services, be sure to check out this [book](http://leanpub.com/amazonwebservice_en)!

Also, check out the other code repositories from this book:

- [Project01](http://github.com/siecola/aws_project01): In this example, an application will be built with REST services for product registration, in a store context. Such products will be stored in a MySQL database using [AWS RDS](https://aws.amazon.com/rds/). For each product registration, deletion, or change operation, an event will be published to an [AWS SNS](https://aws.amazon.com/sns) topic, allowing integration with other applications. This application will also import invoice files through [AWS S3](https://aws.amazon.com/s3/).
- [Project02](https://github.com/siecola/aws_project02): This project will use an [AWS DynamoDB](https://aws.amazon.com/dynamodb) table to persist the events generated by the first application, integrated through an [AWS SQS](https://aws.amazon.com/sqs/) queue.
- [Lambda01](https://github.com/siecola/aws_lambda01): This will be a simple example of a serverless application using functions with [AWS Lambda](https://aws.amazon.com/lambda/), demonstrating how to schedule a function to be executed.
- [Lambda03](https://github.com/siecola/aws_lambda03): Here's how to create a **Lambda** function to consume imported files in **S3** and persist its data to a **DynamoDB** table.

