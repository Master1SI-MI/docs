# Documentation

This repository will hold all docs related to the project such as :
-   grpc protos
-   api definitions


# Generate API docs

For generating api docs pages use the command below, but change parameters, because you might want to generate api docs for auth **yaml files**
```sh
sudo docker run --rm   -v ${PWD}:/local openapitools/openapi-generator-cli generate   -i /local/openapi/auth/auth.yaml   -g html   -o /local/pages/auth/
```