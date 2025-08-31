# Exercise 6 - Manage your Feature in Cloud ALM & Deployment

In this exercise, we will manage the assignment and deployment of Cloud Transport Management service transport requests in SAP Cloud ALM. By managing the lifecycle of your Feature you can keep track of your changes with a governed process. This includes confirmation of successful test in QA and the apporval for the deployment to the production environment. Eventually you can validate the deployed application in the production environment.

## Exercise 6.0 - Manage the lifefcylce of your feature

1. Got yo the Feature created in exercise 2.
2. Switch tro Edit mode.
3. Go to the Transports setcion and click Assign.
4. In the selection dialog search for your transport ID (prefix is the destination name of the connection between Cloud ALM and CTMS).
5. Select the transport and click Assign.
6. Save and Close the Feature.
7. The Transport is assigned to your Feature.
   
## Exercise 6.1 - Deploy and monitor changes in your QA and Prod environment

1. The transport in the Transports section is released and shows the CTMS target node as target tenant.
2. Click Deploy and Confirm the deployment to the ragte node in teh dialog.
3. Use the Refresh button on the Transports Section to retrieve the Import Result.
4. As soon as the import is succeeded the status changes to Deployed in <Target Tenant>.
5. Now you can change the Feature status to In Testing.
6. The action Confirm Successfu Test will be executed centrally.
7. Click on Analytics in the top right corner to access the Feature Traceability.
8. Check whether your feature is in status "Successfully Tested".
9. Now you can approve the Feature for Production.
10. In status "Approved for Production" you can trigger the deployment to Production by clicking Deploy in the Transports section.
11. Refresh the section to retrieve the import result.

## Exersice 6.2 - Find and access the deployed applications

After completing these steps you will have...

## Summary

You've now done
