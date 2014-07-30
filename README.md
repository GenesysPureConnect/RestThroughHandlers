Rest Through Handlers

===================


See blog at https://developer.inin.com/blog/Pages/RestThroughHandlers.aspx

These handlers can be used to call external web services from handlers or listen to inbound requests and respond to them.

Handler Description
-------------------

JSONToList.ihd - takes a simple JSON object and converts it into two lists of Names and Values

ListToJSON.ihd - Takes two lists of Names and Values and converts into a JSON object

RestMakeRequest.ihd - Handler that wraps making a request to an external web service

RestParseMethod.ihd - Gets the HTTP method (GET,POST,PUT,DELETE) and the uri from the HTTP payload.

RestRead.ihd - Reads the TCP connection and parses out the data.

RestRespond.ihd - Responds to an inbound request.


RestListenerSetup.ihd - Opens a TCP port on the server for listening

RestReceiver.ihd - Handles inbound TCP connections and parses out the HTTP data

RestTest.ihd - Example handler showing how to make an outbound request and getting the response. 
