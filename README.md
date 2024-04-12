### What is this API intended to do?

This API should allow retrieving data from endpoints with:

Samples:
* Name
* Quantity
* Availability
* Description
* Specialty

### Architecture

RESTful architecture, resources are identified by URIs (Uniform Resource Identifiers), and the client interacts with those resources with standard HTTP methods such as GET, POST, PUT, and DELETE.

### Examples of GET method:

Get all samples:
Request: GET :/api/v1/samples

Get all samples by name:
Request: GET :/api/v1/samples/name

Other ideas for get requests:

* Get by availability
* Get by specialty
* Get by quantity

### Example of POST method:

* Create sample

### Example of PUT method:

* Update sample

### Example of DELETE method

* Remove sample

This would be an initial idea of this project.