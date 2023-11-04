# python-web-cherrypy-api-dolt-pop

## Description
Simple web app that serves an api
for a cherrypy project.

Uses sqlalchemy query a table `pop`.

## Tech stack
- python
  - cherrypy
  - sqlalchemy
- dolthub/dolt-sql-serverdb

## Docker stack
- python:latest
- dolthub/dolt-sql-serverdb:latest

## To run
`sudo ./install.sh -u`
- [Endpoint at](http://localhost/)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
