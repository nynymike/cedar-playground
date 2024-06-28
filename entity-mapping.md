## Entity Mapping 

* **TrustedIssuer**: Created on startup from Policy Store
* **Client**: Created from access token 
* **Application**: Created if input supplies an Application name
* **Role**: Created for each `role` claim value in the joined id_token and userinfo token
* **User**: Created based on the joined id_token and userinfo token. `sub` is the entity identifier
* **Access_token**: 1:1 mapping from claims in token
* **id_token**: 1:1 mapping from claims in token
* **Userinfo_token**: 1:1 mapping from claims in token

