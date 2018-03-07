# ec2-instance-not-connecting-after-adding-elastic-ip-address
how to fix ssh connection to ec2 instances after associating elastic ip address

Follow this tutorial to fix first.

[How do I troubleshoot problems connecting to an instance in a VPC?](https://aws.amazon.com/premiumsupport/knowledge-center/instance-vpc-troubleshoot/)


1. Remove the keygen save in your local computer

    ```ssh-keygen -R ec2-xx-xx-xx-xx.eu-west-2.compute.amazonaws.com```
    
2. Go to the root directory where you have saved you keypair and run below command

    ```chmod 600 yourkeypair.pem```
    
  
