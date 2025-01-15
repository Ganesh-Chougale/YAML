when we write a stand alone `string`, `number` or `boolean` it is a scaler inside a yaml file  
```yaml
"this is a scaler"
```  
```yaml
"this is yet another scaler"
```  
we dont need give double quotes until it has more than one consecutive white spaces, YAML reserved keywords or special character inside it  
```yaml
this scaler do not need double quotes
```  
```yaml
"this scaler, !$# needs double quotes"
```  
```yaml
"this scaler    needs double quotes"
```  