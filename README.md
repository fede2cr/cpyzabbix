# cpyzabbix
Circuitpython implementation of a zabbix API library (pyzabbix)

This is mostly a fork of [pyzabbix](https://github.com/lukecyca/pyzabbix/tree/master).

Please take a look at examples/

Differences:
- It uses adafruit_requests instead of cpython requests so it had to be adjusted.
- It does not use a logger library. It's calls were replaced with prints which are commented on the code.
