This is the [docker compose](https://docs.docker.com/compose/) setup to run a plain [OntoWiki](http://ontowiki.net/).

The compose setup uses:
- Virtuoso Open Source `tenforce/virtuoso:1.1.0-virtuoso7.2.4`
- PHP 5.6 FPM with ODBC extension and linking to Virtuoso `aksw/php-5.6-fpm-odbc-virtuoso`
- NGINX configured for OntoWiki `aksw/nginx-ontowiki` (based on the official `php`)
- and a container with the OntoWiki Source Code `aksw/ontowiki`

For using it you have to install [docker](https://www.docker.com/community-edition) and [docker compose](https://docs.docker.com/compose/install/).
