## About This project
This project deploys the cloud infraestructure and a basic website on AWS, using AWS Cloud Formation

## Prerequisites
* You need to create an account in AWS

## Usage
* You need to modify the template in network.yml to have your account settings

#### 2. Create the infrastructure and deploy the website
  Run this in your terminal

     $ ./create.sh yourStackName network.yml network-parameters.json
#### 3. Update the infrastructure and deploy the website
  Run this in your terminal
  
    $ ./update.sh yourStackName network.yml network-parameters.json
#### 4. Open the website
  To open the website you need the URL of the Load Balancer
