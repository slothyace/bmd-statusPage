# Status Page
![Action Interface](image.png)

## Documentation
### Host
The `ip` address to host the site on. By default, it is pre-configured to `localhost` (local machine availability).<br>
If left empty, defaults to `localhost`.<br>
To host it such that it is available on your local network, host it on `0.0.0.0`.

### Port
The `port` number to listen to. By default, it is pre-configured to port `3000`.<br>
If left empty, defaults to port `3000`.

### Login Username
The username to login with.<br>
If left empty, defaults to `user`.

### Login Password
The password to access the site with.<br>
If left empty, defaults to `password`.

### Login System
By default, it is set to `Basic Login`, meaning it uses the browser's native authorization headers which essentially amounts to a small login pop-up.

If `Token Login` is chosen as the login system, it switches over to using `cookies` and a dedicated login page.<br>
`cookies` are valid until bot restarts as they're wiped upon the process going offline.

### Graph History Count
How many data points are there on the CPU/RAM usage graphs.

### Console History Count
How many console logs / errors to keep in the `Logs` pane of the site.

### Update Interval
How often the usage graph updates in seconds. This is independant of console updates.

### Theme
The theme of the status page, alternative themes are available [here](https://github.com/slothyace/bmd-statusPage/tree/main/themes).