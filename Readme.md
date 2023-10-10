# Bicep Modules
## Publish
In order to publish a module to a container registry I can type:  

* **Item A**
* Item B
---
- *Item A*
- Item B
---
1. Item 1
2. Item 2

[Link](https://google.com)

```sh
az bicep publish --file .\network\network.bicep --target br:eruza.azurecr.io/bicep/modules/network:v0.0.2
```

> az bicep publish --file .\network\network.bicep --target br:eruza.azurecr.io/bicep/modules/network:v0.0.2
