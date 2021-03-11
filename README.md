# Take_Home_Assessment

##Question 1:
###You are assisting a Red Hat Partner with building a solution for their Python-based web application. The web application uses Django for the front-end UI and MySQL for the backend database. The application is currently hosted on virtual machines but they are interested in migrating to containers.

###You have been instructed to assist the Partner with understanding the advantages (and disadvantages) of containers compared to their current virtual machine solution. They also want you to present a demo of this containerized solution with a sample web application using both Django and MySQL. The web application can be extremely basic and is used for a simple demo of the containerized web application.

Consider the following:
* What will the container build files for the front-end and back-end images look like? Provide an example of each.
* How would we ensure the containers run as non-root users? Why is that important?
* How do we ensure the customer’s data is persistent, backed-up, and restored? Why is that important?
* What does networking look like in this scenario?
* How does communication occur between the front and backend services?
* Will the customer need to make any adjustments to firewall rules?
* Where will the container images reside and how will the containers access images in a private repository?
* How can we handle single-points of failure in a containerized environment? Are there any existing tools or software that can help with this?

##Question 2:
###A Red Hat Partner is currently using Amazon Web Services for their music streaming app. The application allows users to search for music based on artist, album, or genre, and allows them to create, edit, and share playlists. Describe each AWS service listed below and how the Partner would use that service to architect their application. Give as much detail as possible.


* EC2
* EC2 Autoscaling
* Elastic Load Balancing
* VPC
* Route 53
* S3
* CloudFront
* DynamoDB
* Simple Notification Service (SNS)
