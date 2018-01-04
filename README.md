# Manager Examples Configuration Blueprint

This blueprint will configure your manager to support the Cloudify Examples.

This blueprint will make the following modificatons to your Cloudify Manager:

* The following secrets will be created:
	* Common Secrets:
		* ExampleNetworkID: The ID of the network. (AWS VPC, Openstack Network, GCP VPC Network, Azure Virtual Network)
		* ExampleNetworkCIDR: The Network CIDR.
		* ExampleSubnetAID: The ID of Subnet A.
		* ExampleSubnetACIDR: Subnet A CIDR.
		* ExampleSubnetAZone: The zone of Subnet A.
		* ExampleSubnetBID: The ID of Subnet B.
		* ExampleSubnetBCIDR: Subnet B CIDR.
		* ExampleSubnetBZone: The zone of Subnet B.
		* ExampleKeyAgentsPublic: The public ssh key for agent VMs.
		* ExampleKeyAgentsPrivate: The private ssh key for agent VMs.
		* ExampleCentosCoreImage: The ID of a Centos Core image in your account.
		* ExampleUbuntuTrustyimage: The ID of a Ubuntu Trusty image in your account.
		* ExampleSmallImageSize: The ID of a small machine size.
		* ExampleMediumImageSize: The ID of a medium image size.
		* ExampleLargeImageSize: The ID of a large image size.
		* ExampleCredentials: Your account credentials.
	* ExampleFloatingIPNetworkID: Openstack. This is the ID of the floating IP network, also known as external network. 
	* ExampleRouterID: Openstack. This is the ID of the router.

* The following plugins will be uploaded:
	* Common Plugins:
		* Diamond Plugin 1.3.6 for Centos Core.
		* Diamond Plugin 1.3.6 for Ubuntu Trusty.
		* Fabric Plugin 1.5.1 for Centos Core.
		* Kubernetes Plugin 2.0.0 for Centos Core.
		* Utilities Plugin 1.4.2.1 for Centos Core.
	* Openstack Plugin 2.5.0 for Centos Core will be uploaded to Openstack Managers.
	* AWS Plugin 1.5.1.2 for Centos Core will be upload to AWS Managers.
	* AWSSDK Plugin 1.2.0.1 for Centos Core will be uploaded to AWS Managers.
	* GCP Plugin 1.3.0.1 for Centos Core will be uploaded to GCP Managers.
	* Azure Plugin 1.4.3 for Centos Core will be uploaded to Azure Managers. 


# Pre-requisites

* A Cloudify Manager, version 4.2 or above.


# Instructions

# manager-examples-configuration
