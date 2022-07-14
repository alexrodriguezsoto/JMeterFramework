Test
Execute

mvn clean verify -Dthreadcount=30 -DrampUp=20 -DtestPlan=Workspace.jmx

ISSUES: make sure you have maven installed
perform:
mvn --version to make sure its installed

Make sure POM dependencies are updated. This framework
is updated as of July 10, 2022