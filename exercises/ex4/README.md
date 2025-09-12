# Transport your low-code application

In this exercise, you will create a new transport request using **SAP Content Agent Service** and **SAP Mobile Services**.

## Exercise 4.0 - Setup SAP Content Agent Service

1. In SAP BTP cockpit, navigate to your developlment btp subaccount named `XP266_DEV`. 
2. Go to **Services** > **Instances and Subscription** and open **Content Agent Service** in the Subscriptions area to access the UI.
3. The Content Agent Service Overview page opens. In here navigate to Cloud Transport Management.
4. Choose **TransportManagementService** as Destination and click **Refresh Connection**. The status should be **Connected**.

## Exercise 4.2 - Create and send a Transport Request in SAP Content Agent Service UI

In SAP Content Agent Service, you will now prepare a transport request containing development content provided by the SAP Mobile Services SDK.

1. In SAP Content Agent Service UI, go to **Export** and tick XP266DEVMS and XP266DEVMSRES of Tyoe Mobile application.
2. Go to **Step 2**
3. As Export Mode leave SAP Cloud Transport Management
4. Choose ``DEV`` as your Source Node. 
5. Enter a description e.g. ``My low-code application``
6. Continue with **Step 3** and  **Step 4** to trigger **export** to SAP Cloud Transport Management Service.

## Summary

You've now create a transport request via SAP Content Agent Service by bundling low-code development content provided by SAP Mobile Services. 

In the next exercise you will veryfy the creation fo two transport requests. One that has been created in this execercise 3 and one that has been created in the previous exercise 4.

Continue to - [Verify all Release Steps](../ex5/README.md)
