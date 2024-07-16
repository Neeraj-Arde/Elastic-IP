# Elastic-IP
Uses of Elastic IP

```bash
As we have seen in instance deployment session. Public IP will we get released after every reboot and It can cause a choas in productions due to rechability.
To avoid such things from happen we can you an Elastic IP as a solution. Elastic IP is IP which will stick to the instance even if it is in stopped state or reboot.
Hence it will be easy for us to manage the network and there will be no need to change whole configuration after every reboot.
```
# How to implement
Steps as follows
```bash
1. Go to EC2 dashboard and navigate to Elastic IP.
2. Click on Allocate Elastic IP Address. It allocate an IP to our AWS account.
3. Select Amazon's pool of IPv4 addresses and Select network border. Click on allocate.
4. Now IP will be visible in our account and we need to associate the IP with our instance.
5. Select the IP and click on actions and select associste IP address.
6. Select instance and choose the instance which want to attach the IP and click on associate.
```
