# Bachelor Thesis. Files are not avaliable due to NDA (since it was a production project).

Installation and configuration of a cloud and a chat application to work with an existing custom Web application, sharing the same users via the LDAP protocol, using a Single Sign On mechanism and fully managed by a Java library.

I set up and fully configure on a vps: openLDAP, Nextcloud , Rocketchat , Keycloak , elasticsearch.
I developed a Java library to fully manage the above. 

Install NextCloud (lamp stack).

Install RocketChat (Snaps).  
Install openLDAP as the main db.  
Install KeyCloak for SSO.  
Install ElasticSearch for OCR and full text search.  
Fully configure them to communicate with each other. The main db was openLDAP and all the users were imported from there to all the applications.  
Using NextCloud, RocketCHAT , openLDAP API i developed a library(wrappper) to fully manage all of the above.   
All of those were build on an existing Java web application.  
