this is a mapping  
```yaml
"Bharat" : "im most diverse nation in the world"
"007" : "the name is bond!, James Bond"
```
this is a sequence  
```yaml
- apple
- banana
- Apple
- Banana
``` 
what if we want to bind that in single file?  
we can do it with using triple dashes: ---  

```yaml
"Bharat" : "im most diverse nation in the world"
"007" : "the name is bond!, James Bond"
---
- apple
- banana
- Apple
- Banana
...
```  
In YAML, you can separate different documents within a single file using the **triple dashes (`---`)**. 

### Key Rules:
1. **Triple Dashes (`---`)**: Marks the start of a new document in a multi-document YAML file.
2. **Multiple Documents**: Each section (e.g., a mapping or sequence) can be a separate document, and `---` is used to separate them.
3. **Order of Documents**: YAML parsers will process each document independently in the order they appear.
4. **Triple Dots (`...`)**: to end yaml document