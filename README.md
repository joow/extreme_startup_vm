# Extreme Startup VM

1. Add the box
	$ vagrant box add extreme extreme-startup-vm.box

2. Create a directory :
	$ mkdir extreme

3. Change current directory to extreme one :
	$ cd extreme

4. Initialize the box :
	$ vagrant init extreme

5. Start the box :
	$ vagrant up

6. SSH into the box :
	$ vagrant ssh

7. Change current directory to extreme_startup directory :
	$ cd extreme_startup

8. Start the server in WARMUP mode (accessible through http://host:8080) :
	$ WARMUP=1 ruby web_server.rb

9. Let the participants register.

10. Close the server (CTRL+C) and launch it :
	$ ruby web_server.rb

11. Use the control panel to control the game :
	$ http://host:8080/controlpanel

12. Enjoy !