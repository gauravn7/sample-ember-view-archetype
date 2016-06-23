# emberjs ambari view template

**First install archetype**

`mvn clean install`

**Then to create view execute the following commands**

`mvn archetype:generate -B -DarchetypeGroupId=org.apache.ambari.view -DarchetypeArtifactId=sample-ember-view-archetype -DgroupId={groupName} -DartifactId={viewName} -Dversion={version} -Dpackage={packageName}`

`cd {viewName}`

`sh initialize-ember-app.sh`
