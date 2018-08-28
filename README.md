# Swagger Project Integration Sample 
Quick demonstration to include swagger editor in an existing project.

The package.json has the script used to locate the swagger.yaml file:
```json
{
  "scripts": {
    "edit": "swagger_swagger_fileName=docs/swagger/swagger.yaml swagger project edit"
  }
}
```
### Requisites
- npm
- swagger
 ```sudo npm install -g swagger```

### Setup

1 - Clone or download this repository.
2 - Change directory to the root path.
3 - Run this command
```bash
npm run edit

> event-api@0.0.1 edit /home/oromero/Downloads/Swagger/Swagger
> swagger_swagger_fileName=docs/swagger/swagger.yaml swagger project edit

Starting Swagger Editor.
Opening browser to: http://127.0.0.1:35361/#/edit
Do not terminate this process or close this window until finished editing.
```

### Swagger Editor
Go to your browser and start rocking... 
```
http://127.0.0.1:35361/#!/
```