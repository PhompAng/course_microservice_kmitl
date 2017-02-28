##Evolution of Architecture
- monolith
	every service in single coomputer
	tigh copuling
- tiers
	split to multiple layers 
- soa
	many services work w/ each others
- microservice
	split to many service deployed to many computer
	all service sperate from each other

#Monolith
- pros
	+ simple
- cons
	+ single point of failure
	+ only scale up

#tiers
+ Presentation Layer 
+ Application Layer (sublayer of BLL)
+ Business Logic Layer (BLL)
+ Data Access Layer

	## Three-tier architecture
	+ Presentation Tier - display information
	+ Application Tier - perform detailed processing
	+ Data Tier - data persistence mechanisms 
- pros
	+ scale easier
	+ better and finer security control (enforce the security differently for each tire)
	+ Independence tier upgerading
	+ Better reusability
- cons
	+ More cost for hardware, network, maintenance, and deployment

#SOA
+ Service Provider - It create a web service and provides its information to the service registry. 
+ Service Requester - It locate entries in the broker registry and then bind to the service provider in order to invoke one of its web services.
+ Service Registry - Make the information regarding the web service avaliable to any requester.

- pros
	+ Service reusability
	+ Easy Maintainability
	+ Greater Reliaibility
	+ Improve Scalability
	+ standard
- cons
	+ Increased Overhead 
	+ complex service management
	+ work with same standard service

+ Enterprise service bus - implement of communication system between service


	# Implementation Approach

	## WebService
	- An implementation of soa
	- Webservice Description Language (WSDL) + Universal Description, Discovery and Integration (UDDI)
	- Simple Object Access Protocol (SOAP) - protocol sepcification for exchanging structured information 
	- YO mama so fat

	## REST (REpresentational State Transfer)
	- rides directly on HTTP
	- slim

	## microservice
	- call service via API gateway
	- each service use rest api
		

