# IP2GeoDatFile

Sometimes it is useful to translate IP addresses to Country. If you want to do that in python, there are 2 great resources for that:

1. Python library [pygeoip](https://github.com/appliedsec/pygeoip)
2. Dat file from [Miyuru](https://www.miyuru.lk/geoiplegacy)

```python
>>> import pygeoip
>>> gi = pygeoip.GeoIP('maxmind4country.dat')
>>> gi.country_name_by_addr('64.233.161.99')
'United States'
```

Hope this helps!
