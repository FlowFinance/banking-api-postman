# banking-api-postman

Here you will find Postman's files to get started using the Banking API faster.

All of the endpoints are available here but also documented in our official documentation. You can take a look at https://flowfinance.readme.io/

All endpoints need to be authenticated, so make sure you have credentials to access the Banking APIs. 

## environment

Import the file `Flow Finance - banking api (sandbox).postman_environment.json` and fill the following variables with the correct values:

- originator_client_id
- originator_client_secret

Don't worry about `originator_access_token`, this value will be automatically filled.

## originator

If you're an originator, you should import the file `Flow Finance - banking api [originator].postman_collection.json`.

## authentication

Before using the api endpoints, you need to request a valid authentication token, to do this, you need to invoke the collection request named `update access token` inside of `authentication` folder. This request will fill the environment variable used to authenticate the requests.

## values used in the example collections

Please override the values used in the example collections (path, body...) with necessary values. 
