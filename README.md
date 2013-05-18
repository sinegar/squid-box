Creates a squid proxy box without access restrictions.  

vagrant plugin install vagrant-exec
vagrant exec "sudo tail -f /var/log/squid/access.log"
