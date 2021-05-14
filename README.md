Mara sov's bath water

## Download
#### Clone repo or run this command: 
```wget -q https://raw.githubusercontent.com/cloudex99/Destiny-2-Matchmaking-Firewall/main/d2firewall.sh -O ./d2firewall.sh```
## Usage
#### Setup: initial setup
``` sudo bash d2firewall.sh -a setup ```
#### Add: add a sniffed id to your firewall
``` sudo bash d2firewall.sh -a add ```
#### Remove: remove ids from the end of the list
``` sudo bash d2firewall.sh -a remove ```
#### Sniff: Auto sniffer. (You must add your 2 host consoles prior to running this)
``` sudo bash d2firewall.sh -a sniff ```
#### Open: Enables public matchmaking 
``` sudo bash d2firewall.sh -a open ```
#### Close: Disables public matchmaking
``` sudo bash d2firewall.sh -a close ```
#### List: List the current accounts
``` sudo bash d2firewall.sh -a list ```
#### Update: Update the script to the newest version.
``` sudo bash d2firewall.sh -a update ```
#### Load: Load the saved rules after a reboot
``` sudo bash d2firewall.sh -a load ```
#### Reset: Reset iptables to default
``` sudo bash d2firewall.sh -a reset ```
#### Credits to inchenzo & BasRaayman for coming up with the method.
