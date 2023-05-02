# Accelerator Log

## Options
```json
{
  "bsGitBranch" : "",
  "containerPort" : "1026",
  "createRabbitMQCluster" : true,
  "createResourceClaim" : true,
  "includeBuildToolWrapper" : true,
  "numRabbitMQClusterNodes" : "1",
  "projectName" : "spring-smtp-gateway",
  "rabbitMQName" : "rmq-1",
  "serviceNamespace" : "developer-ns",
  "servicePort" : "25",
  "workloadNamespace" : "developer-ns"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ engine.transformations[0].validated.delegate (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo, InvokeFragment, Provenance)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Exclude
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate (Exclude)
┃ ┃ ┃ ┃ ┃  Info Will exclude [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml]
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug icons/email.png matched [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/catalog/catalog.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/boot/SmtpGatewayApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/GetMessageHeaderStream.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/MessageSizeException.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMessageHandler.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SafelistedServerSocket.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStream.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStreamFactory.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedStreamCreator.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/springconfig/SMTPServerBeanConfig.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SmtpGatewayMessageSource.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/task/SimulatedLoadTask.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/bootstrap.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_largeRecipsTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_maxSizeTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_sendMessageTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_authCidrTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_multiAuthCidrTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_noauthCidrTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testConfig.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalAuthorizedCIDRConfig.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalMultiAuthorizedCIDRConfig.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalNoAuthorizedCIDRConfig.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/catalog/catalog.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/SmtpSinkApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMessageSink.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/test/java/com/java/example/smtpsink/SmtpSinkApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.template matched [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.template matched [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug templates/workloads.template matched [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath, InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/config/workload.yaml, **/templates/workloads.template]
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/email.png didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/.gitignore didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/Tiltfile didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/catalog/catalog.yaml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/config/workload.yaml matched [**/config/workload.yaml, **/templates/workloads.template] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/pom.xml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/boot/SmtpGatewayApplication.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/GetMessageHeaderStream.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/MessageSizeException.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMessageHandler.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SafelistedServerSocket.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStream.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStreamFactory.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedStreamCreator.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/springconfig/SMTPServerBeanConfig.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SmtpGatewayMessageSource.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/task/SimulatedLoadTask.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/application.yml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/bootstrap.yml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_largeRecipsTest.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_maxSizeTest.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_sendMessageTest.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_authCidrTest.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_multiAuthCidrTest.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_noauthCidrTest.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testConfig.properties didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalAuthorizedCIDRConfig.properties didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalMultiAuthorizedCIDRConfig.properties didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalNoAuthorizedCIDRConfig.properties didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/.gitignore didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/Tiltfile didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/catalog/catalog.yaml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/config/workload.yaml matched [**/config/workload.yaml, **/templates/workloads.template] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/pom.xml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/SmtpSinkApplication.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMessageSink.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/resources/application.yml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/test/java/com/java/example/smtpsink/SmtpSinkApplicationTests.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.template didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.template didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug templates/workloads.template matched [**/config/workload.yaml, **/templates/workloads.template] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [app.kubernetes.io/part-of: spring-smtp-gateway->app.kubernetes.io/pa...(truncated), rmq-1->rmq-1, 25->25, name: smtp-gateway->name: spring-smtp-ga...(truncated), 1026->1026, name: smtp-sink->name: spring-smtp-ga...(truncated), workloads->developer-ns]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ Debug Path 'templates/workloads.template' matched 'templates/workloads.template' with groups {g0=templates/workloads.template} and was rewritten to 'config/developer/workloads.yaml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[3] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[3].validated (Combo)
┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Condition (#bsGitRepository != null) evaluated to false
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/catalog/catalog.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/email.png didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/.gitignore didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/Tiltfile didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/catalog/catalog.yaml matched [**/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/config/workload.yaml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/pom.xml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/boot/SmtpGatewayApplication.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/GetMessageHeaderStream.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/MessageSizeException.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMessageHandler.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SafelistedServerSocket.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStream.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStreamFactory.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedStreamCreator.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/springconfig/SMTPServerBeanConfig.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SmtpGatewayMessageSource.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/task/SimulatedLoadTask.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/application.yml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/bootstrap.yml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_largeRecipsTest.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_maxSizeTest.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_sendMessageTest.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_authCidrTest.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_multiAuthCidrTest.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_noauthCidrTest.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testConfig.properties didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalAuthorizedCIDRConfig.properties didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalMultiAuthorizedCIDRConfig.properties didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalNoAuthorizedCIDRConfig.properties didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/.gitignore didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/Tiltfile didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/catalog/catalog.yaml matched [**/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/config/workload.yaml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/pom.xml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/SmtpSinkApplication.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMessageSink.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/resources/application.yml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/test/java/com/java/example/smtpsink/SmtpSinkApplicationTests.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.template didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.template didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug templates/workloads.template didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [name: smtp-gateway->name: spring-smtp-ga...(truncated), name: smtp-sink->name: spring-smtp-ga...(truncated), app.kubernetes.io/part-of=spring-smtp-gateway->app.kubernetes.io/pa...(truncated)]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#createRabbitMQCluster) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[3].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/rmqCluster.template]
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/email.png didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/.gitignore didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/Tiltfile didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/catalog/catalog.yaml didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/config/workload.yaml didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/pom.xml didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/boot/SmtpGatewayApplication.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/GetMessageHeaderStream.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/MessageSizeException.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMessageHandler.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SafelistedServerSocket.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStream.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStreamFactory.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedStreamCreator.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/springconfig/SMTPServerBeanConfig.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SmtpGatewayMessageSource.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/task/SimulatedLoadTask.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/application.yml didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/bootstrap.yml didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_largeRecipsTest.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_maxSizeTest.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_sendMessageTest.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_authCidrTest.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_multiAuthCidrTest.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_noauthCidrTest.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testConfig.properties didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalAuthorizedCIDRConfig.properties didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalMultiAuthorizedCIDRConfig.properties didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalNoAuthorizedCIDRConfig.properties didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/.gitignore didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/Tiltfile didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/catalog/catalog.yaml didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/config/workload.yaml didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/pom.xml didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/SmtpSinkApplication.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMessageSink.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/resources/application.yml didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/test/java/com/java/example/smtpsink/SmtpSinkApplicationTests.java didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.template matched [**/rmqCluster.template] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.template didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug templates/workloads.template didn't match [**/rmqCluster.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[3].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [rmq_service_namespace->developer-ns, numReplicas->1, rmq_instance_name->rmq-1]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[3].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/rmqCluster.template' matched 'templates/rmqCluster.template' with groups {g0=templates/rmqCluster.template} and was rewritten to 'config/service-operator/rmqCluster.yaml'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#createResourceClaim) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[4].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[4].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/rmqResourceClaim.template]
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/email.png didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/.gitignore didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/Tiltfile didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/catalog/catalog.yaml didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/config/workload.yaml didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/pom.xml didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/boot/SmtpGatewayApplication.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/GetMessageHeaderStream.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/MessageSizeException.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMessageHandler.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SafelistedServerSocket.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStream.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStreamFactory.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedStreamCreator.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/springconfig/SMTPServerBeanConfig.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SmtpGatewayMessageSource.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/task/SimulatedLoadTask.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/application.yml didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/bootstrap.yml didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_largeRecipsTest.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_maxSizeTest.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_sendMessageTest.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_authCidrTest.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_multiAuthCidrTest.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_noauthCidrTest.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testConfig.properties didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalAuthorizedCIDRConfig.properties didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalMultiAuthorizedCIDRConfig.properties didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalNoAuthorizedCIDRConfig.properties didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/.gitignore didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/Tiltfile didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/catalog/catalog.yaml didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/config/workload.yaml didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/pom.xml didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/SmtpSinkApplication.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMessageSink.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/resources/application.yml didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/test/java/com/java/example/smtpsink/SmtpSinkApplicationTests.java didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.template didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.template matched [**/rmqResourceClaim.template] -> included
┃ ┃ ┃ ┃ ┃ ┗ Debug templates/workloads.template didn't match [**/rmqResourceClaim.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[4].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [rmq_service_namespace->developer-ns, rmq_instance_name->rmq-1, rmq_workloads_namespace->developer-ns]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[4].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/rmqResourceClaim.template' matched 'templates/rmqResourceClaim.template' with groups {g0=templates/rmqResourceClaim.template} and was rewritten to 'config/app-operator/rmqResourceClaim.yaml'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[5] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[5].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[5].validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[5].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[5].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeBuildToolWrapper) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[5].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [mvnw, mvnw.cmd, .mvn/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug icons/email.png didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/catalog/catalog.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/boot/SmtpGatewayApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/GetMessageHeaderStream.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/MessageSizeException.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMessageHandler.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SafelistedServerSocket.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStream.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStreamFactory.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedStreamCreator.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/springconfig/SMTPServerBeanConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SmtpGatewayMessageSource.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/task/SimulatedLoadTask.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/bootstrap.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_largeRecipsTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_maxSizeTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_sendMessageTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_authCidrTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_multiAuthCidrTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_noauthCidrTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalAuthorizedCIDRConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalMultiAuthorizedCIDRConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalNoAuthorizedCIDRConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/catalog/catalog.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/SmtpSinkApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMessageSink.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/resources/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/test/java/com/java/example/smtpsink/SmtpSinkApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.template didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.template didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.template didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug mvnw.cmd matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.transformations[0].sources[5].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.transformations[0].sources[6] (Provenance)
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ Debug Multiple representations for path 'smtp-gateway/config/workload.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'smtp-sink/config/workload.yaml', will use the one appearing last 
┃ ┗ ┗ ┗ Debug Multiple representations for path 'README.md', will use the one appearing last 
┗ ╺ engine.transformations[1] (UniquePath)
```
