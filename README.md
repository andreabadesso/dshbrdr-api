# API for Dshbrdr

Using Express.JS, will receive data via REST and store it

* Expects data to come in this format:

```JSON
{
    "uniqueKey": "TIDE:18281",
    "data": [
        ...
    ]
}
```

* Returns status code 200 for success, 500 for error

```JSON
{
    "status": 200
}
```
