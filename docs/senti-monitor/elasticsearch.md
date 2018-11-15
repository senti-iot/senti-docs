Data:    /usr/local/var/lib/elasticsearch/elasticsearch_cb/
Logs:    /usr/local/var/log/elasticsearch/elasticsearch_cb.log
Plugins: /usr/local/var/elasticsearch/plugins/
Config:  /usr/local/etc/elasticsearch/

To have launchd start elasticsearch now and restart at login:
  $ brew services start elasticsearch

Or, if you don't want/need a background service you can just run:
  $ elasticsearch