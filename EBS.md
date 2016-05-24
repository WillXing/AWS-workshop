## EBS

### Create Volume

*There are two ways to create EBS volume, one is create during lunching EC2 instance, now we are doing the second way*

1. Go to `ELASTIC BLOCK STORE`>`Volumes`.

2. Click `Create Volume`.
    * **Volume Type:** different type have different I/O and Throughput.
    * **Availability Zone:** should be same with the EC2 instance you want to attach with.
    * **Snapshot ID:** choose snapshot, and create the EBS have same content with it.
    
    ![Create Volume](./images/ebs/create-volume.pn)