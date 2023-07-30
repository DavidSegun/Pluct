# Pluct
A python client to json API
// BUILD STATUS //
from pluct import resource
app = resource.get("http://myapi.com/app/myapp")
//Verifying if the resource is valid
app.is_valid()
// Retriving the reource data
app.data
//Retriving resource schema
app.schema
//Testing
The tests directory contains the standard test stack for Pluck
