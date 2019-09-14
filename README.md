# founders-api
An API connected to the Founders' server hosting panel.

API Call     | Description                              | Errors                              | Example Result
-------------|------------------------------------------|-------------------------------------|----------------------------------------
`/users/:id/`|Returns info about a specific user.       |*404 - Not found. *500 - Fetch error.|`json`
             |                                          |                                     |`    {`
             |                                          |                                     |`        "username":"Xelada",`
             |                                          |                                     |`        "rank":"Admin",`
             |                                          |                                     |`        "servers":"2,4",`
             |                                          |                                     |`        "lastSeen":1568418961,`
             |                                          |                                     |`        "created":0`
             |                                          |                                     |`}`






Task List:
- [x] connect domain to api
- [x] create a few simple api calls
- [x] work on creating libraries that utilize the pai
- [ ] start/stop servers
- [ ] run commands on servers through api
- [ ] give you a cookie