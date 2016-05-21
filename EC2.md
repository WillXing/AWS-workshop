## EC2

### Create Key Pair

1. Pick `NETWORK & SECURITY` > `Key Pairs`

2. Create key pair, and download `.pem` file

### Create Instance

1. Open the Console.

2. Go to EC2 console, click `Lunch Instance` button.

    *You can check [this page](http://aws.amazon.com/cn/ec2/pricing/) for pricing detail*

3. Choose the Amazon Machine Image you want to use.

    *Some of the AMI are not free tier eligible, choose one you like*
    *Suggest use `Amazon Linux AMI` for learning and testing*

4. Choose an Instance Type.

    *Different Instance type have different CPU, Memory, disk... Choose one that suit your requirement*
    *For now, only `t2.micro` are free tier eligible*

5. Configure you instance.

    *Just use default value here will also works, hover on the information icon, will show further details*
    
    ![Configure](./images/ec2/configure.png)
    
6. Add Storage.

    *Add Storage for your instance, the root volume will be added by default, you can add your new volume*
    *The new volume which type is `ELB` will persists independently from the lifetime of an instance*
    *There are two volume type column, in the second one, you can choose SSD or HDD you want for this volume*
    
    ![Add Storage](./images/ec2/add-storage.png)
    
     