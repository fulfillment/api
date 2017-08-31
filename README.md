# Fulfillment.com API v2 OpenAPI Specification

Our current version is hosted at https://api.fulfillment.com/v2

## Links

- [Official Documentation](https://fulfillment.github.io/api/) (ReDoc)
- [SwaggerUI](https://fulfillment.github.io/api/swagger-ui/)
- Look full spec:
    + JSON https://fulfillment.github.io/api/swagger.json
    + YAML https://fulfillment.github.io/api/swagger.yaml


## Working on specification
[![Build Status](https://travis-ci.org/fulfillment/api.svg?branch=master)](https://travis-ci.org/fulfillment/api)

Note use node v6 or lower, to manage your node version look into '[n](https://github.com/tj/n)'

1. Run `npm start`
2. Checkout console output to see where local server is started.
3. Make changes using your favorite editor or `swagger-editor` (look for URL in console output)
4. All changes are immediately propagated to your local server, moreover all documentation pages will be automagically refreshed in a browser after each change
**TIP:** you can open `swagger-editor`, documentation and `swagger-ui` in parallel
5. Once you finish with the changes you can run tests using: `npm test`

After you have committed your changes the above links will be updated only after Travis CI finishes deployment.