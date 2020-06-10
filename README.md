# Sentinel 

## Features

* Should act as a middleware for K8S and Traefik.
* Should provide a UI.
* Should allow users to login via SSO
* Should allow admins to manage users
* Should allow client admins to manage users belonging to a group/organisation
* Password policies should be dynamically configurable via the UI.
* Should allow users to register their own password.
* Password policies:
	* Set password to expire after a time period
	* Set minimum password strength requirement
* Admins should be able to view when the password was last used
* Admins should be able to easily add bypass rules/trusted sources via the web ui
* Should provide an API for web clients to integrate with
