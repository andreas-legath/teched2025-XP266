# Transport your low-code application

In this exercise, you will create a new transport request using **SAP Content Agent Service** and **SAP Mobile Services**.

## Exercise 4.0 - Setup SAP Content Agent Service

1. In SAP BTP cockpit, navigate to your development SAP BTP subaccount named `XP266_DEV`.
2. Go to **Services** > **Instances and Subscription** and open **Content Agent Service** in the Subscriptions area to access the UI.
        <br>![](../ex4/images/btp_cas.png)
3. The Content Agent Service Overview page opens. In here navigate to Cloud Transport Management.
4. Choose **TransportManagementService** as Destination and click **Refresh Connection**. The status should be **Connected**.

## Exercise 4.2 - Create and send a Transport Request in SAP Content Agent Service UI

In SAP Content Agent Service, you will now prepare a transport request containing development content provided by the SAP Mobile Services SDK.

1. In SAP Content Agent Service UI, go to **Export**.
        <br>![](../ex4/images/cas_export.png)
2. Tick XP266DEVMS and XP266DEVMSRES of Type Mobile application.
        <br>![](../ex4/images/cas_transportrequest_content.png)
3. Go to **Step 2**
4. As Export Mode leave SAP Cloud Transport Management
5. Choose ``DEV`` as your Source Node.
6. Enter a description e.g. ``My low-code application``
7. Continue with **Step 3** and  **Step 4** to trigger **export** to SAP Cloud Transport Management Service.
        <br>![](../ex4/images/cas_transportrequest_submit.png)

## Summary

You've now created a transport request via SAP Content Agent Service by bundling low-code development content provided by SAP Mobile Services.

In the next exercise you will verify the creation for two transport requests. One that has been created in this exercise 3 and one that has been created in the previous exercise 4.

Continue to - [Verify all Release Steps](../ex5/README.md)
