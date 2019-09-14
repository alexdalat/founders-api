# Founders Api
An API connected to the Founders' server hosting panel.

# Glossary
* [Users](#user-apis)
  * [All](#get-all-users-info)
  * [Single](#get-specific-users-info)
* [Servers](#server-apis)
  * [All](#get-all-servers-undetailed-info)
  * [Single](#get-specfic-servers-undetailed-info)

## User APIs
#### Get specific users' info
* `/users/<userid>/`
```json
[
    {
        "username": "TestUser1",
        "rank": "Member",
        "servers": "2,4",
        "lastSeen": 1567893766,
        "created": 1567893766
    }
]
```

#### Get all users' info
* `/users/all/`
```json
[
    {
        "username": "TestUser1",
        "rank": "Member",
        "servers": "2,4",
        "lastSeen": 1567893766,
        "created": 1567893766
    }, 
    {
        "username": "TestUser2",
        "rank": "Member",
        "servers": "1,5",
        "lastSeen": 1567893785,
        "created": 1567893785
    }, 
    {
        "..."
    }
]
```

## Server APIs
#### Get specfic servers' undetailed info
* `/servers/<id>/`
```json
[
    {
        "domain": "mc.google.com",
        "ip": "8.8.8.8",
        "port": 25565,
        "name":"Google MC",
        "server-jar": "spigot-1.14.4"
    }
]
```

#### Get all servers' undetailed info
* `/servers/all/`
```json
[
    {
        "domain": "mc.google.com",
        "ip": "8.8.8.8",
        "port": 25565,
        "name":"Google MC",
        "server-jar": "spigot-1.14.4"
    }, 
    {
        "domain": "mc.yahoo.com",
        "ip": "209.191.122.70",
        "port": 25566,
        "name":"Yahoo MC",
        "server-jar": "spigot-1.14.4"
    },
    {
        "..."
    }
]
```

---

## Task List:
- [x] connect domain to api
- [x] create a few simple api calls
- [x] work on creating libraries that utilize the api
- [ ] start/stop servers
- [ ] run commands on servers through api
- [ ] give you a cookie