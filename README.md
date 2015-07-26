## clinical:hipaa  

HIPAA Compliance for Meteor Apps.  Meta package containing audit log, user accounts, and ssl security.


==================================
#### Installation  

``meteor add clinical:hipaa``


==================================
#### Packages

This is a meta package, and includes the following sub-packages:  

[accounts-base](https://atmospherejs.com/meteor/accounts-base)  
[accounts-password](https://atmospherejs.com/meteor/accounts-password)  
[clinical:hipaa-audit-log](http://github.com/awatson1978/clinical-hipaa-audit-log)  
[clinical:hipaa-policies](http://github.com/awatson1978/clinical-hipaa-policies)  
[force-ssl](https://atmospherejs.com/meteor/force-ssl)  

We're currently in the process of adding at-rest disk encryption for secure PHI at rest.


==================================
#### Policy Index

* [Introduction](policies/introduction.md)
* [HIPAA Inheritance for PaaS Customers](policies/hipaa_inheritance_for_paas_customers.md)
* [HIPAA Inheritance for Platform Add-on Customers](policies/hipaa_inheritance_for_platform_addon_customers.md)
* [Policy Management Policy](policies/policy_management_policy.md)
* [Risk Management Policy](policies/risk_management_policy.md)
* [Roles Policy](policies/roles_policy.md)
* [Data Management Policy](policies/data_management_policy.md)
* [System Access Policy](policies/systems_access_policy.md)
* [Auditing Policy](policies/auditing_policy.md)
* [Configuration Management Policy](policies/configuration_management_policy.md)
* [Facility Access Policy](policies/facility_access_policy.md)
* [Incident Response Policy](policies/incident_response_policy.md)
* [Breach Policy](policies/breach_policy.md)
* [Disaster Recover Policy](policies/disaster_recovery_policy.md)
* [Disposable Media Policy](policies/disposable_media_policy.md)
* [IDS Policy](policies/ids_policy.md)
* [Vulnerability Scanning Policy](policies/vulnerability_scanning_policy.md)
* [Data Integrity Policy](policies/data_integrity_policy.md)
* [Data Retention Policy](policies/data_retention_policy.md)
* [Employees Policy](policies/employees_policy.md)
* [Approved Tools Policy](policies/approved_tools_policy.md)
* [3rd Party Policy](policies/policyTemplates/3rd_party_policy.md)
* [Key Definitions](policies/key_definitions.md)
* [HIPAA Business Associate Agreement (“BAA”)](policies/hipaa_business_associate_agreement.md)
* [HIPAA Mappingsto Business Controls](policies/hipaa_mapping_to_controls.md)


==================================
#### API

````html
{{> thirdPartyPolicy}}
{{> approvedToolsPolicy}}
{{> auditingPolicy}}
{{> breachPolicy}}
{{> configurationManagementPolicy}}
{{> dataIntegrityPolicy}}
{{> dataManagementPolicy}}
{{> dataRetentionPolicy}}
{{> disasterRecoveryPolicy}}
{{> disposableMediaPolicy}}
{{> employeesPolicy}}
{{> facilityAccessPolicy}}
{{> hipaaBusinessAssociateAgreement}}
{{> hipaaInheritanceForPaasCustomers}}
{{> hipaaInheritanceForPlatformAddOnCustomers}}
{{> hipaaMappingToBusinessControls}}
{{> idsPolicy}}
{{> incidentResponsePolicy}}
{{> keyDefinitions}}
{{> policyManagementPolicy}}
{{> riskManagementPolicy}}
{{> rolesPolicy}}
{{> systemAccessPolicy}}
{{> vulnerabilityScanningPolicy}}
````

Of course, any of these templates can be included in a route using Iron Router or Flux Router.  



==================================
#### Licensing  
