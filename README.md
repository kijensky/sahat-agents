 # add extension
 
 ```
 az vmss extension set \                                                                                                                                           ─╯
--vmss-name {vmss-resource-name} \
--resource-group {resource-group} \
--name customScript \
--version 2.0 \
--publisher Microsoft.Azure.Extensions \
--settings '{ "fileUris": ["https://raw.githubusercontent.com/kijensky/sahat-agents/main/myScript.sh"], "commandToExecute": "./myScript.sh" }'
```
