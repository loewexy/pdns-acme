# PDNS Util ACME

This is a hook script for dehydrated to use PDNS Util
with the dns-01 challenge to obtain TLS certificates.

## Dependencies
In order to use this tool you must have the following programms installed.

* jq
* pdnsutil (included in *pdns-tools*)

## Contribute
If you want a new feature or you found a bug, feel free to create a pull request or open a issue.

## Example
```
dehydrated -c --challenge dns-01 --domain www.example.com --hook ./pdns-acme
```
