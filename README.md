# classic-node-server
<p>a node server without any external dependencies, for CRUD of users into a JSON database</p>

### To run
<code>npm run dev</code>

### Base Url
<code>http://localhost:3333</code>

## Resources
**<code>/users</code>**

### Methods
- <code>GET baseURL/users</code>
- <code>POST baseURL/users</code>
- <code>PUT baseURL/users/:id</code>
- <code>DELETE baseURL/users/:id</code>

### Query Params
- for name searches 
- <code>GET baseURL/users?search=john</code>
