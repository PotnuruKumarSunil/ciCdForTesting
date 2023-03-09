# CI for Team Project
<!-- ABOUT THE PROJECT -->
## About The Project
Have you ever worried about the code once you pushed??<br />
if not, here's the simple architecture about where does your code goes after you push it.<br />
Being a developer, you do have full rights to know what goes with your code.<br />
### Built With
* AWS Cloud Services
* GitHub
* Jenkins
* Ansible
* WebServer
### Brief
* A developer always pushes his/her code and chills. At the very next, the CloudOps or the Devops guys come into play.
* This is a simple architecture where the developer pushes the code to a Central repository (here github).
* After every push of developer, there's a jenkins master node which checks for pushes and runs the job immediately.
* Here, the job includes to clone the code into ansible slave node.
* The ansible also configures the webserver according to the requirement and deploys the code into webserver.
* And finally, webserver serves the code for the whole internet.
