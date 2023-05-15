# DEVOPS STUFF

[100 days of DevOps](https://github.com/100daysofdevops/100daysofdevops)

[Python for DevOps tutorials](https://realpython.com/tutorials/devops/)

Sample projects:

Host a static website in S3, For a simple web app consider making it a page that documents everything you have done. A bit like people making their CV into a website that they built. A kind of showcase if you will. [Try this one](https://towardsaws.com/forget-a-server-bring-your-static-website-to-life-with-aws-s3-lambda-and-api-gateway-8734baaada6f) or [This one from AWS](https://aws.amazon.com/getting-started/projects/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/module-1/)

Create a full secure cloud environment for this project (web site mentioned above) using terraform and GitOps and runs security scans of the application and infrastructure code in the ci/cd pipeline

Create a simple web application you could build and deploy into a cloud environment like AWS or GCP. Build your cloud infrastructure with Terraform for this application. Deploy that infrastructure and the application itself using GitOps. For exampleBut also make sure you are doing security testing inside that Ci/CD process, here is an example of that https://medium.com/javarevisited/sast-and-github-securing-your-organization-from-exposed-credentials-a80d2103d56b. That way you demonstrate building and deploying an application with automated security testing

DEPLOYMENTS

Sample deployment 1:
Use ansible to code up a system that will take a fresh linux install and deploy your web app to it so it's ready to serve requests. Bonus points for wiring it up to Packer so you can build AMI's (AWS EC2 instance machine images).

Sample deployment 2:
Write a bunch of terraform to host your app in a robust way. A VPC, subnets in multiple availability zones, autoscaling groups, load balancer, (don't forget health checks), datastores etc.

Sample deployment 3:
Pick a CI tool, like Jenkins or CircleCI and create a build and deploy process wired up to the github repo for your web app. When a PR is cut the CI runs tests and sends results to github. When you merge to master the CI deploy the latest version of your app to the hosting environment that youve built.

Sample deployment 4:
Containerize the app and run it in ECS or EKS

MORE PROJECT EXAMPLES

Find a piece of software to deploy. Pull a simple "hello world" webapp, or write your own.

Write a CI/CD pipeline to execute different tests (linting, unit tests, etc) and have that pipeline deploy it to different targets depending on the branch.

Take said software project, figure out how you'd monitor it for errors

Take said software project, figure out how you'd scale it (use load testing tools like JMeter). +100XP for auto scaling.

Take said software project, figure out how to secure it (scan for outdated dependencies, auto renew TLS certs using letsencrypt, OWASP vuln scanning using something like Zap).)

Python for DevOps tutorials

Sample projects:

Host a static website in S3, For a simple web app consider making it a page that documents everything you have done. A bit like people making their CV into a website that they built. A kind of showcase if you will. Try this one or This one from AWS

Create a full secure cloud environment for this project (web site mentioned above) using terraform and GitOps and runs security scans of the application and infrastructure code in the ci/cd pipeline

Create a simple web application you could build and deploy into a cloud environment like AWS or GCP. Build your cloud infrastructure with Terraform for this application. Deploy that infrastructure and the application itself using GitOps. [For example](https://learn.hashicorp.com/tutorials/terraform/github-actions). But also make sure you are doing security testing inside that Ci/CD process, here is an example of that [SAST and Github: securing your organization from exposed credentials](https://medium.com/javarevisited/sast-and-github-securing-your-organization-from-exposed-credentials-a80d2103d56b). That way you demonstrate building and deploying an application with automated security testing

DEPLOYMENTS

Sample deployment 1:
Use ansible to code up a system that will take a fresh linux install and deploy your web app to it so it's ready to serve requests. Bonus points for wiring it up to Packer so you can build AMI's (AWS EC2 instance machine images).

Sample deployment 2:
Write a bunch of terraform to host your app in a robust way. A VPC, subnets in multiple availability zones, autoscaling groups, load balancer, (don't forget health checks), datastores etc.

Sample deployment 3:
Pick a CI tool, like Jenkins or CircleCI and create a build and deploy process wired up to the github repo for your web app. When a PR is cut the CI runs tests and sends results to github. When you merge to master the CI deploy the latest version of your app to the hosting environment that youve built.

Sample deployment 4:
Containerize the app and run it in ECS or EKS

MORE PROJECT EXAMPLES

Find a piece of software to deploy. Pull a simple "hello world" webapp, or write your own.

Write a CI/CD pipeline to execute different tests (linting, unit tests, etc) and have that pipeline deploy it to different targets depending on the branch.

Take said software project, figure out how you'd monitor it for errors

Take said software project, figure out how you'd scale it (use load testing tools like JMeter). +100XP for auto scaling.

Take said software project, figure out how to secure it (scan for outdated dependencies, auto renew TLS certs using letsencrypt, OWASP vuln scanning using something like Zap).
