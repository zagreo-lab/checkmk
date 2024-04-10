# checkmk

You can now for the first time log in and try Checkmk out. You will find the provisional password for the cmkadmin account in the logs that are written for this container (the output is abbreviated to the essential information here in this example):

root@linux# docker container logs monitoring
Created new site cmk with version 2.2.0p1.cre.

  The site can be started with omd start cmk.
  The default web UI is available at http://73a86e310b60/cmk/

  The admin user for the web applications is cmkadmin with password: 2JLysBmv
  For command line administration of the site, log in with 'omd su cmk'.
  After logging in, you can change the password for cmkadmin with 'cmk-passwd cmkadmin'.

# Backup
Il backup target è: 
  
Directory to save the backup to: 	/opt/omd/sites/cmk/backup

Mountpoint: 	off
