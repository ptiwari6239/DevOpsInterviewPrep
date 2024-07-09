## CICD 

## What is CI 
- It is practice where developer frequently integrate their code changes into a shared repository , often multiple times a day.
- By integrating regularly, we can detect  errors quickly and improve the quality of software . Automated test run on each integration to ensure new code does'nt break the existing code base.

## What is CD
- CD is extenstion of CI part that automates the deployment of the code changes to production enviroment . This means every changes that pases that CI part is automatically deployed to the production enviroment .
- This ensure that the software can be released at any time, reducing the time to market and allowing for faster delivery of new features and bug fixes.


## What is Continuous Delivery 
- Continuous Delivery ensures that the software can be released to production at any time. This means  the software is kept in a deployable state throughout its lifecycle.
- it allows teams to release new features, improvemnts, and bug fixes more frequently .

## What are some popular CI/CD tools?
- jenkins
- circleCI
- Bamboo
- Team City
- Codefresh

## Explain the benefit of the CI/CD Pipeline
- Faster time to market 
  - Automated  processes
  - Frequent Releases
- Improvde code quality 
  - Automated Testing
  - consistent Building
- Increased Developer Productivity
  - Reduced manual efforts
  - faster feedback loop
- Enhanced collaboration 
  - Centrilized codebase
  - Transparency
- Reduced Risk 
  - Early bug detection 
- Scalibility 
- Cost Saving

## Difference between declarative and scripted pipeline 
- Scripted Pipeline 
  Scripted Pipeline is the original pipeline syntax for Jenkins, and it is based on Groovy scripting language. In Scripted Pipeline, the entire workflow is defined in a single file called a Jenkinsfile. The Jenkinsfile is written in Groovy and is executed by the Jenkins Pipeline plugin. Scripted Pipeline provides a lot of flexibility and control over the workflow, but it can be more complex and verbose than Declarative Pipeline

- Declarative pipeline 
  Declarative Pipeline is a more recent addition to Jenkins and provides a more structured and simpler syntax for defining pipelines. Declarative Pipeline is based on the Groovy programming language, but it uses a Groovy-based DSL (Domain-Specific Language) for pipeline configuration.. The main benefit of Declarative Pipeline is its readability and ease of use, as it is designed to be more intuitive and less verbose than Scripted Pipeline.

## Problem faced while learning jenkins
- Pipeline Syntax Error 
   - The first few times I ran the pipeline, I encountered syntax errors that were hard to debug. The error messages were sometimes not very descriptive, which made it difficult to pinpoint the exact issue.
- Environment Configuration
    - Setting up the Jenkins environment to support our build and deployment tools (like Maven and SSH) required proper configuration and sometimes additional plugins. This setup process was time-consuming and prone to errors.
- Managing Credentials
  - Securely managing credentials (like SSH keys and passwords) within the pipeline was another hurdle. Initially, I struggled with getting the Jenkins Credentials Plugin to work correctly and securely inject credentials into the pipeline.
