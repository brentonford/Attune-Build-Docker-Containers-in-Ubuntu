Stop systemd-resolve from listening on port 53. 

One of the changes Ubuntu 20.04 LTS is systemd-resolve is configured to listen on port 53. Pi-hole won't start with systemd-resolve listening to port 53.