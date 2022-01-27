# cool_commands
Commands that make my life easier

Credit: 
* https://missing.csail.mit.edu/about/

## Python
Kill open python processes
```pkill -f python --all```

## Transferring files
Syncs files in from here there, copies only differences from here to there not everything like scp.
```rsync -ah --info=progress2 /copy/from/here /copy/to/there```

Copies files in parallel 
```fpsync --verbose /from/local/folder /to/storage/device```

## Computing
Fix time sync errors across different computers ```ntpdata -q <ip address>```

## Git

## Data Wrangling

## Everyday
Unzip a tar.gz and extract to a specified directory: ```sudo tar xvf <filename>.tar.gz -C <destination>```

Find IPs on a local network ```arp -a```

Make sure all files have been transferred to storage before unmounting using command ```sync```
