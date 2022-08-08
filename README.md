# Turbine

## Pre-requisites

### MongoDB Resource
```shell
meroxa resources create mdb --type mongodb -u "mongodb+srv://$MONGODB_USER:$MONGODB_PASSWORD@$MONGODB_HOST/myFirstDatabase?retryWrites=true&w=majority"
```
For this example I created a Shared MongoDB instance on [MongoDB Atlas](https://www.mongodb.com/atlas).