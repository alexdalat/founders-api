# Founders Api
An API connected to the Founders' server hosting panel.

## User APIs
**Returns info about a specific user.**
* `/users/:id/`
```json
[{
    "username": "TestUser1",
    "rank": "Member",
    "servers": "2,4",
    "lastSeen": 1567893766,
    "created": 1567893766
}]
```

**Returns info about all users.**
* `/users/all/`
```json
[{
    "username":"TestBot1",
    "rank":"Admin",
    "servers":"2,4",
    "lastSeen":1568418961,
    "created":0
}, {
    "username": "TestUser2",
    "rank": "Member",
    "servers": "1,5",
    "lastSeen":1567893785,
    "created":1567893785
}]
```








## Task List:
- [x] connect domain to api
- [x] create a few simple api calls
- [x] work on creating libraries that utilize the api
- [ ] start/stop servers
- [ ] run commands on servers through api
- [ ] give you a cookie