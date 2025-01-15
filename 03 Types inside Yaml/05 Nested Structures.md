YAML allows deeply nested mappings and sequences  
```yaml
employees:
  - name: Alice
    role: Developer
    skills:
      - Python
      - YAML
  - name: Bob
    role: Designer
    skills:
      - Photoshop
      - Illustrator
```  

#### Additional Notes:
- Spaces vs Tabs: Only spaces should be used for indentation, and they must be consistent (usually 2 or 4 spaces per level).  
- Complex Nesting: You can have even deeper nesting where sequences and mappings are mixed. Just make sure each level of nesting is properly indented.  
```yaml
company:
  name: TechCorp
  departments:
    - name: Development
      employees:
        - name: Alice
          role: Developer
          skills:
            - Python
            - YAML
    - name: Design
      employees:
        - name: Bob
          role: Designer
          skills:
            - Photoshop
            - Illustrator
```  