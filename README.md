## Dependencies

* Ruby 2.6
* Rubygems
* Imagemagick, GhostScript, Poppler-Utils
* LibreOffice
* Webserver (Apache/Unicorn/Thin/Nginx)
* Rack interface to the webserver (Passenger, FastCGI)
* ActiveRecord-compatible database (Mysql, SQLite, Postgres)
* Nodejs as the javascript engine (as of version 2.4.0)

## Docker Image

To build and run the docker image locally, (make sure you don't already have port 80 in use):

```
1. git clone git@github.com:jatschudy/concerto.git
2. cd concerto
3. docker build -t concerto .
4. docker-compose up
```
