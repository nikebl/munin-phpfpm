# munin-phpfpm
Setup: 
	make sure that cgi-fcgi binary is exist in your system.
	move file to munin plugins dir, 
	run "munin-node-reconfigure --suggest --shell | grep phpfpm_" ,
	run the suggestions provided symlink creation command,
	reload munin-node.
