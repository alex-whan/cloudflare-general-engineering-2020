# Cloudflare Workers - General Software Engineering

## Version: 1.0.0

## [LIVE LINK](https://general-engineering.alex-whan.workers.dev/) | [JSON API CODE](https://new-json-api.whana.workers.dev/)

## Overview

A basic linktree-style website utilizing Cloudflare Workers to modify static HTML. This assignment consists of two parts: a JSON API providing links data and an HTML main page serving that data via Cloudflare Workers' HTMLRewriter API (see `"Deployed Applications"` links below).

## Author

-   [Alex Whan](https://github.com/alex-whan)

## Deployed Applications

-   [Deployed main site via Cloudflare Workers](https://general-engineering.alex-whan.workers.dev/)
-   [Deployed JSON API with links data](https://new-json-api.whana.workers.dev/)

## Using this application

This application responds to two requests, as follows:

-   `/`: Home route that serves the [HTML frontpage](https://general-engineering.alex-whan.workers.dev/) with dynamic link data from the JSON API. Please note that _any_ route aside from `/links` below will respond by serving this HTML page.

-   `/links`: Displays the raw link data in JSON format from the [JSON API](https://new-json-api.whana.workers.dev/) response.
