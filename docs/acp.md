# Access Control Policy



## What are the access control policies in oneM2M?

oneM2M resources can be thought of as digital representation of physical entities. Any unwanted access to these resources can make a system vulnerable by unauthorized operation on these resources. It may also lead to loss of sensitive data. Hence any unauthorized access to these resources should be prevented. 

oneM2M Access control Policies defines an authorization mechanism for oneM2M resources. These policies contain access control rules which define who is authorized to access these resources, what operations ( e.g. Create, Retrieve, Discover) are allowed, what attributes of these resources and under which conditions (e.g. time, location, IP address, limit) access is allowed for operating on oneM2M resources. 

Access control policies are also represented as a resource in the CSE. For controlling the access to resources other than access control policy resource it defines the concept of privileges. For operating on Access Control Policy resources it defines the concept of self privileges. 

![Screenshot](img/acp.png)

