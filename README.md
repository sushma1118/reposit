|    Test Id    |  Job Name  |   Date And Time   |Result |
|--------------:|------------|-------------------|-------|
|124561553065301|deploy_mongo|2019-03-20T12:31:41|fail   |
|124561553065293|deploy_mongo|2019-03-20T12:31:33|fail   |
|124561553065286|deploy_mongo|2019-03-20T12:31:26|fail   |
|124561553065277|deploy_mongo|2019-03-20T12:31:17|fail   |
This job that will create the storage classes with the properties supported by OpenEBS.

Prerequisites
K8s cluster should be created.
OpenEBS should be deployed in K8s cluster.
Storage pool should be created.

Procedure
The job should be capable of creating OpenEBS storage classes.
Check if the OpenEBS storage classes are created using kubectl command kubectl get sc
Test Result

