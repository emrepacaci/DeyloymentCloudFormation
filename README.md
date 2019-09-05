## About This project
This project deploys the cloud infraestructure and a basic website on AWS, using AWS Cloud Formation

## Prerequisites
* You need to create an account in AWS

## Usage
* You need to modify the template in network.yml to have your account settings

#### 2. Create the Network infrastructure and deploy the website
  Run this in your terminal

     $ ./create.sh yourNetworkStackName network.yml network-parameters.json
#### 3. Update the Network infrastructure and deploy the website
  Run this in your terminal
  
    $ ./update.sh yourNetworkStackName network.yml network-parameters.json
    
#### 4. Create the Server infrastructure and deploy the website
    
     $ ./create.sh yourServerStackName server.yml server-parameters.json
#### 5. Update the Server infrastructure and deploy the website
    
     $ ./update.sh yourServerStackName server.yml server-parameters.json
     
#### 4. Open the website
  To open the website you need the URL of the Load Balancer
