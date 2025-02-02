<div align="center">
	<a target="_blank" href="https://gitforcetalent.com">
        <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://gitforcetalent.com/_next/image?url=%2Fimages%2Flogo-light.png&w=1920&q=75">
            <source media="(prefers-color-scheme: light)" srcset="https://gitforcetalent.com/_next/image?url=%2Fimages%2Flogo.png&w=1920&q=75">
            <img alt="https://gitforcetalent.com" src="https://gitforcetalent.com/_next/image?url=%2Fimages%2Flogo.png">
        </picture>
	</a>
    <br />
    <br />
</div>

---

---

# Cloud Infrastructure Task: API Gateway with Load Balancing

## Objective

Create a scalable and highly available infrastructure using AWS services, with load balancing.

## Requirements

1. Use one of the following Infrastructure as Code (IaC) tools:

   - AWS CDK
   - AWS CloudFormation
   - Terraform

2. Implement a load balancing solution for the backend services to ensure high availability and scalability.

3. Set up at least two EC2 instances as backend services running a simple web application (e.g., a "Hello World" app).

4. Configure appropriate security groups and network access controls.

## Detailed Steps

1. Set up the IaC project using your chosen tool (AWS CDK, CloudFormation, or Terraform).

2. Define a VPC with at least two public subnets in different Availability Zones.

3. Create an Application Load Balancer (ALB) in the VPC, spanning the public subnets.

4. Launch at least two EC2 instances in different Availability Zones, each running a simple web application.

5. Create a target group and register the EC2 instances with it.

6. Configure the ALB to forward traffic to the target group.

7. Implement appropriate security groups for the EC2 instances and the ALB.
