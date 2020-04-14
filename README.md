# ALM-LCS-PowerAutomate
Samples for PowerAutomate in order to call API for LCS - Dynamics365 FinOps project - with your favorite lowcode editor PowerAutomate - setup automatic refresh database 

See my article in my blog in order to fully understand step-by-step process :
https://www.powerazure365.com/blog-1/lcs-api-database-movement-with-powerautomate


Database movement operations are a suite of self-service actions that can be used as part of Data Application Lifecycle Management (also referred to as DataALM). These actions provide structured processes for common implementation scenarios such as golden configuration promotion, debugging/diagnostics, destructive testing, and general refresh for training purposes.

In this topic, you will get PowerAutomate samples flow to use automatic database movement operations to perform refresh, export, import, and various flavors of point-in-time restore.

At the time, I've done these samples, the LCS API have only 4 methods but I hope Microsoft will add soon more methods and of course I will share/change that with you in this GitHub project, depending on which and when it will possible. 

We can perform the following operations through the RESTful API:

List DB backups for an LCS project.

Create a DB refresh between two environments (only Prod and Sandbox environments, like we can do in LCS).

Get an ongoing operation status.
