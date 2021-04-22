# Cloud Computing

### What is cloud computing?
- providing and accessing services over the internet, rather than setting up and maintaining physical data centres on site
- pay as you go pricing

### 3 benefits
- quicker and easier to set up than a centre on site
- add and remove capacity at will
- can deploy an application worldwide easily

### Best use cases/who is using it in the industry
- Businesses of all sizes and areas
- Amazon, Microsoft, Google all provide cloud services
- Pinterest, Etsy, Zoopla use it

### What is AWS
- Amazon Web Services
- a range of cloud computing services, such as CloudSearch to create a search engine for your website, Snowball to allow transfer of large amounts of data

### 3 advantages of AWS
- reliable
- secure
- single point of entry to many services

### Who is using AWS?
- used by Netflix, Uber, Airbnb, Instagram

### Types of cloud
- public cloud
    - e.g. AWS, Google Cloud, Microsoft Azure
    - Netflix only pays for when film is being watched
    - software as a service
- on premises/private
    - secure as less connected to outside
- hybrid cloud
    - bridges the private and public cloud
    - banks, some government
    - sensitive data is saved in a private cloud on premises
    - publicly available information goes on the public cloud
    
![Public, Private and Hybrid Cloud diagram](https://www.cisecurity.org/wp-content/uploads/2019/06/hybrid-cloud-environment.png)
    
### Scaling
- scaling up is making a component larger or faster
- scaling out is making more servers to handle load

### AWS Setup
- Sparta Global naming convention for EC2
    - name of your group
    - your name
    - Eng84_isobel_app
- Security group works on the instance level as a firewall for your machine
- SSH works on Port 22
- DO NOT push any keys etc. to Git-hub

### Monolith architecture
- everything in the same "box"
- any changes made in the app means the entire machine has to restart
- the UP time takes longer and longer

### Two-tier architecture
- 2 different machines on the same cloud, eg:
- Ubuntu 16.04 app EC2 with Nodejs and Nginx - Public IP
- Ubuntu 16.04 for Mongo DB - No public IP, only accessible from the app machine
- application and database as two tiers
- can restart the app without restarting the database

![Two tier architecture diagram](https://i.pinimg.com/originals/7d/22/da/7d22dae92ba8494d062aab040bfc4209.png)

### Three tier architecture
- Presentation layer, application layer, and data layer

![Three tier architecture diagram](https://www.jinfonet.com/wp-content/uploads/2017/12/3-tier_architecture-1.png)

### EC2
- Elastic Compute Cloud
- Infrastructure running in the cloud
- Very flexible and scalable

### Subnets
- public or private
- security for your virtual machine
- network within a larger network
- improves network routing efficiency - network traffic can travel a shorter distance and avoid unnecessary routers
- e.g. create one subnet for teachers and one for students

### Security groups
- works as a firewall on the instance level

### VPC
- Virtual Private Cloud
- allows you to create a private, secure place on the public cloud

### Regions and Availability Zones
- https://aws.amazon.com/about-aws/global-infrastructure/regions_az/
- use the nearest AZ to the user
- if one data centre goes down traffic is redirected to a nearby one

### Multi-cloud architecture
- deploying an application on multiple clouds to make it highly accessible
- expensive, so used by big companies