::: moniker range="vsts"

## YAML snippet

```YAML
# Chef
# Deploy to Chef environments by editing environment attributes
- task: Chef@1
  inputs:
    connectedServiceName: 
    environment: 
    attributes: 
    #chefWaitTime: '30' 
```

::: moniker-end