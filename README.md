Creates a squid proxy box without access restrictions.  

```shell
vagrant plugin install vagrant-exec
vagrant exec "sudo tail -f /var/log/squid/access.log"
```
