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

### Two-tier architecture
- 2 different machines on the same cloud, eg:
- Ubuntu 16.04 app EC2 with Nodejs and Nginx - Public IP
- Ubuntu 16.04 for Mongo DB - No public IP, only accessible from the app machine

### EC2
- Elastic Compute Cloud
- Infrastructure running in the cloud
- Very flexible and scalable