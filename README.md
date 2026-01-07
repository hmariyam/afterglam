# Afterglam 💄💫
Afterglam is a completely free platform designed to recycle expired makeup by allowing clients to donate their unused or expired cosmetics to funeral homes. Clients can submit donation requests on Afterglam, enabling funeral homes to collect the cosmetic products they need. This helps reduce waste from unused or unfinished makeup. As a result, funeral homes also avoid spending money on new cosmetic products.

# Developement
In this project, we will develop a database that allows retrieving, modifying, and deleting data. To achieve this, we will create the database creation script, the tables, and the initial data to insert. This database will be created and connected on the Idéfix server. We will also deploy this database on Docker Desktop in its own container. When a client submits a donation request, the Afterglam application sends the request to the API (controller layer), then to the server side in the service layer, and finally to the database. To return the result, the database sends SQL data back to the service layer, then to the API, which interprets the result as JSON and displays it on the interface. Therefore, we will need to create the interface, the business layer containing the service layer and data access, as well as the server-side logic and the database.

# Authors
- <a href="https://github.com/LeenAlHarash">leen<a>
- me

# User Roles: Admin & Client
Administrators can:
- View client information
- View admin information
- Create cosmetic products
- View donation forms and see which ones are handled by other administrators
- Search funeral homes, clients, forms, and cosmetics by their ID

Clients can:
- Create a form and fill it out with their information
- View funeral homes
- Find their submitted forms using their email address
- View the list of available cosmetics
