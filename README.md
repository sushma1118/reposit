                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               Prerequisites
K8s cluster should be created.
OpenEBS should be deployed in K8s cluster.
Storage pool should be created.
Procedure
The job should be capable of creating OpenEBS storage classes.
Check if the OpenEBS storage classes are created using kubectl command kubectl get sc
Test Result
|    Test Id    |  Job Name  |   Date And Time   |Result |
|--------------:|------------|-------------------|-------|
|124561553065828|deploy_mongo|2019-03-20T12:40:28|fail   |
|    Test Id    |  Job Name  |   Date And Time   |Result |
|--------------:|------------|-------------------|-------|
|124561553065838|deploy_mongo|2019-03-20T12:40:38|fail   |
