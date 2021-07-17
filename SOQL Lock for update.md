https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/langCon_apex_locking_statements.htm
In Apex, you can use FOR UPDATE to lock sObject records while they’re being updated in order to prevent race conditions and other thread safety problems.

```Java
 Account [] accts = [SELECT Id FROM Account LIMIT 2 FOR UPDATE];
```

#Salesforce