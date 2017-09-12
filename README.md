# Fabric All The Things
Service Fabric Examples and usecases

All examples updated with latest version of the service fabric SDK and .NET47 and or Dotnetcore2 where relevant.

# GuestApplication
example lifted from "Programming Service Fabric"

Demonstrates deploying an un-servicefabric aware webservice with a watchdog service which reports on the apps health.
* publish to your local cluster
* connect to the cluster from VisualStudio/CloudExplorer and view streaming logs.
* open http://localhost:8088 and see the time response.
* Open Service Fabric Explorer and find the node with the TimeService running, and restart the node
* in the streaming logs notice the changes and when fabric has redeployed the apps refresh the page to see the time response.

