YAML supports multiline strings using two styles:  

- Literal Block (|): Preserves line breaks.  
- Folded Block (>): Folds newlines into spaces.  

```yaml
literal_block: |
  This is line 1.
  This is line 2.

folded_block: >
  This is a long sentence
  that spans multiple lines
  but will be folded into one.
```  