# AWS Projects Showcase
A collection of AWS Applications 
---
## **[Web Application Architcure](https://github.com/rjm3q/AWS-Projects/tree/main/Architecure-Focused)**

### Using an EC2 instance and RDS build a website using best AWS Architecure practices
- [ ] What was designed
- [ ] Why use these services
- [ ] How they work together
- [ ] Add Architecure Diagram
---
## **Text-to-Speech Application**

### Using a Lambda function and Polly create an application that takes text input from the user to convert into speech
- [ ] Setup Lambda
- [ ] Choose languages and voices
- [ ] Create simple web interface
---
## **Lambda Email Application**

### Using a Lambda function and SES create an Email application to reach out to a large audience

- [ ] Setup Lambda
  - [ ] Import CSV in dataabse
  - [ ] read recipient data
  - [ ] Configure SES to send emails
- [ ] Setup S3 bucket to store files
  - [ ] CSV with email addresses
  - [ ] Email Message
- [ ] S3 Event trigger to monitor for csv changes
---
## **CI/CD Pipeline**

### Build a CI/CD pipeline with Github actions and AWS Code pipeline to automate the build, test, and deploy process

- [ ] Host project code on GitHub
  - [ ] Setup version control
  - [ ] Congifure build env with GitHub actions
- [ ] Create AWS Code Pipeline
  - [ ]  Define Build phase
  - [ ]  Define Test phase
  - [ ]  Define Deploy phase
  - [ ]  Define deployment targets (AWS Compute Service)
  - [ ]  Configure Manual Approval
- [ ] Rollback strategy for failed deployments
---
## **Virtual Assistant Application**

### Build a Virtual Assistant application using a lambda function and AWS ASK

- [ ] Define custom Alexa skill
- [ ] Create Lambda to execute actions from voice
  - [ ] Play Music
  - [ ] Set Reminder
  - [ ] Book event space
- [ ] Connect the Lambda and ASK 
---
## **Content Recommendation Application**

### Using Sage Maker and AWS MLS to create an AI/ML app that will recommend contect based on past online behavior

- [ ] Setup Sage Maker
  - [ ] Gather user data
- [ ] Configure ML process (k nearest neighbor)
  - [ ] train data
---
## **Document Convert-o-matic**

### Using a Lambda function create an application to allow users to transform files

- [ ] Setup lambda
  - [ ] Take Input
  - [ ] Convert
  - [ ] Produce Output
- [ ] Create UI
  - [ ] Web Based
  - [ ] CLI Based
- [ ] Option to download or Display
- [ ] Delpoy and host on Github webpage
---

# learn-cantrill-io-labs

![DEMOGRID](https://github.com/acantril/learn-cantrill-io-labs/raw/master/demogrid.png)

Welcome .. this repo stores a collection of freely available demos and mini projects for AWS (and in the future other cloud platforms)
These demos are available in three ways:-

- here in instruction & architecture diagram form for free
- as part of [https://learn.cantrill.io](https://learn.cantrill.io) courses - including theory lessons and guided videos.
- **some** of the popular mini projects have been upgraded with video guides on this repo (people buying my courses supports this)

**💰💰 You can be paid to create new mini projects for this repo ... [click here](https://github.com/acantril/learn-cantrill-io-labs/blob/master/get-paid-to-create-projects.md) for more info 💰💰**  
*this is made possible via my courses at [learn.cantrill.io](https://learn.cantrill.io) so if you need any training content please check this out*  

The free versions here are fully functional, with instructions & architecture diagrams and are maintained by me.

All demos have a structure ...
-  Most are started using a `1-Click Deployment` .. click a link, check a box, click create stack and wait until complete.
- `01_LABSETUP` contains assets required for the DEMO if required - **many are linked directly from the instructions.**
- `02_LABINSTRUCTIONS` contains text instructions and architecture diagrams - **most of these are directly linked from the instructions.**

A full range of Video guided versions are available in my courses at https://learn.cantrill.io

**I give free course credits for any bugs submitted via PR so please submit fixes for any issues you find**

## VIDEO GUIDED MINI PROJECTS (videos linked inside and on [Youtube](https://youtube.com/c/learncantrill))

- [Web Application Architecture Evolution](https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-elastic-wordpress-evolution)
- [Implement a Serverless Application](https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-serverless-pet-cuddle-o-tron)
- [Implement a Dynamic, BGP Based, Highly-Available Site-to-Site VPN](https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-hybrid-bgpvpn)
- [Building a serverless application using Web Identity Federation](https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-cognito-web-identity-federation)
- [CatPipeline - code commit, build, deploy & pipeline using containers and ECS](https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-codepipeline-catpipeline)
- [Hybrid DNS using Route53 Inbound and Outbound Endpoints](https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-hybrid-dns)
- [Implement a simple client VPN](https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-client-vpn)
- [Pixel Art Image Processing Workflow - Pixelator 3000](https://github.com/acantril/learn-cantrill-io-labs/tree/master/00-aws-simple-demos/aws-lambda-s3-events)
- [Database Migration using DMS](https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-dms-database-migration)
- [Implement Hybrid Directory - On-premises & AWS](https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-hybrid-activedirectory)

## TEXT ONLY MINI PROJECTS

## UNDER CONSTRUCTION OR BROKEN PROJECTS (DON'T USE) - fixes in progress

- [Patching AWS and On-premises using Systems Manager Patch Manager](https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-patch-manager)
