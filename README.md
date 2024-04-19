Hubzilla - Customizations for Docker Image
==========================================


**What are these customizations?**

These customizations are available to users, to assist with ann create various functions, relating specifically to the docker image.


**Explain each customization?**
OK, here's what each customization does:

- update_db
    - update_db allows a user to update their DB from the command line, similarly to how they would if they accessed 'hubzilla_site/admin/dbsync'; this was created, as the docker image doesn't setup nor update in the intended way
