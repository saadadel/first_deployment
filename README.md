# Flask webapp Deploy
This is the 6th project for udacity full stack nanodegree

##### IP Address of server:

18.185.59.214

##### hostname: 
ec2-18-185-59-214.eu-central-1.compute.amazonaws.com


# software installed
- Apache webserver using Flask framework and bootstrap formatting.

- Data is saved to a Postgresql database on the server.

# Configurations made

  -  Root access disabled

   - Postgresql user called 'catalog' added, with password 'x'

-    An additional superuser called 'grader' with password 'x' was added to allow Udacity grader to access the server

 -   Password access to the server disabled

  -  Access limited to private rsa key authentication

   - Enabled firewall to restrict ports to 2200 for ssh, 80 for webservice, 123 for NTP. All others ports have been blocked.

-    The ssh port is 2200 - a non-default port. The normal port (22) has been disabled.

# Third Party Resources

 -   https://github.com/mulligan121/Udacity-Linux-Configuration

  -  https://github.com/mulligan121/Udacity-Linux-Configuration

