# How to use Digits
I assume you have AWS account and you have created virtual machine as shown in the [Video](https://www.youtube.com/watch?v=QZaAcl_F9R0&list=PLAeuFh2kplHsM3azmgg0qRxgqgg__m_3_). 
This tutorial would help you to solve following questions
## How do I see contents/access my vertual machine where Digit is running ?
Assuming you have key (.pem) with you:
```
chmod 600 your_key.pem
ssh -i your_key.pem ubuntu@ipv4public_address

```
## How do I trasfer data from Local machine to Ec2 ?
``` 
scp -i your_key.pem -r path/your_data ubuntu@ipv4public_address:~/path_on_Ec2/
```



