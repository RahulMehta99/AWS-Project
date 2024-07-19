

Step to host website on AWS
----------------------------------------------
1. Login to  AWS console [image](https://github.com/user-attachments/assets/099d83b0-aeb6-43c2-9052-ac3192b07a0d)

2. create ec2 machine [image](https://github.com/user-attachments/assets/ecbcfeb1-fbb4-4ef0-8c8f-b0910b7a62f3)

3. configure security group(ssh -22 for admin only)(80 - for normal traffic) [image](https://github.com/user-attachments/assets/36f0fd98-5341-4a0d-81b1-d99a01f53acf)

4. connect to ec2 machine

5. install httpd webserver in machine(used to run web app)
 
 /     sudo su   /
 /  yum update -y   /
 / yum install httpd -y [image](https://github.com/user-attachments/assets/56e3e8d9-b04c-4fa3-aa96-8802c52cb70c)  /

 cd /var/www/html
 create website 
 service httpd start [image](https://github.com/user-attachments/assets/c44c106c-a66b-4632-a0bc-975b1d0b422d)

7. access website from browser using ec2 public ip or DNS [image](https://github.com/user-attachments/assets/bdc69fdf-e06b-4043-9a71-f5de3a72d811)
