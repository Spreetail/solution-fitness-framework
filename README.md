# The Solution Fitness Framework
Solution Fitness is an aggreagte measure of the overall quality, maintainability, and resiliency of a software system. It is an aggregate measure made up of smaller components called Solution Fitness Parameters. Each parameter is an indicator of healthy software. 

The original motivation behind the solution fitenss framework is the [Joel Test] (https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/), a popular "napkin-math" style test to determine the effectiveness of software teams. 

## History of the Metric @ Spreetail
The health of software systems has traditionally been a “feeling” without any specific, objective traits to indicate what constitutes a healthy system. Teams have struggled to objectively define software health for many years. 

For example, legacy systems are commonly considered unhealthy, with traits like repeated code and less-than confident development. This general “feeling” can be confirmed through other subjective side-effects, like long build times and long spin-up times for new developers working on the system. Refactoring work put into legacy systems can improve subjective feelings, but the subjective nature of the changes make them a risk to include in development sprints. 

Spreetail is a measurment driving organization, so the subjective feelings surrounding legacy systems have been difficult to address without the ability to measure the positive effects of refactoring. 

## Measurement Method
Overall Solution Fitness is measured as average percent complete. Percent complete is measured through the evaluation of each Solution Fitness Parameter across each critical codebase. A cross-functional team sets acceptance criteria for each Solution Fitness Paramter and evaluates how well each solution adheres to the parameter requirements. Adherence to each of the parameters will give a codebase a percent complete metric. Percent complete metrics are averaged across all critical codebases to arrive at an average percent complete.
  
### Critical Codebases?
Codebases are defined as critical if they meet any of the following criteria: 
- Deployed software used directly by the business (i.e. CRM Systems, WMS Systems)
- Infrastructure components that support deployed software (i.e. Redis, RabbitMQ)
- Libraries or components that are used by deployed software (i.e. user interface components, Shared Libraries).

## Solution Fitness Parameters
- [Individual Owner](solution-fitness-parameters/individual-owner.md)

