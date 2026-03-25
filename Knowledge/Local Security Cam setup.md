10.1.1.160 is the saved backup for cam firmware

Change the following for IP address change -

check env (run "env")
(run "export LOCATION=???) to set location

cd /etc
sudo nano environment
(change to correct location)

run (sudo nano dhcpcd.conf) and set appropriate ip address

run "sudo raspi-config" to change wifi ssid
