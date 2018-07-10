```
sudo cat /lib/systemd/system/consul.service

sudo cat /etc/consul/config.json

sudo systemctl stop consul.service

```

```
sudo /usr/local/bin/consul agent     -config-file=/etc/consul/config.json     -config-dir=/etc/consul/consul.d     -pid-file=/var/run/consul/consul.pid -log-level=trace
```

```

```