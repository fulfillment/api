# Fulfillment.com API v2 OpenAPI Specification

- [Official Documentation](https://fulfillment.github.io/api/) (ReDoc)
- JSON https://fulfillment.github.io/api/openapi.json
- YAML https://fulfillment.github.io/api/openapi.yaml


## FDC Developers

Make changes in the swagger link here:
https://editor.swagger.io/

If there is nothing in the editor, copy/paste the openapi.yaml contents into it. This YAML file is the file we 
update. You must then generate the JSON file from the YAML file somehow (used to be free on swagger before). You must 
commit both 
files when you are 
finished. 

```bash
docker pull swaggerapi/swagger-editor
docker run -d -p 3000:8080 swaggerapi/swagger-editor

docker ps
docker stop [id]
```
