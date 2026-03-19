# AWS Certified Cloud Practitioner CLF-C02 2026
[[slides link]](https://courses.datacumulus.com/downloads/certified-cloud-practitioner-zb2/)

## Introduction
1. Example of question: Which AWS service would simplify the migration of a database to AWS?
    1. AWS Storage Gateway
    1. AWS Database Migration Service (correct)
    1. Amazon EC2
    1. Amazon AppStream 2.0
1. Pay attention to distractors, because aws has more than 200 services
1. Instructor Stephane
1. Types of certification
    1. Foundational
    1. Associate
    1. Professional
    1. Specialty
1. $100 free credits

### Creating an AWS Account
1. Free plan to the course
1. Needs credit card in free plan
1. Needs activation

### What is Cloud Computing
1. how websites work: client > network > server
    1. IPs
1. what is a server composed of? CPU, RAM, storage data, data base, network (DNS, routers, switch)
1. IT terminology: network, router, switch
1. Traditionally: local servers, data centers
    1. space, power supply, cooling, maintenance, disaters
1. Advantages: on-demand-delivery, pay-as-you-go pricing, right type and size
1. Deployments: private cloud, public cloud, hybrid cloud
1. 5 characteristics: on-demand self service, broad network access, multi-tenancy and resource pooling, rapid elasticity and scalabity, measured service
1. 6 advantages: CAPEX, OPEX, reduced TCO and OPEX, benefits from massive economies, stop guessing capacity, increase speed and agility, stop spending money running and maintaining data centers, go global in minutes
1. Problems Solved by the cloud: flexibility, cost-effectiveness, scalability, elasticity, high-availabitliy, agility

### The diferent types of cloud computing
1. IaaS (EC2), PaaS (Elastic Beanstalk), SaaS (Rekognition)
1. Pricing fundamentals: compute, storage, data transfer (OUT)

### AWS Cloud History
1. 2002 internally, 2003 infrastructure, 2004 publicly SQS, 2006 re-launched (SQS, S3, EC2), 2007 europe
1. cloud number facts: 2023 90 bilion ARR, 31% of market in 2024, 1 million active users
1. use cases: mac donalds, 21st century fox, activision, netflix

### AWS Global Infrastructure
1. regions, availability zones, data centers, edge locations
1. regions: all around the world, us-east-I, eu-west-3, is a cluster of data centers, services are region-scoped,
1. how to choose an AWS region: compliance, proximity, available services, pricing
1. availability zones: min is 3, max is 6, ap-southeast-2a
1. edge locations: 400 points of presence
1. console: global services vs region-scoped

### Tour of the console & services UI Update
1. console home > region
1. services
1. compute
1. search bar
1. features, blogs, documentation
1. route 53 (global)
1. EC2 (region)
1. https://aws.amazon.com/about-aws/global-infrastructure/

### Shared Responsability Model diagram
1. https://aws.amazon.com/compliance/shared-responsibility-model/

### AWS Acceptable Use Policy
1. https://aws.amazon.com/aup/

## IAM - Identity and Access Management

### Introduction
1. global service
1. root account, users, groups
1. users can be in a multiple groups or in anyone
1. permissions
1. account alias
1. sign in as IAM user
