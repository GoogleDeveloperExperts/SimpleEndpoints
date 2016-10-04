# SimpleEndpoints
With SimpleEndpoints, you can turn your app engine project into Parse-like service. It automatically creates CRUD endpoints for all entities without any coding. You can now focus on building enpoints that has business logic.

# Endpoints
You can pull this repo as eclipse project and deploy it as one of the versions of your app engine project. Once deployed, you will have access to the following endpoints:

# Read Endpoint
List of all entities of a kind - GET https://endpoints.myproject.appspot.com/entity/<kind>
Read of an entity for the list - GET https://endpoints.myproject.appspot.com/entity/<kind>/<id>

# Update Endpoint
Update of an entity - PUT https://endpoints.myproject.appspot.com/entity/<kind>/<id>

# Create Endpoint
Create of an entity - POST https://endpoints.myproject.appspot.com/entity/<kind>/<id>

# Delete Endpoint
Delete of an entity - DELETE https://endpoints.myproject.appspot.com/entity/<kind>/<id>
