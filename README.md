# Founders Api
An API connected to the Founders' server hosting panel.

## User APIs
**Get specific users' info**
* `/users/**<userid>**/`
```json
[{
    "username": "TestUser1",
    "rank": "Member",
    "servers": "2,4",
    "lastSeen": 1567893766,
    "created": 1567893766
}]
```

**Get all users' info**
* `/users/all/`
```json
[{
    "username": "TestUser1",
    "rank": "Member",
    "servers": "2,4",
    "lastSeen": 1567893766,
    "created": 1567893766
}, {
    "username": "TestUser2",
    "rank": "Member",
    "servers": "1,5",
    "lastSeen": 1567893785,
    "created": 1567893785
}, {
    ...
}]
```

## Server APIs
**Get specfic servers' (undetailed) info**
* `/servers/**<id>**/`









## Task List:
- [x] connect domain to api
- [x] create a few simple api calls
- [x] work on creating libraries that utilize the api
- [ ] start/stop servers
- [ ] run commands on servers through api
- [ ] give you a cookie