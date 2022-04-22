# Send-Notifications
Related to this blog: https://blogs.sap.com/2020/10/14/mobile-push-notifications-in-s4hana-ecc-using-standard-fiori-client-part-2/

This is a sample program to send notifications from sap backend

Remember that you need to define your own values on the following constants that are located on the Z_PUSH_NOTIFICATION_TOP include:

- c_rfc_scpms  --> Should contain the name of the RFC you have defined in t-code SM59
- c_query      --> Should contain the app name you have defined in the SCPms console

