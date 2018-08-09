# HTTPD Docker #

## Objective ##

Provide docker image with apache's httpd server and a volume to work with the code.

## Usage ##

In you terminal, run:

```bash
docker run -d -v /your/application/path:/usr/local/apache2/htdocs/ -p <Your Port>:80 lrabbt/httpd
```