## Input Variables
* Values set by:
    * Defaault value
    * Environment variable
    * File (terraform.tfvars, or *.auto.tfvars)
    * Command line

Command line --> file --> environment variable --> if none of those then default value --> if no default value = null

## Output Variables
output to console

## Variable Types
* String: development, t2.micro
* Boolean: true/false
* Number: integers and fractional values
* List: [1, 5, 2, 9], var.environment_list[2] --> 0 indexed, all elements must be of the same type, and ordered
* Set:like a list but unordered
* Map: key-value pairs, values must be of the same type, keys are strings and must be unique 
* Object: Like a struct in C, KEY = VALUE value can be of any type, object({instance_type=string, monitoring=bool})
* Tuple: similar to objects, stricter type-conversion rules

