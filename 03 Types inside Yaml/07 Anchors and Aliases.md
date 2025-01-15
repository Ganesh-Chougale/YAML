Reusing content with references:  
- Anchor (&): Define reusable content.  
- Alias (*): Reference the reusable content.  
```yaml
defaults: &default_settings
  timeout: 30
  retries: 3

server_1:
  <<: *default_settings
  host: server1.example.com

server_2:
  <<: *default_settings
  host: server2.example.com
```  
In YAML, **anchors (`&`)** and **aliases (`*`)** allow you to reuse content:

1. **Anchor (`&`)**: Defines reusable content, like `default_settings` in the example.
2. **Alias (`*`)**: References the content defined by the anchor, like `*default_settings`.
3. **Merge key (`<<`)**: Used to merge the content of the alias into another mapping.

In the example, `server_1` and `server_2` both inherit the settings from `defaults` (timeout and retries) and can add/override specific properties like `host`.