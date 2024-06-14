# eWebtel-API-test
Commercial API test done according to provided documentation

API description:

API designed to fetch the data from the eWebtel platform.

eWebtel is the data acquisition system for the devices produced by PLUM company; data loggers for the gas and water measurement.

Because data transmission between devices and eWebtel is encrypted, and policy of gas companies sometimes do not allow for using external systems or protocols, therefore API is established, to fetch the data directly from eWebtel in JSON format.

Scope of the tests:

1. Check if the authentication token is generated according to provided documentation
2. Check basic requests
3. Check data correctness if the timestamp and sample match the value from the system (manual comparing with csv file)
4. Check if authorization token validity time is equal to 2h

