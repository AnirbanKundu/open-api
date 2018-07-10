# About the Repo

This repository shows an unobtrusive way to generate Swagger Spec. Means, there is no annotations defined in the code. All API definition is defined in the YAML file only. 
The documentation of the API is hosted in https://app.swaggerhub.com/apis/AnirbanKundu/UserAPI/3.0.0 

### SwaggerHub AWS Gateway Integration 
SwaggerHub provides easy hooks to automate with your API gateways. The Swagger Spec is passed to the gateway layer to generate the external APIs. Not only that, Swagger has plug-ins through which the Spec in Swagger Hub can be kept in sync and vice-versa. 

### AWS Gateway URI 
https://27mg0lfx5a.execute-api.us-west-2.amazonaws.com/PROD/v3/users/119

The app original URI is : https://open-api-user.herokuapp.com/v3/users/111 

### Documentation Hosting 
Either SwaggerHub or https://api-docs.io/ could be used to used to host the documentation 

### Run App from local 

    Clone the repo
    npm install
    node app.js
