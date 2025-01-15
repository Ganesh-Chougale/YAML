this is valid yaml because it has no duplicate value✅  
```yaml
names:
 ? ganesh
 ? gorav
 ? vorag
```  
but this is  not valid yaml because it has duplicate value❌  
```yaml
names:
 ? ganesh
 ? gorav
 ? vorag
 ? ganesh
```  