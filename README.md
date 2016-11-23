# ocp-php
PHP demo application for OpenShift Container Platform
Prints version number and IP of the Pod it runs on, perfect for demonstrating rolling upgrades with something like:

$ while true; do curl -s http://phpapp-ocp-fqdn.com|grep Version; sleep 1; done

