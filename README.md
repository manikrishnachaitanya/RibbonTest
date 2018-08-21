# RibbonTest
This is a sample app using spring-boot to test to Netflix Ribbon. 
HelloApplication is a simple spring boot app. HelloAppClient demos a ribbon client.


HelloApplication is a simple spring-boot Rest based application which returns a greeting String. 
This application can be replicated to run on 3 ports (say 8090,9092,9999) for complete testing. 

HelloAppClient demonstates a Ribbon client which invokes HelloApplication using a RestTemplate to get the greeting message.
This application has to run on a different port (say 9092).
This uses Netflix Ribbon to load balance the requests to the above 3 clients.
