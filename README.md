# ECOM-ORDER-SERVICE <br/>
Service responsibility & interaction<br/> 
	&nbsp;- Manages order creation, updates.<br/>
	&nbsp;- Responsible for validating orders, calculating totals and assigning order IDs.<br/>
	&nbsp;- Publishes order created event to Service Bus for downstream processing.<br/>
	Interaction:<br/>
	&nbsp;- Receives data from client through API Gateway.<br/>
	&nbsp;- Sends message to service bus for downstream processing.<br/>
	&nbsp;- Reads inventory availability via inventory service API.<br/>
	&nbsp;- Sends notification via notification service.<br/>
