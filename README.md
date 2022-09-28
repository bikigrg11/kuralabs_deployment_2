<h1> CI/CD pipeline Deployment 2 - URL Shortner </h1>

<h3> Please download the documentation from :  https://github.com/bikigrg11/kuralabs_deployment_2/blob/main/documentation.docx </h3>
                                                                                                
<h3> Name: Biki Gurung <br>
</h3>

<h3>Version	Date</h3>
<table>
<tr>
<td> V 1.0 </td>
<td> 09/05/2022 </td>
</tr>
<tr>
<td> V 2.0 </td>
<td> 09/22/2022 </td>
</tr>
</table>

<h3>Description:</h3>
<li> Use Jenkins for CI / CD Pipeline - Build, Test and Deploy application 
<li>	Use Elastic Beanstalk to deploy application
<li>	Use AWS CloudWatch to Monitor
<li>	Use Cypress and JUnit Test 


<h3> Pre-requisites: </h3> 
<li>	AWS account
<li> CI tool of choice (Jenkins)
<li> GitHub repository you’d like to deploy

<h2>Tables of Contents: </h2>
<br>

<li>Install Jenkins on an EC2:	3
<li>Install Virtual Environment	5
<li>Activate the Jenkins user on the EC2	6
<li>Create a Jenkins user in your AWS account	7
<li>Install AWS CLI on the Jenkins EC2 and configure	9
<li>Configure AWS CLI for Jenkins (Sub User)	9
<li>Install EB CLI in the Jenkins EC2 user	9
<li>Connect GitHub to Jenkins Server	10
<li>Create an access token from GitHub	11
<li>How to setup Jenkins:	12
<li>Create a multibranch build	14
<li>How to Deploy application in Elastic Beanstalk	19
<li>Deploy application using Elastic Beanstalk CLI and Jenkins:	19
<li>How to Manually Deploy to Elastic Beanstalk	21
<li>How to create an Elastic Beanstalk Env	23
<li>Continuous Deployment (CD) using Jenkins and Elastic Beanstalk	25
<li>List of Issues and their solution	28
<li>Issue #1 – Couldn’t download zip file using SCP from the Server	28
<li>Issue #2: Elastic beanstalk kept on failing with HTTP 502	30
<li>Issue #3, Do not create new Jenkins User	32
<li>Modifications to Pipeline	33
<li>Add another test to Pytest unit testing	33
<li>Add a way to Monitor and Notify you	33
<li>Add CloudWatch Agent to Monitor your Jenkins Server	33
<li>Add a way to notify you:	35
<li>Use Cypress for testing	37
<li>Add a Linter	37
<li>Change something on the application front	38
<li>What Improvements can be made?	40
<li>CI/CD Pipeline Diagram:	41





CI/CD Pipeline Diagram: https://github.com/bikigrg11/kuralabs_deployment_2/blob/main/deployment2.png
<img src="https://github.com/bikigrg11/kuralabs_deployment_2/blob/main/deployment2.png">


