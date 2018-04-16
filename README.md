# rac-heat-templates
Heat Templates for RAC

https://docs.openstack.org/heat/latest/

After launching heat stack, wait for `bootstrap.sh` to complete. Login to instance and run `watch -n 5 "ps aux | grep bootstrap"`.

## Guacamole
Access web app at http://<span></span>[ipv6]:8080/guacamole

## Etherpad
* Manually associate floating ipv4 to instance.
* Access webapp at http://<span></span>ipv4:80

## Jupyter Notebook
* Access webapp at https://<span></span>[dns_name].yyc.cybera.ca:8888
* Log process output in /var/log/jupyter.log
### References
* https://github.com/squillace/staging/blob/master/articles/virtual-machines/virtual-machines-linux-jupyter-notebook.md
* [Jupyter config settings](http://jupyter-notebook.readthedocs.io/en/latest/public_server.html)
