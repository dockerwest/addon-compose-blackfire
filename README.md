blackfire docker compose
========================

Addon for your docker compose environment to support blackfire profiling of
your PHP applications.

Environment variables
=====================

To allow profiling you will have to add the following environment variables to
your `.env` file:

- BLACKFIRE_SERVER_ID
- BLACKFIRE_SERVER_TOKEN
- BLACKFIRE_CLIENT_ID
- BLACKFIRE_CLIENT_TOKEN

You can find the values for these environment variables at the [BlackFire website](https://blackfire.io/docs/integrations/docker#documentation)

License
-------

MIT License (MIT). See [License File](LICENSE.md) for more information.
