# HW2-DevOps

Name: Vidhisha Jaswani Unity ID: vjaswan

Goal: Using ansible, to be able to automatically configure a server running mattermost.

Instructions: [Mattermost](https://docs.mattermost.com/install/install-ubuntu-1604.html)

## Folder Structure

![folderstructure](images/folderstructure.png)

Here ansible-srv is the configuration server and mm-srv is the server on which we setup Mattermost. The keys are created inside baker.yml of ansible-srv so that we manually do not have to create and place them.

Inside configure-mattermost we have everything required to setup the mattermost server.

```inventory``` file contains the IP, username, and path for private key.

```sit.yml``` is the main playbook which will be called.

```configure-mattermost/tasks``` contains all yml files.

```configure-mattermost/templates``` contains files we need to replace on setup.

```configure-mattermost/vars``` contains main.yml with all variables.


## Screencast
[Screencast Link]()


## References
https://docs.mattermost.com/administration/command-line-tools.html#mattermost-3-6-and-later
https://docs.mattermost.com/administration/config-settings.html

**Thank you!**
