# How _Uber_ switched from monolithic architecture to microservice architecture
***
#### Monolithic Architecture

When **Uber** was a startup they built their solution for a single offering in a single city. 
Features such as passenger management, billing, notification features, payments, trip management and driver management were composed within a single framework.
As they grew they had problems arised :

+ All the features had to be re-built, deployed and tested again and again to update a single feature.
+ Fixing bugs became extremely difficult in a single repository as developers had to change the code again and again.
+ Scaling the features simultaneously with the introduction of new features worldwide was quite tough to be handled together. 


![Mono](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/02/Monolithic-Architecture-Of-UBER-Microservice-Architecture-Edureka-768x730.png)
 
#### Microservice Architecture

To prevent any these problems in the future **Uber** decided to transition from monolithic to microservices.
+ The major change that we observe here is the introduction of API Gateway through which all the drivers and passengers are connected. From the API Gateway, all the internal points are connected such as passenger management, driver management, trip management and others.

+ The units are individual separate deployable units performing separate functionalities.
-For Example: If you want to change anything in the billing microservices, then you just have to deploy only billing microservices and don’t have to deploy the others.

![Micro](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/02/Microservice-Architecture-Of-UBER-Microservice-Architecture-Edureka-768x762.png)
 
 
