---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Monitor
  platforms: java
---

# Getting Started with Monitor - Autoscale Settings Based On Performance Or Schedule - in Java #


  This sample shows how to programmatically implement scenario described <a href="https://docs.microsoft.com/azure/monitoring-and-diagnostics/monitor-tutorial-autoscale-performance-schedule">here</a>.
   - Create a Web App and App Service Plan
   - Configure autoscale rules for scale-in and scale out based on the number of requests a Web App receives
   - Trigger a scale-out action and watch the number of instances increase
   - Trigger a scale-in action and watch the number of instances decrease
   - Clean up your resources
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/master/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/monitor-java-autoscale-based-on-performance.git

    cd monitor-java-autoscale-based-on-performance

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.