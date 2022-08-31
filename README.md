MIGRATION OF EBS INSTANCE
EC2 Instances have their data stored on EBS volumes which are persistent disks that provide fast storage for your data. They may be viewed as the hard disk of your server.
One way of creating a copy of an EBS instance to another account is by following these simple steps
    1.	Create a snapshot of the EBS Volume
    2.	Share the snapshot with the secondary account
    3.	Create a copy of the snapshot in the secondary account
    4.	Create an AMI from the new snapshot
    5.	Create a new EC2 instance from the AMI
    6.	If there is no need for the original snapshot, delete it. 
