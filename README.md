# FinOps Multicloud Evaluator

Multi-cloud evaluator with multiple parameters and case-scenarios

## Why another calculator/estimator tool ?

Well, consider the following scenario :

There are differences in the way of how cloud providers estimates resources, calculates workloads and make data available, so customers can make more accurate and realistic assumptions about their billing. Along with that, having different tools and approaches brings us to a estimation swamp, making the task of cost estimation as well control-center much more complex and unfordable.

## How do we plan to help reduce this complexity ?

First and foremost, our approach is to think about the variances and variables needed to take more realistic and feasible cost usage, bringing API access, resources creating via Infrastructure as Code (IaC) and datasets creation in a standardized way. No matter the cloud provider, is just to add it to our inventory, and we're done !

## TODO 

Here are some stuffs that needs to be done to accomplish our basic goals :

- [ ] Define which ways providers interfaces are going to be accessed 
- [ ] Define datasets formats and ways to visualize
- [ ] Define which ways calculations are getting done and presented
- [ ] Take FOCUS entries and converters to be used internally
- [ ] Define interfaces to Terraform and possibly Terraform Cloud for when creating resources 
- [ ] Research and test possible interfaces or even plugin for Internal Development Platform (IDP) like Backstage
- [ ] Make tests and integrations with tools like Infracost as well others out there
- [ ] Include possible ways of calculating estimations and costs usage in different currencies 
- [ ] Create possible ways for calculating differences in taxes and regions