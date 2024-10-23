

Data Transfer Object = CSharp representation of JSON data
Data Access Object = Database representation of Object
Data Validation Object = 

Serialize = From Code to JSON
Deserialize = From JSON to Code

\[Consumes] heißt deserialization 

Controller = RestAPI uses DTOs


builder.Services.AddScoped = Map an Interface to an Implementation, from now on *ONLY* use the Interface

Scoped... The same implementation is used for every call
Transient... Creates a new implementation instance for every call


Für JSON... DTO
Für BL... DAO


Work in Containers when done... in Debugger when coding


Validation Framework "Fluent Validation" -> Validator

Write Validators that check whether an Object is valid...
replaces massive if else if blocks

RuleFor<x => x.Username>
.NotEmpty()
.MinimumLength(3).withMessage("Minimum length = 3")
.NotEmpty.withMessage("Username is required")

