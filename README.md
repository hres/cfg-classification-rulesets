#  Canada Food Guide Classification Rulesets

This project provides the directory tree structure to house the CFG classification rulesets

## Directory Structure for Rulesets

1. Clone this project in the directory where you want the services to manage the rulesets. 
2. Make sure the [RULESETS_HOME] property gets updated to directory path leading to `dtables`. Default setting is RULESETS_HOME=/opt/ruleset/cfg-classification-rulesets/rulesets
3. Chown proper user/group ownership of the entire directory tree.  Provide read/write permissions to the account running tomcat. 

## Directory Structure Diagram

![Directory Structure Diagram](hierarchy.png "Directory Structure Diagram")

[//]: # (These are the references links used in the body of this note and get stripped out when the markdown processor does its thing.  There is no need to format nicely because it should not be seen.)

[RULESETS_HOME]: <https://github.com/hres/cfg-classification-service/blob/master/src/main/java/ca/gc/ip346/util/rulesets.properties>
