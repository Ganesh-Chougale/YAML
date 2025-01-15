Combine mappings using the `<<` merge key.

# Example:
```yaml
defaults:
  timeout: 30
  retries: 3

config:
  <<: *defaults
  retries: 5
```  
In YAML, the **`<<` merge key** is used to merge mappings. When applied, it includes all the key-value pairs from the referenced mapping. 

### Key Rules:
1. The value of `<<` is typically an alias (`*defaults`), referencing another mapping.
2. The content of the alias is merged into the target mapping.
3. Any existing keys can be **overridden** by specifying them after the merge.

In the example, `config` inherits from `defaults`, but the `retries` value is overridden to `5`.