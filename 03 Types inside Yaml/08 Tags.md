Custom data types with explicit tags.

# Example:
```yaml
timestamp: !!timestamp "2023-01-15T10:00:00Z"
binary_data: !!binary |
  R0lGODdhEAAQAMQAAAAA
```

In YAML, **custom data types** can be defined using **explicit tags**:

- `!!timestamp` is used to indicate a timestamp format, ensuring YAML knows it's a date-time value.
- `!!binary` denotes binary data, and the pipe (`|`) indicates multiline content.

### Key Rules:
1. **Custom tags**: Tags like `!!timestamp` or `!!binary` define non-standard types.
2. **Data formatting**: The value after the tag must match the expected format for that type.
3. **Multiline content**: For binary data, the pipe (`|`) allows for multiline strings. 

Custom types allow for specialized parsing or handling in YAML parsers.