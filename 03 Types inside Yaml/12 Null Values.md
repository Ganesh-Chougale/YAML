Explicit null representation.

# Example:
```yaml
key_with_null_value: null
key_without_value:
```

In YAML, **explicit null values** can be represented in two ways:

1. **Using `null`**: You can explicitly set a key’s value to `null`, like `key_with_null_value: null`.
2. **Empty value**: A key without a value (i.e., `key_without_value:`) is interpreted as `null`.

### Key Rules:
- `null` is case-insensitive (e.g., `NULL`, `Null` are also valid).
- The empty key without a value is also treated as `null`, but is less explicit.
Both methods indicate that the value is intentionally empty or missing.