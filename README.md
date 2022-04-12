# Urbanclap-Backend-Design
#### Problem Statement:
Design & Develop a Backend System for Application similar to Urban Clap, The business idea is to bridge the gap between service providers and service receivers.
Service Receivers (Consumers) can hire electricians, yoga trainers, interior designers, etc. They can avail all these services via placing an order through the Mobile App.
When a service is requested, Admin team will assign the request to the Service Providers according to the Area or Availability, the professionals in that area get a notification. They can either accept or deny. 
If the request is accepted, the user will get notifications with respect to the booking confirmation and service provider details & Provider will also get the Job Description.


#### Tools used:
* Eureka (Service Discovery)
* Zuul ( API Gateway for implementing routing)
* Jaeger for distributed tracing
* Docker as deployment tool(docker compose file)

#### Execution instruction:
Execute docker compose file using below command, wait for couple minutes, all services will be deployed inside single container.

`docker compose start`

Refer [Design document](https://github.com/VatsalHirpara/Urbanclap-Backend-Design/blob/main/Design%20document.pdf) for REST endpoints and more details
