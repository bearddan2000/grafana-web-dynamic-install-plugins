# grafana-web-dynamic-install-plugins

## Description
A demo of loading plugins
dynamically at build time.

To plugins:
- Nav to http://localhost
- Login with `admin/admin`
- configuration -> plugins
  - Plugins marked as `signed` are new

## Tech stack
- grafana

## Docker stack
- grafana/grafana

## To run
`sudo ./install.sh -u`
- GRAFANA DASHBOARD http://localhost
  - Login with `admin/admin`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
