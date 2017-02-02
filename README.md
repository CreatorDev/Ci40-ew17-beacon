![logo](https://static.creatordev.io/logo-md-s.svg)

# Embedded World 2017 - beacon

## Overview

This script broadcasts url in eddystone-url format. Such broadcast can be observed by Android and iOS devices giving user notifications.

## Prerequisties

Following packages need to ba available on board
* bluez
* python3

## Running the script

Start advertisement

`python3 advertise-url.py --url <url-to-advertise>`

Stop advertisement

`python3 advertise-url.py --stop` 