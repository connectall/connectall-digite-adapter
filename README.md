# ConnectALL Digite Adapter

ConnectALL Digite Adapter is developed as an extension to the Universal Adapter capability of ConnectALL. The adapter specifications will let the user sync a Digite issue to another endpoint using the ConnectALL Integration Hub. A common use is that an ITSM application (like ServiceNow or Salesforce) will create an incident due to a customer reported problem and this incident will be cloned to Digite's backlog as an issue to be worked on. As the Digite issue is worked on any changes to status, priority, etc. can be synched back to the ITSM ticket..

Please refer to https://wiki.connectall.com/ca/latest/adapters/universal-adapter for more information

# How to use

## Import specifications
* Import digite_config.zip into ConnectALL using "Install custom adapter" feature.

## Define application links
* Create an application link in ConnectALL between Digite and another application of your choice.
* Navigate to `Configuration -> Connections` screen and create a new connection to Digite.
* In the Entity mapping tab under Advanced Properties choose "Sync Type" as POLL
* In the field mapping tab add the field that you want to sync between the applications.

> In order to use the Digite adapter you will need to get the license from ConnectALL sales team. Please reach out to sales@connectall.com for licenses and quotes.

