![data_source](https://user-images.githubusercontent.com/108756145/222932122-c44027c0-8108-443c-b6a3-0b08082f3e33.png)

# Data Source
What is Data sources?

- Data sources allow data to be fetched or computed for use elsewhere in Terraform configuration. Use of data sources allows a Terraform configuration to make use of information defined outside of Terraform, or defined by another separate Terraform configuration.


- Providers are responsible in Terraform for defining and implementing data sources. Whereas a resource(block) causes Terraform to create and manage a new infrastructure component, data sources(block) present read-only views into pre-existing data, or they compute new values on the fly within Terraform itself.

For example;

 - a data source may retrieve remote state data from a Terraform Cloud workspace, configuration information from Consul, or look up a pre-existing AWS resource by filtering on its attributes and tags.

Every data source in Terraform is mapped to a provider based on longest-prefix matching. For example the "aws_ami" data source would map to the aws provider (if that exists).

<<<<<<< HEAD
# Data Source Block
=======
# Data Source Block
![VPC](https://user-images.githubusercontent.com/108756145/222932527-12e3e478-469c-410f-9a4e-e56199b011cc.jpg)
>>>>>>> cb951a1f9971d28fb4ede9a2bf2ac4b7eba252df
