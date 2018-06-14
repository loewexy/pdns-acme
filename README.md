# PDNS Manager ACME

[PDNS Manager](https://pdnsmanager.lmitsystems.de) is a simple yet powerful free administration tool for the
Powerdns authoritative nameserver. It features an API for changing records.

This is a tool which uses PDNS Manager and [dehydrated](https://github.com/lukas2511/dehydrated)
with the dns-01 challenge to obtain TLS certificates. For an explanation on how to use it see the PDNS Manager [documentation](https://pdnsmanager.org/documentation/letsencrypt).

## Dependencies
In order to use this tool you must have the following programms installed.

* jq
* openssl
* curl

## Contribute
If you want a new feature or you found a bug, feel free to create a pull request or open a issue.
