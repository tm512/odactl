**odactl**

This is a simple launcher for odamex servers.

Just populate the cfgs/ directory with configuration files (see the included
skeleton.cfg). Put the names of any servers you want autostarted into 
servers.cfg, and then run `./odactl start` without arguments to start all of the
servers listed in servers.cfg. `./odactl stop` will stop all of them. You may 
also specify a specific server to start/stop by passing a 3rd argument, like 
`./odactl start dwango5`.

*Note, you will need to set the DOOMWADPATH environment variable, you can set it
inside of odactl's script, if you'd like to.*
