# Fulfillment.com API v2 OpenAPI Specification

- [Official Documentation](https://fulfillment.github.io/api/) (ReDoc)
- JSON https://fulfillment.github.io/api/openapi.json
- YAML https://fulfillment.github.io/api/openapi.yaml


## FDC Developers

https://editor.swagger.io/

```bash
docker pull swaggerapi/swagger-editor
docker run -d -p 3000:8080 swaggerapi/swagger-editor

docker ps
docker stop [id]
```

docker pull swaggerapi/swagger-ui
docker run -p 5000:8080 -e BASE_URL=/api -e SWAGGER_JSON=/docs/openapi.json -v ${PWD}/docs:/usr/share/nginx/html/ swaggerapi/swagger-ui
docker run -p 5000:8080 -e BASE_URL=/api -e SWAGGER_JSON=$(pwd)/docs/openapi.json -v $(pwd)/docs:/tmp swaggerapi/swagger-ui
