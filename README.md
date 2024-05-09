# Tunnel Client

Rebuild from [Localtunnel](https://github.com/localtunnel/localtunnel)

# Features

1. Add basic auth

    Add basic auth with `--username` and `--password` arguments

# Start

Start tunnel using pm2

```
pm2 start src/index.js -- --port 8080 --subdomain domain --username yourusername --password yourpassword
```