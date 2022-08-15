### Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the starter code for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:


#### final-project-starter.yml
Students have to write the CloudFormation code using this YAML template for building the cloud infrastructure, as required for the project. 

#### server-parameters.json
Students may use a JSON file for increasing the generic nature of the YAML code. For example, the JSON file contains a "ParameterKey" as "EnvironmentName" and "ParameterValue" as "UdacityProject". 

In YAML code, the `${EnvironmentName}` would be substituted with `UdagramProject` accordingly.


### How to run the supporting material?
You can run the supporting material in two easy steps:
```bash
# Create servers
# Create the network infrastructure
# Check the region in the create.sh file
./create.sh  udm-intra udm-intra.yml udm-intra-params.json

# Ensure that the AWS CLI is configured before runniing the command below
# Create the application servers
# Check the region in the create.sh file
./create.sh  udm-servers udm-servers.yml udm-servers-params.json
```

