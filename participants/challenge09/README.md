# KfW DevOps Challenge

## Challenge 9 - Monitoring

[Home](../../README.md) - [Next >](../challenge10/README.md)

### Intro

>[...story part
>
>...]

To bring our DevOps journey full circle we need to understand what is happening in our deployed environments. It is too late for us to find out about a problem, by the time our users are complaining about it. It is also imperative to know about not only the performance of the site, but also the impact positive or negative a feature has had on our users. Please take a moment to review the articles below to gain a better understanding of the importance of monitoring and Application Insights, one of the tools we have to make it easy in Azure. 

1. [What is Monitoring?](https://docs.microsoft.com/en-us/azure/devops/learn/what-is-monitoring)
2. [What is Application Insights?](https://docs.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview)

### Tasks

In this challenge we will look at some of the telemetry that has already been collected by our running instance. We will also link a Log Analytics Workspace to our App Service. This will allow us to collect logs and store them for a longer period. 

1. Find the Diagnostic Settings in your App Service and add a setting to collect all logs to a Log Analytics Workspace.

2. Create a dashboard in the Azure Portal and pin a chart displaying all successfull (2xx) requests.

3. Implement a dashboard to display amount of API requests grouped by route in a five minute intervall.

### Checklist

1. Diagnostic settings are enabled in your App Service
2. A Dashboard in Azure with at least one chart to display successfull requests.
3. On the same dashboard you have a chart displaying the amount of API requests grouped by route.

### Lernmaterial

- [Azure Dashboards](https://docs.microsoft.com/en-us/azure/azure-portal/azure-portal-dashboards)
- [Azure kusto query language](https://docs.microsoft.com/en-us/azure/data-explorer/kusto/query/)


[Home](../../README.md) - [Next >](../challenge10/README.md)