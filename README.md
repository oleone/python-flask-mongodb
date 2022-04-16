
## Start Commands

```docker exec -it mongodb bash```

```mongo  -u mongodbuser -p```

```password```

`show dbs`

`use pythonflaskdb`

`db.createUser({user: 'pythonflaskuser', pwd: 'pythonflaskpwd', roles: [{role: 'readWrite', db: 'pythonflaskdb'}]})`
`exit`

`mongo -u pythonflaskuser -p pythonflaskpwd --authenticationDatabase pythonflaskdb`