# cloudformation-base-infra-reference
These two templates are crossed referenced. One template creates a VPC with all its resources
and the other template deploys an ec2 into the VPC. This template creates a Mapping function to 
dynamically choose a region. The template also has parameters for requesting user inputs. 
The template outputs the values of the DNS name of the EC2 instance. The ec2 instance is
installed and configured with apache using User data.
