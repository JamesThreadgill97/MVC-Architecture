### Software Design Patterns
- Scaling
- Teamwork
- Testing/Debugging

# Separation of Concerns
## Everything should be separated to make it easier to work on a project
- E.g.
	- html file
	- css file
	- js file

#### Components
Every element on the page should be broken down into components

## DATA

- in/out -> APIs
- around -> state & models


### MVC

Used in the back end
Used to structure data flow in application
Separate logic, routes, data etc

#### Model - Where the data lives
- Handles Data logic
- Interacts with Database
#### View - Client
- Handles data presentation
- Dynamically rendered
#### Controller - Mediator between the model and the view
- Handles request flow
- Never handles data logic

![[Pasted image 20230926115345.png]]

### Microservices

### Monolithic

![[Pasted image 20230926115635.png]]

#### OOP 
Method on a class - Static Method
Method on an instance - Instance Method
		
	const api = require("../api location")
	class Name {
		constuctor (name) {
			this.obj = name.obj
		}

		static <function name>() {
			return new Name();
	}
	module.exports = Name




## CRUD Application

Create Read Update Delete

GET 
POST
PATCH
DELETE
### REST
#### Representational State Transfer

##### Request
- HTTP Verb
- Headers
- Body
- Path
##### Response
- Status Code
- Message
- Content Type

Restful Function Keywords
index -> Get everything
create -> Post
show -> Get by ID
update -> Update function
