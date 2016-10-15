emq_auth_username
=================

Authentication with Username and Password

Build
-----

```
make && make tests
```

Configuration
-------------

etc/emq_auth_username.conf:

```
auth.username.$name=$password
```

Load the Plugin
---------------

```
./bin/emqttd_ctl plugins load emq_auth_username
```

License
-------

Apache License Version 2.0

Author
------

feng at emqtt.io

