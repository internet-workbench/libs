# libs
This repo contains the approved javascript libraries for the Internet Workbench. The Internet Workbench uses requirejs to load external libraries, so anything here conforms to that standard.

If you would like a library included, please send a pull request.

We are using a maven like structure for flexibility. All javascript libraries have the equivalent of an artifactId (the name) and a version. We need to add the equivalent of the maven groupId, which is similar to a reverse domain name. It is guarenteed to be unique for a contributor, so it will avoid any name conflicts in the libraries.

The path to the library is groupId/artifactId/version/artifactId-version.js

This will also accomodate other files types, such as templates and css.
