# WEB SOLUTION WITH WORDPRESS 

Start an EC2 instance designated as the "Web Server." Create three 10 GiB volumes in the same AZ as your web server EC2.

Attach each of the three volumes to your Web Server EC2 instance one at a time.
![EBS volumes attached](./images/the%20EBS%20volumes.png)

For a list of the block devices connected to the server, use the `lsblk`command on the terminal and make sure you see `xvdf` `xvdg` `xvdh` as shown below:

![block devices attached to the server](./images/lsblk.png)

