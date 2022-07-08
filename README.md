# AWS-SNS-System-API
System API to integarte with AWS SNS and send SMS notifications to mobile

# Pre-requisites:
- AWS Access Key
- AWS Secret Key
- Access to SNS
- Recipient mobile numbers should be registered in AWS SNS

# How to run
- Run as any other mule api
- Exposes the integration as a http endpoint, /sendSMSAlerts
- The mobile number and SMS message are currently hardcoded. They can be parameterized under publish component in the implementation.
