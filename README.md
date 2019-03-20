|    Test Id    |  Job Name  |   Date And Time   |Result |
|--------------:|------------|-------------------|-------|
|124561553064441|deploy_mongo|2019-03-20T12:17:21|fail   |
|124561553064435|deploy_mongo|2019-03-20T12:17:15|fail   |
|124561553064430|deploy_mongo|2019-03-20T12:17:10|fail   |
|124561553064423|deploy_mongo|2019-03-20T12:17:03|fail   |
|124561553064393|deploy_mongo|2019-03-20T12:16:33|fail   |
This job that will create the storage classes with the properties supported by OpenEBS.

Prerequisites
K8s cluster should be created.
OpenEBS should be deployed in K8s cluster.
Storage pool should be created.
Procedure
The job should be capable of creating OpenEBS storage classes.
Check if the OpenEBS storage classes are created using kubectl command kubectl get sc
Test Result

