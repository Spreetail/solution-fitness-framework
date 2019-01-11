# The Solution Fitness Framework
Solution Fitness is an aggregate measure of the overall quality, maintainability, and resiliency of a software system. It is an aggregate measure made up of smaller components called Solution Fitness Parameters. Each parameter is an indicator of healthy software. 

The original motivation behind the Solution Fitness Framework is the [Joel Test](https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code), a popular "napkin-math" style test to determine the effectiveness of software teams. 

[Nebraska.Code() Presentation](presentation/index.html)

## Solution Fitness Themes
### Make Health Objective
### Journey > Destination
### Forced Visibility
### Distributed Professional Development
### Increased Stakeholder Trust

## History of the Metric @ Spreetail
The health of software systems has traditionally been a “feeling” without any specific, objective traits to indicate what constitutes a healthy system. Teams have struggled to objectively define software health for many years. 

For example, legacy systems are commonly considered unhealthy, with traits like repeated code and less-than confident development. This general “feeling” can be confirmed through other subjective side-effects, like long build times and long spin-up times for new developers working on the system. Refactoring work put into legacy systems can improve subjective feelings, but the subjective nature of the changes make them a risk to include in development sprints. 

Spreetail is a measurement driving organization, so the subjective feelings surrounding legacy systems have been difficult to address without the ability to measure the positive effects of refactoring. 

## Measurement Method
Overall Solution Fitness is measured as average percent complete. Percent complete is measured through the evaluation of each Solution Fitness Parameter across each critical codebase. A cross-functional team sets acceptance criteria for each Solution Fitness Parameter and evaluates how well each solution adheres to the parameter requirements. Adherence to each of the parameters will give a codebase a percent complete metric. Percent complete metrics are averaged across all critical codebases to arrive at an average percent complete.
  
### Critical Codebases?
Codebases are defined as critical if they meet any of the following criteria: 
- Deployed software used directly by the business (i.e. CRM Systems, WMS Systems)
- Infrastructure components that support deployed software (i.e. Redis, RabbitMQ)
- Libraries or components that are used by deployed software (i.e. user interface components, Shared Libraries).

## Solution Fitness Parameters
Each Solution Fitness Parameter is an indicator of a quality application. A cross-functional sets the requirements for each parameter that applications must meet. These requirements are meant to be inclusive - they have easy to satisfy requirements. This is done on purpose to build momentum for more applications meeting more solution fitness parameters. 

For some parameters, the criteria is very easy to communicate. For example, the "readme" style parameters only need a brief description in each category for the parameter to be considered satisfied. This causes problems for other parameters because the requirements are too easy. The "Tests" parameter only specifies that a single test is written for the code-base. 

These parameters are meant to be indicators of a quality system. If a system meets the requirements of a majority of the parameters, then it is probably running in production, easy (to moderate) to change, and can be worked-on by more than one developer. 

### Current Solution Fitness Parameters
- [Individual Owner](solution-fitness-parameters/individual-owner.md)
- [Group](solution-fitness-parameters/group.md)
- [Readme - Functionality](solution-fitness-parameters/readme-functionality.md)
- [Readme - Local Development](solution-fitness-parameters/readme-local-development.md)
- [Readme - Runbooks](solution-fitness-parameters/readme-runbooks.md)
- [GitIgnore](solution-fitness-parameters/gitignore-file.md)
- [Source Control](solution-fitness-parameters/source-control.md)
- [Environment Awareness](solution-fitness-parameters/environment-awareness.md)
- [Tests](solution-fitness-parameters/tests.md)
- [Continuous Integration](solution-fitness-parameters/continuous-integration.md)
- [Continuous Deployment](solution-fitness-parameters/continuous-deployment.md)
- [Continuous Quality](solution-fitness-parameters/continuous-quality.md)
- [Application Performance Management](solution-fitness-parameters/apm-integration.md)
- [Hound](solution-fitness-parameters/hound.md)
- [Service Discovery](solution-fitness-parameters/service-discovery.md)
- [Logging](solution-fitness-parameters/logging.md)

### Parameters != Quality
It is important to note that Solution Fitness Parameters are indicators of a quality system - they are not provers of a quality system. It is still possible to satisfy the requirements of multiple parameters but still have a unhealthy, low-quality system. 
