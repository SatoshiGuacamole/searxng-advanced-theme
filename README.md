# searxng-advanced-theme

This theme adds advanced filters to your SearxNG homepage.

## Getting started

### 1. Place directory contents in `/usr/local/searxng/searx/templates/advanced/`

`git clone https://github.com/SatoshiGuacamole/searxng-advanced-theme.git /usr/local/searxng/searx/templates/advanced/`

### 2. Launch uwsgi
`exec uwsgi --http-socket 0.0.0.0:80 --ini /usr/local/searxng/dockerfiles/uwsgi.ini --ini /usr/local/searxng/searx/templates/advanced/uwsgi.ini`
