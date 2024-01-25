# evoting_app
Learn how to build a secure voting platform with Django.

## it runs as an app in digital ocean

1. Source: https://github.com/curious-mind-free-soul/evoting_app
1. Environment Varibles
   - DEBUG: False
   - DATABASE_URL: postgres://...:...@dpg-cmkuh8f109ks73a3kggg-a.oregon-postgres.render.com/...
1. Commands
   - Build Command
   - Run Command:
     gunicorn --worker-tmp-dir /dev/shm myvoting.wsgi
1. HTTP Port: 8080

- URL:  
  seahorse-app-343h9.ondigitalocean.app
