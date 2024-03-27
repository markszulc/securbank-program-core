# SecurBank example foundation code for AEM Cloud Service full stack deployments

## Key notes

There is no front end code or content in this project. Use Quick Site Creation, or Edge Delivery Services for Front End. 


## Created with AEM Maven Archetype

    mvn -B org.apache.maven.plugins:maven-archetype-plugin:3.2.1:generate \
    -D archetypeGroupId=com.adobe.aem \
    -D archetypeArtifactId=aem-project-archetype \
    -D archetypeVersion=48\
    -D appTitle="SecurBank" \
    -D appId="securbank" \
    -D groupId="com.securbank" \
    -D aemVersion="cloud" \
    -D includeFormscommunications="y" \
    -D includeFormsenrollment="y" \
    -D sdkFormsVersion="latest" \
    -D includeFormsheadless="y" \
    -D includeCif="y"


## How to build

To build all the modules and deploy the `all` package to a local instance of AEM, run in the project root directory the following command:

    mvn clean install -PautoInstallSinglePackage


