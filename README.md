# GATE

this is the gate that holds our monorepo for the server

## Dependencies
* Caddy server

## Development Run and Setup

### Setup
in `Caddyfile` comment the line `css.uwindsor.ca` at the start
uncomment the line `localhost`

### Run

run `hub` at port `5000` on localhost

run `wiki` at port `3000` on localhost

run `sudo caddy start`

## Production Run and Setup

### Setup
there is none

### Run

run `hub` at port `5000` on localhost

run `wiki` at port `3000` on localhost

run `sudo caddy start`

## Todo

* Talk to CSIT about exposing port 80 and 443

* Docker and Docker compose
