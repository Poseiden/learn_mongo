# learn_mongo

### add role
```
db.createRole({role:'sysadmin',roles:[],
privileges:[
{resource:{anyResource:true},actions:['anyAction']}
]})
```

