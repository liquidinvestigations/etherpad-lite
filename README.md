# etherpad-lite

[![Build Status](https://jenkins.liquiddemo.org/api/badges/liquidinvestigations/etherpad-lite/status.svg)](https://jenkins.liquiddemo.org/liquidinvestigations/etherpad-lite)

Settings and Dockerfile for building a custom etherpad, tracking the `develop` branch.


Run this with:

        docker run \
            --env PORT=1234 \
            --env TITLE=something \
            --env POSTGRES_DB=eth \
            --env POSTGRES_USER=user \
            --env POSTGRES_HOST=host \
            --env POSTGRES_PORT=3306 \
            --env POSTGRES_PASSWORD=X \
            --env POSTGRES_DATABASE=Y \
            liquidinvestigations/etherpad-lite

