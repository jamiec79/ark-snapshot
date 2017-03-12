# ark-snapshot
script to make snapshot for ark
#~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~#

ARK Blockchain Snapshot Script

by tharude a.k.a The Forging Penguin

11/03/2017 ARK Team

#~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~#

#~~~~~~~~~~~~~~~~~~~~ INSTRUCTIONS ~~~~~~~~~~~~~~~~~~~#

Edit crontab by typing "sudo nano /etc/crontab"

Put at the end of file the following line to make

the script creating snapshots every 15 minutes:

*/15 * * * * user /path/to/snapshot.sh

Replace the "user" with your username

and path at the end with your real script path.

Save the file with Ctrl+x and Y when you're done

#~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~#
