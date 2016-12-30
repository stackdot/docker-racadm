# racadm cli tool

This docker file allows you to run `racadm` commands via docker ( any OS ).

Example usage:

		docker run stackdot/racadm -u root -p root -r 192.168.1.10 racdump

---

The entrypoint is racadm so there is no need to prepend that to your commands.