# kilsar-ar-html-content
The html content for the MVP app

The HTML displayed inside the app will respond to the following structure

```
ario-ar-demo://<action>/<complement>
```

## Available actions:

```javascript
  back
  next
  scanObject
  listSavedObjects
  showUrl // (requires <complement>  as the url to present)
  showStep // (requires <complement> = the step number)
  
```

### Example:

```javascript
ario-ar-demo://back
ario-ar-demo://scanObject
ario-ar-demo://showUrl/https://www.boeing.com/resources/boeingdotcom/commercial/airports/737-family/737-800/docs/737-800_Airplane_Characteristics_for_Airport_Planning.pdf
```
