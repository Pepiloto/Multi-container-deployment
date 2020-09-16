# Multi-container-deployment

This script allow to easily deploy multiple containers:

To create ```n``` containers with ssh access and display their IP address the username and the password to connect to them once created.
```
multi_deploy.sh --create n
```
To display the infos of the containers created:
```
multi_deploy.sh --info
```
To start the containers already created:
```
multi_deploy.sh --start
```
To destroy the containers:
```
multi_deploy.sh --drop
```
