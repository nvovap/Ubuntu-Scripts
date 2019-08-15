# Ubuntu Demon Creator
An automated way of creating services/demons for ubuntu 16.04.


## Example
	create-demon.sh | sudo name="web" username="web" command="/home/web/start.sh" bash
### Logs
	/var/log/<name>.log
### Removal
	service uninstall <name>
## Parameters
* name: Name of the demon.
* username: The user the demon will run as.
* command: The command to run the demon.
* description (optional): The description of the demon.
