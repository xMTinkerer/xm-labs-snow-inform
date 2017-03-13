# Inform with xMatters for the ServiceNow integration
The [xMatters integration for ServiceNow](https://store.servicenow.com/sn_appstore_store.do#!/store/application/5950d7444f2231000e9fa88ca310c78c) provides a several find and assign workflows for tracking down responsible parties for an Incident. However, there are cases where the need for informing other people about an Incident or providing updates regarding an Incident are important. This is where Inform with xMatters comes in. It does not target any users and instead relies on [subscriptions](http://help.xmatters.com/OnDemand/user/subscriptions.htm) to determine who wants to be notified. 

# Pre-Requisites
* ServiceNow Fuji or Istanbul
* ServiceNow integration to [xMatters v3.7.11+](https://store.servicenow.com/sn_appstore_store.do#!/store/application/5950d7444f2231000e9fa88ca310c78c/3.7.12)
* xMatters account - If you don't have one, [get one](https://www.xmatters.com)!

# Files
* UPDATEME

# Installation


## Configure ServiceNow
Specific steps go here

## Configure xMatters
1. Create a new Shared Library or (In|Out)bound integration
2. Add this code here:
   ```
   var items = [];
   items.push( { "stuff": "value"} );
   console.log( 'Do stuff' );
   ```
   
# Testing
Be specific. What should happen to make sure this code works? What would a user expect to see?

# Troubleshooting
Optional section for how to troubleshoot. Especially anything in the source application that an xMatters developer might not know about. 
