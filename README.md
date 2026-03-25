# Launching-My-First-EC2-Instance-on-AWS
Starting my journey in cloud computing has been exciting, and one of the first milestones I achieved was launching my first virtual server using Amazon EC2 on Amazon Web Services.
To launch my EC2 instance I followed the following steps;
## Step 1: Accessing AWS
- I began by logging into the AWS Management Console and navigating to the EC2 dashboard. This is where you can create, manage, and monitor virtual servers.

## Step 2: Launching the Instance
- Next, I clicked Launch Instance and configured the basic settings:
### Instance Name: My First EC2 Instance
- Operating System: Amazon Linux
### Instance Type: t2.micro (eligible for the free tier)
- I also created a key pair, which is used to securely connect to the server.

## Step 3: Setting Security Rules
- Security is important in cloud environments, so I configured a security group to control incoming traffic.
- I allowed:
  - SSH (Port 22) – to access the server remotely
  - HTTP (Port 80) – to allow web traffic
- Security groups work like a firewall that controls who can access the instance.

## Step 4: Launching the Server
- After reviewing the configuration, I launched the instance. Within a few seconds, the server was up and running in the cloud.

## Step 5: Connecting to the Instance
- Using the key pair I downloaded earlier, I connected to the server using SSH from my terminal. It was exciting to successfully access my cloud server and run commands on it.

# What I Learned
- This experience helped me understand several important cloud concepts, including:
  - How virtual servers are created in the cloud
  - The role of security groups in protecting resources
  - How key pairs enable secure server access
  - How quickly infrastructure can be deployed using AWS
# Final Thoughts
- Launching my first EC2 instance was a great learning experience and an important step in my cloud computing journey. It showed me how powerful cloud platforms like AWS can be and motivated me to continue learning more about cloud technologies.
