# learn_mongo

add role
```
db.createRole({role:'sysadmin',roles:[],
privileges:[
{resource:{anyResource:true},actions:['anyAction']}
]})
```

connect to db
```
use databaseyouwant
db.auth('username','password')
```

