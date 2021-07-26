# Setting up Spark Standalone Cluster and its Configuration



# Submitting spark applications

```
saprk-submit --class <main-class> \
            --master <master-url> \
            --deploy-mode <deploy-mode>
            --conf <key>=<value>
            --packages <>
```
    - deploy-mode:
        - There are 2 deploy modes client and cluster
        - Then there are support for 2 languages python and scala
        - deploy-mode cluster, in standalone cluster is not possible for pyspark
        