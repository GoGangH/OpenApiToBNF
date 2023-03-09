# BNF
```
    paths := pathsObject
    pathsObject := pathObject *
    pathObject := "/"<IDENT> ": {" PathItemObject "}"
    PathItemObject :=  ["$ref"...]
    $ref := <String>
    get := OperationObject
    OperationObject := ["tags"...]
    tags := "array" <String>