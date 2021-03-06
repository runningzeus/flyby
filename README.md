
## FlyBy

----------

### Concept

For a product, that follows Continuous Delivery principles, a commit can potentially result into a release candidate. However, in reality, binary resulting from building a commit, moves through various environment, gets automatically and manually verified and ultimately finds its cozy little corner in binary artifactory, to live for that blessed moment, when business (or whoever empowered) would take a decision to allow the commit to be meeting with world. 

FlyBy is a big fan of this concept. To it, a commit, is THE lowest level granularity for a change. It is legitimate to treat a commit as lowest building block of a change that development team is bringing into the product. 

On other side, from a top down approach, a continuous delivery pipeline, is THAT machinery, that promises to ship a commit from developer's workstation to production environment, validating readiness of it in each step. 

FlyBy, is an ambitious attempt, which wants to formalize this process.
It's ultimate goal is to help you declare arbitrary workflow, that can speak eloquently with human and tools, to get the work done. 
It helps you design your flow, execute and govern it. You should have enough evidence around a commit in each stage of CD pipeline, to be able to derive WHAT has been performed around it, WHAT is its origin and so on. 

Architecturally, FlyBy is a combination of loosely coupled services, communicating through well defined REST interfaces. FlyBy communicates with tools and services via adapters. 

This way you can define the workflow once.
The workflow defined thus serves the purpose of templates. 
Powered by its adapter eco - system, FlyBy helps you port the workflow definition to be supported by newer sets of tools

TBD 

 1. Define technology tasks 
 2. Define feature specification for 1.0.0
 3. Define configuration management posility 