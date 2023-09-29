hellow,
my name is karan kolhe
i am complated my second devops project



this project complated as follows.

1. first we use the terraform tool to mananging and provisoing infrastructure through the code
2. by using terraform we create the three server
 a) jenkins server
 b) ansible server
 c) tomcat server
 ![Instances _ EC2 _ ap-south-1 — Mozilla Firefox 29-09-2023 07_27_53](https://github.com/Karankolhe12/devops_project_registration_app/assets/139026443/f44aeee3-4719-47be-ac50-3ee0c0478b9a)

2nd step :

connect the jenkins server to our putty.

and install and configure the jenkins in our jenkins server.

open link all cammand is present here.https://www.jenkins.io/doc/tutorials/tutorial-for-installing-jenkins-on-AWS/

3rd step :

connect the ansible server to our putty

and install and configure the ansible in our ansible server.

open link all cammand is present here.https://devops4solutions.medium.com/ansible-setup-on-aws-ec2-instance-d83fac41fcc8

4th step :

connect the tomcat server to our putty.

and install and configure the tomcat in our tomcat server.

open link all cammand is present here . https://medium.com/@raguyazhin/step-by-step-guide-to-install-apache-tomcat-on-amazon-linux-120748a151a9

5th step :

in the jenkins i created the 4 project

a) job1 = pull the code from github

b) job2 = build and test the code

c) job3 = deploy the application on tomcat

d) job4 = send .war file to ansible and deploy to another tomcat

![Dashboard  Jenkins  — Mozilla Firefox 29-09-2023 13_51_02](https://github.com/Karankolhe12/devops_project_registration_app/assets/139026443/58944d7f-3add-4d01-92ad-31a01268b673)

here is the CI/CD pipeline structure

![Dashboard  Jenkins  — Mozilla Firefox 29-09-2023 14_00_09](https://github.com/Karankolhe12/devops_project_registration_app/assets/139026443/687e3321-cc40-4fe9-92c3-275e38d0219a)
![Mozilla Firefox 29-09-2023 10_25_47](https://github.com/Karankolhe12/devops_project_registration_app/assets/139026443/e9e82a97-7adc-4382-b98f-141d8252cfe6)

our application is deploy on tomcat server

![Dashboard  Jenkins  — Mozilla Firefox 29-09-2023 13_51_22](https://github.com/Karankolhe12/devops_project_registration_app/assets/139026443/52c47076-0add-4914-b466-af3860956b5e)


