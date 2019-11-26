# check_certificate
--------------------------------------------------------------------------------

Simple 'SSL Certificate Expiration' check for Nagios / Icinga

Changelog
--------------------------------------------------------------------------------

[2019/11/26] - v1 - First Release

How to Use
--------------------------------------------------------------------------------

```sh

        usage:
        check_certificate -s <site> -w <warning> -c <critical>

        example:
        check_certificate -s google.com -w 30 -c 15
```

Output Format
--------------------------------------------------------------------------------

```sh

check_certificate -s google.com -w 30 -c 15
OK: Certificate Status from site google.com is OK. Expiration Date: Jan 28 07:46:16 2020 GMT

```
