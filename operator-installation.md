# Summary

This readme provides the detail steps of operator installation on Openshift 4. It covers installation on Openshift web Console and CLI. It also provides a [Troubleshooting](#troubleshooting) section

For more details regarding Operator Lifecycle see, https://docs.openshift.com/container-platform/4.2/operators/olm-what-operators-are.html

After completing this tutorial you should be able to

- Install Operator fronm OperatorHub.
- Install Operator via CLI.
- Do installation troubleshooting.

### Install Operator in Openshift 4 console
Since Openshift4.1, red hat introduced the Operator concept. A list of pre-pacakaged operators can be discovered in OperatorHub.

#### 1. Login to Openshift with admin role
You can access to Openshift cluster web console via directly url or access it from Openshift cluster dashboard on IBM Cloud console. From left menu, navigate to OperatorHub

Checkpoint: view OperatorHub
![Operator](images/operator-hub.png)

#### 2. View avaialble operators
You can search name by enter text in filter box on console, or view avaialble operators with oc command

Checkpoint: view Operator list via oc
![Operator list](images/operator-list-cli.png)

#### 3. Search and select Operator, then install
You will need to subscribt for installation

Checkpoint: installation subscript
![Operator list](images/operator-subscript.png)

#### 4. Create an instance
In order to use it, you will need to create an instance for deployment 

Checkpoint: instance
![Operator list](images/create-instance.png)

#### 5. Verify the pod status
Ensure deployment is error-free, and view the pod status 

Checkpoint: deployment status
![Operator list](images/operator-pod-status.png)

#### 5. View the all installed operators
At this point, the installed operators should be ready to use

Checkpoint: deployment status
![Operator list](images/view-operator-pods.png)

### Install Operator in Openshift 4 via CLI
Althrough there is a list operators are exiating in the OperatorHUb, however if there is a need to install operators not in the list, install via CLI is an option.

### Troubleshooting
Troubleshooting
