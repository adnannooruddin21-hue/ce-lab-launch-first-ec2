# Lab Solution
**Learning Reflections**

1. What surprised you most about launching a cloud server?

Answer:

Launching a cloud server was much faster and easier than expected. I was able to create an EC2 instance, configure networking and security, and connect to it within a few minutes without purchasing or installing any physical hardware.

2. How is this different from setting up a physical server or local VM?

Answer:

A cloud server can be created on demand through the AWS Management Console or AWS CLI, while a physical server requires purchasing hardware, installation, and manual configuration. Compared to a local virtual machine, AWS provides scalable infrastructure, public networking, managed storage, and high availability without depending on my personal computer.

3. What security concerns did you need to consider?

Answer:

I needed to secure the EC2 instance by:

Restricting SSH (port 22) access to my IP address.
Using a secure SSH key pair instead of passwords.
Configuring Security Groups to allow only required ports (such as 80 and 443).
Following the principle of least privilege with IAM users and roles.
Keeping the operating system updated and protecting sensitive credentials.

4. How long would this process take with traditional infrastructure?

Answer:

With traditional infrastructure, setting up a new server could take several days or even weeks due to hardware procurement, installation, networking, and configuration. Using AWS EC2, the same process can be completed in just a few minutes, making cloud infrastructure much faster, more flexible, and easier to scale.