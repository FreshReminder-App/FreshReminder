# FreshReminder
A next generation grocery tracking app with smart scan and recipe recommendation

# Quick Start
This app uses expo cli with React Native Framework. To view the app, an Expo app is needed on your mobile device (iPhone, iPad etc.):
Simply run:
`npm run-script`
`expo start`

# System Design
* ChatGPT API Microservice containerized and hosted maybe on AWS Elastic Kubernetics
* Account specific user data stored in a NoSQL database like MongoDB or a traditional relational database
* Scanning model hosted in AWS Lambda / [Azure MLOps] (https://github.com/microsoft/MLOps)
* Maybe consider a caching mechanism on MongoDB
