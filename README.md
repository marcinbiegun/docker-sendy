# Docker-Sendy

Docker-compose config for running [Sendy](https://sendy.co).

It contains:

* PHP + MySQL + NGNiX stack,

and a few adjustments requried by Sendy:

* URL rewrite rules as NGNiX config,
* additional PHP extensions,
* MySQL sql_mode without ONLY_FULL_GROUP_BY.

## Installation

If you need step-by-step instructions, read them on my blog: http://marcinbiegun.com/2017/01/15/sendy-docker/

## Kudos

Based on [mortezaPRK/docker-php](https://github.com/mortezaPRK/docker-php).
