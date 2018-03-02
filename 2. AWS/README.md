# Spinning Up Servers on Amazon Web Services (AWS)

## Signing up for AWS

```
https://portal.aws.amazon.com/billing/signup#/start
```

## Launching an EC2 instance

AWS instructions
```
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html
```

1. Go to EC2 Page and Select region in the top right of the toolbar
```
https://console.aws.amazon.com/ec2/v2/home?region=us-east-1#Home:
N. Virginia
```

2. Click "Launch Instance"
```
https://console.aws.amazon.com/ec2/v2/home?region=us-east-1#LaunchInstanceWizard:
```

3. Select an OS
```
Ubuntu Server 16.04 LTS (HVM), SSD Volume Type
```

4. Choose an Instance Type (vCPU, Memory, Network Performance)
```
t2.micro
```

5. Click "Next: Configure Instance Details"

6. Click "Next: Add Storage"

7. Select from the Dropdown under "Volume Type"
```
Select Magnetic
```

8. Click "Next: Add Tags"

9. Click "Add Tag"
```
Key: Name, Value: Your Custom Instance Name
```

10. Click "Next: Configure Security Group"

11. Under "Security group name:" enter
```
"Open"
```

12. Click "Add Rule"

13. Select from the "Type" Dropdown
```
All Traffic
```

14. Select from the "Source" Dropdown
```
Anywhere
```

15. Click "Review and Launch"

16. Select from the Pop-up
```
Continue with Magnetic as the boot volume for this instance.
```

17. Click Next

18. Click Launch

19. Select from the First Dropdown
```
Create a new key pair
```

20. Name your Key, Download it (Do not lose it), and save it in your Home Directory (~), Accept Terms, and Click "Launch Instances"

21. Observe the Status of Your Instance under "Instance State" and "Status Checks":
```
https://console.aws.amazon.com/ec2/v2/home?region=us-east-1#Instances:sort=instanceState
```

22. Start, Stop, Terminate, Reboot by Right Clicking Instance Row
```
Instance State > Start | Stop | Terminate | Reboot
```
