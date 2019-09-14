# Founders Api
An API connected to the Founders' server hosting panel.
Test

<table>
    <tr>
        <th>API Call</th>
        <th>Description</th>
        <th>Errors</th>
        <th>Example Result</th>
    </tr>
    <tr>
        <td markdown="1">
        `/users/:id/`
        </td>
        <td>
        Returns info about a specific user.
        </td>
        <td>
        * 404 - Not found. * 500 - Fetch error
        </td>
        <td>
<pre><code>{
    "username":"Xelada",
    "rank":"Admin",
    "servers":"2,4",
    "lastSeen":1568418961,
    "created":0
}</code></pre>
        </td>
    </tr>
</table>






Task List:
- [x] connect domain to api
- [x] create a few simple api calls
- [x] work on creating libraries that utilize the api
- [ ] start/stop servers
- [ ] run commands on servers through api
- [ ] give you a cookie