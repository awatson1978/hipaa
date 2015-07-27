## clinical:hipaa  

HIPAA Compliance for Meteor Apps.  Meta package containing audit log, user accounts, and ssl security.


==================================
#### Installation  

``meteor add clinical:hipaa``

================================================
####  HIPAA Compliance Questionaire

https://catalyze.io/hipaa-self-assessment-checklist


==================================
#### Packages

This is a meta package, and includes the following sub-packages:  

[accounts-base](https://atmospherejs.com/meteor/accounts-base)  
[accounts-password](https://atmospherejs.com/meteor/accounts-password)  
[clinical:hipaa-audit-log](http://github.com/awatson1978/clinical-hipaa-audit-log)  
[clinical:hipaa-policies](http://github.com/awatson1978/clinical-hipaa-policies)  
[force-ssl](https://atmospherejs.com/meteor/force-ssl)  

We're currently in the process of adding at-rest disk encryption for secure PHI at rest.

================================================
####  Hosting Providers Willing to Sign Business Associate Agreements (BAA)  

[Modulus.io](http://modulus.io/)  
[Catalyze.io](http://catalyze.io)  

================================================
####  HIPAA Compliant Scale Out Using Meteor

Phase 1 - Development (1 server)  
``meteor add clinical:hipaa``  

Phase 2 - Platform as a Service (2 to 10 servers)  
  [modulus.io - Node/Meteor App Hosting on AWS](https://modulus.io/)
  [compose.io - Mongo Hosting on AWS](http://www.mongohq.com/)  


Phase 3 - Infrastructure as a Service (11+ servers)  
  [Amazon Web Services](http://aws.amazon.com/)  
  [Deploying a Meteor App on Elastic Beanstalk](https://groups.google.com/forum/#!topic/meteor-talk/VxMQzpVFpME)  

Phase 4 - Federal HIPAA
  [Amazon Web Services - HIPAA/Federal Tier](http://aws.amazon.com/compliance/)  
  [Amazon Web Services - HIPAA Whitepaper](https://aws.amazon.com/about-aws/whats-new/2009/04/06/whitepaper-hipaa/)

==================================
#### Licensing  
