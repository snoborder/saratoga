# Saratoga Logs Analyzer
### Copyright DevB 2016-2021

![Logo](img/saratoga01.png)

### License MIT

## Makefile
### build, clean, run, prune, status. test
#### Ensure you change the folder name in S_INSTALL in Makefile 
```
    make [cmd]
    ## Examples
    make build
    make test ARGS="vpcId"
```

### Parameters in curl post
```
accessKeyId, accountId, arn, creationDate, dBInstanceArn
eventName, eventSource, eventTime, principalId
recipientAccountId, awsRegion, sourceIPAddress
subnetIdentifier, vpcId
```