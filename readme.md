# nxg reverse proxy

1. In `nginx.conf`, change the ports on line 10 and 11 to match your local instance of nxg.

2. Then run: `docker-compose up`.

3.  (Optional) If you ever change the ports or want to make configuration settings, run `docker-compose build` then `docker-compose up`.
