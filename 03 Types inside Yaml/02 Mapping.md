A collection of key-value pairs, similar to a dictionary or object in other formats.  
```yaml
person:
  name: Bruce wayne
  age: 30
  location: "@Gotham City!"
```  
the double quotes rule for key & value are same as for scaler  
only one addition difference is specially for `key`, if key has even one space it needs to put inside double qoutes  
```yaml
"my key with spaces": Hello World
"123startWithNumber": Value
"special:char": Value
```  