# Node
## Cook book for node app

**installed nginx web server on ubuntu/xenial64**

**Installed and upgraded the nodejs on the new chef instance**

**Created a proxy server to redirect the port:3000 to listen on port 80**

**ran unit tests for nginx: install,enabled, running**

**Unit test for nodejs: installed, version 6**

**Unit test for webserver: listening on port 80, bad gateway(502)**

	installation of nginx and nodejs canbe found inside 	
	Cookbook-node/node/recipes/default.rb

	Unit tests can be found inside 
	Cookbook-node/node/test/smoke/default/
	default_test.rb`

