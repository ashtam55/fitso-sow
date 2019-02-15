## Node-RED setup for Fitso
This document to help as a guide, if needed for the Node-RED setup for the timebeing. 

## Current Setup
I have setup a small Node-RED flow which has
* 2 MQTT listeners, listing to
    * In-facility device 1 Humidity
    * In-facility device 1 Temperature
* 2 HTTP request Nodes, to forward this data to an endpoint
    This contains the URL endpoints used
* 2 debug node
    

## How to
You can simply edit any node by double clicking.

To change the HTTP endpoint, double click the HTTP node, to edit it.
Then change the URL.
I have used the variable __payload__ to append to the GET request


To add new nodes (from the list you would see on the left), simply drag and drop.


[Making your first flow](https://nodered.org/docs/getting-started/first-flow) page might be helpful.

## Thanks
Node-RED is an amazing tool to wire-up automated flows

## Need further help
Feel free to raise an issue on this git repo
Or mail me at kartik@akriya.co.in

