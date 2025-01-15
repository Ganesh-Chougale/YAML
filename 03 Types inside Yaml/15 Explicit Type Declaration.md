```yaml
# String declared explicitly
string_value: !!str 1234

# Integer declared explicitly
integer_value: !!int "5678"

# Boolean declared explicitly
boolean_value: !!bool "true"

# Float declared explicitly
float_value: !!float "3.14"

# Date declared explicitly
date_value: !!timestamp "2023-01-15T10:00:00Z"

# Null value declared explicitly
null_value: !!null ""
```  
```yaml
# Binary data (Base64 encoded)
binary_value: !!binary |
  R0lGODdhEAAQAMQAAAAA

# Octal value (Base-8)
octal_value: !!int "075"  # Equivalent to 61 in decimal

# Hexadecimal value (Base-16)
hex_value: !!int "0x1A"  # Equivalent to 26 in decimal

# Comma-separated list (Array)
comma_separated_list: !!seq
  - apple
  - banana
  - cherry

# Positive Infinity
positive_infinity: !!float "Infinity"

# Negative Infinity
negative_infinity: !!float "-Infinity"

# Not a Number (NaN)
not_a_number: !!float "NaN"
```  
```yaml
null_key: "This is a value for a null key"
"null": "This is a value for a key with the string 'null'"
"": "This is a value for an empty key"
null: "This is a value for a null key (without quotes)"
~: "this a value of null key"
```  