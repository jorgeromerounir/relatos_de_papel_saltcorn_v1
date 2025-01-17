# relatos_de_papel_saltcorn_v1


Quickstart with Docker
You can run a local instance for quick testing by running the following command:

docker-compose -p 'saltcorn_relatos_de_papel' up -d

and then go to http://localhost:3000 in your web browser.

NOTE: The dependencies to build mobile apps are quite large, they are not installed in the standard docker image (saltcorn/saltcorn). To use an image that includes the mobile dependencies as well, either use 'saltcorn/saltcorn-with-mobile' directly or replace 'saltcorn/saltcorn' with 'saltcorn/saltcorn-with-mobile' in the docker-compose file.
