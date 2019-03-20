|    Test Id    |  Job Name  |   Date And Time   |Result |
|--------------:|------------|-------------------|-------|
|124561553064819|deploy_mongo|2019-03-20T12:23:39|fail   |
|124561553064732|deploy_mongo|2019-03-20T12:22:12|fail   |
|124561553064719|deploy_mongo|2019-03-20T12:21:59|fail   |
Prerequisites
K8s cluster should be created.
OpenEBS should be deployed in K8s cluster.
Storage pool should be created.
Procedure
The job should be capable of creating OpenEBS storage classes.
Check if the OpenEBS storage classes are created using kubectl command kubectl get sc
Test Result

