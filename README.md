# Add-Trackers

Add Public trackers to Transmission Daemon    
I have modified the original script and I cant remember the source. Most of the functionality and the single version was added by me.


These are 2 simple bash script to add additional public trackers to Transmission Daemon.

insert-trackers-single    
Add all trackers to a SINGLE torrent in queue.
You will be presented with a list of all torrents in queue and press the number of the torrent
and the trackers will be automatically added.

insert-trackers    
Add all trackers to ALL torrents in queue.
Just simply run this script and all trackers will be added to ALL torrents in queue

To run either put the script in your path or run manually

Add your transmission username and password to each file.    
Example:    
auth=username:password    
host=localhost


make the script executable    
chmod +x insert-trackers   
chmod +x insert-trackers-single    

Run the file manually    
./insert-trackers-single    
