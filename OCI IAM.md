### Identity and Access Management Service
> Fine Grained Access COntrol
> AuthN - Who are you?
> AuthZ - What permission do you have?
> Allows user to be assigned of multiple roles, and the roles comes with there own permission.

`There ae multiple OCI IDentity Concepts`
 - Identity Domains, Users, Groups, Principals and many more.
  
### Identity Domains
  > An Identity Domain represents the set of user population in OCI and associated configuration and security Settings.
  - Basically, It contains user and groups.
  - Over that ID -> we build `POLICIES` -> `COMPARTMENTS` -> `RESOURCES`
      **RESOURCES**
       - It has multiple tools provided by oracle to use the cloud as per there prefrences.
       - To use all the resources Oracle provide a Unique ID `OCID(ORACLE CLOUD ID)`
       - ```ocid1.<RESOURCE TYPE>.<REALM>.[REGION][.FUTURE USE].<UNIQUE ID>```
          - REALM : Set of Regions that share the same Characterstics.
          - REGION : The region Code.
          - RESOURCE TYPE : The type of Resources (Storage, Compute).
  
    **COMPARTMENTS**
     - 