Python Server for Torque Pro
============================

This is a server that receives uploaded logging from the Android Torque Pro app
and then publishes it to an InfluxDB database.

Includes support for many Bolt (electric car) specific PIDs.

Influx Config
-------------
Sample configuration file:
Influx.conf
```
host=localhost
port=6543
user=torquepro
password=secretpassword
database=torquepro
```
