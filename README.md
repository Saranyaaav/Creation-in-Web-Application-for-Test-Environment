 # CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
## AIM
To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT
Creating a web application for a test environment is essential to provide developers and testers with a dedicated platform to simulate, test, and validate software functionalities. The challenge lies in building an easy-to-use, scalable, and efficient application that supports realistic testing scenarios, automates workflows, and ensures smooth collaboration while minimizing setup and maintenance efforts.

## ALGORITHM
 ### Steps 1: 
 Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.
 ### Steps 2: 
 Connect to the instance using SSH and install a web server like Apache
 ### Steps 3:
 Create a simple HTML file in the server's default directory with basic content for testing.
 ### Steps 4:
 Access the instance's public IP in a browser to verify the HTML page is displayed.
 
 
## COMMANDS
### To install httpd:
```
yum install httpd -y
```
### To enable and start httpd :
```
systemctl enable httpd
systemctl start httpd
```
### Create a simple HTML page :
```
cd /var/www/html
sudo nano nandha.php
```

```php
<!Doctype html>
<html>
<body>
<h1>Hello Friends</h1>
<?php
echo "Hello World";
?>
</body>
</html>
```

### REG NUMBER:212223040188
### NAME:SARANYA V

## OUTPUT
## TERMINAL:
![Screenshot 2024-11-21 211223](https://github.com/user-attachments/assets/fc14897f-1e62-4c21-90f0-b9ce3f9ee7cc)
## WEBSITE:
![Screenshot 2024-11-21 211409](https://github.com/user-attachments/assets/051b5cab-8940-46b9-9352-00e7bcdd9810)

## RESULT
Thus the web application for test environment has successfully been created and executed.

  


