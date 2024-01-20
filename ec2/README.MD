EC2- Module

Inputs
    ami(optional): AMI ID is optional. Default ami is ami-03265a0778a880afb which is centos8 from Join DevOps.
    instance_type(optional): default value is t2.micro
    tags(optional): default value is empty

Outputs
    Public_ip: public_ip of the instance
    Private_ip: private_ip of the instance
    id: instance id of the instance