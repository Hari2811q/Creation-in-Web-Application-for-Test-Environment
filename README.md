 # CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
  ## AIM
       To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT
    Explain about the Experiment.

## ALGORITHM
## Steps 1:

Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.

## Steps 2:

Connect to the instance using SSH and install a web server like Apache

## Steps 3:

Create a simple HTML file in the server's default directory with basic content for testing.

## Steps 4:

Access the instance's public IP in a browser to verify the HTML page is displayed.
## COMMANDS
## To install httpd: 

yum install httpd -y
## To enable and start httpd :

systemctl enable httpd
systemctl start httpd



## OUTPUT
Terminal:
![image](https://github.com/user-attachments/assets/682a5a86-3716-4ec5-adca-480d08415abe)
Website:
![image](https://github.com/user-attachments/assets/26b053a1-d5d6-45e9-b5ab-58e50dff5213)

### REG NUMBER:212223040059
### NAME:Hariprasath.R
 
## RESULT
Thus the web application for test environment has successfully been created and executed.
  


