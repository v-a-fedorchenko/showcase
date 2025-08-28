# Diagrams Examples

## Reference Diagrams

![Alt Text](../diagrams/my-diagram.puml)

## Inline Diagrams

```puml
@startuml sign_in_sequence  
  
title "Sign In Sequence Diagram"  
  
actor User  
participant "@action authenticate" as authenticate
entity User as UserModel  
  
User -> authenticate: {"email": email, "password": password}
```