# DNS-Entries for internal zone ".ffnord"

## Zone ".ffnord"

The zone ".ffnord" is used as an internal DNS-zone by https://ffnord.net/

## Entries

This zone serves two DNS-records for:

1. our gateways and infrastructure (update-servers, NTP,...)
2. static clients 

Nodes in Freifunk Nord will be available in a sub-domain named "nodes.ffnord" soon.

## How to get your host into .ffnord

### Preferred 

Please [fork](https://help.github.com/articles/fork-a-repo/) this repository into your own github-Account.

Please "reserve" your adress at https://wiki.freifunk.net/Freifunk_Nord/IP-Bereiche#Reservierte_Adressen. 

Please enter your hostname at the end of the file. Please provide an IPv6-address from our pool (2a03:2267:4e6f:7264/64) and an IPv4-address (only if you'll have to serve legacy clients, please use 10.187.255/24).

Please increment the serial number of the zone. Please use our format: YYYYMMDDNN (year, month, day, number of edits at that date; Example: 2016051001)

Please generate a [pull request](https://help.github.com/articles/using-pull-requests/). 

Pull requests will be accepted after 2 gateway admins commented with "OK".

### Alternative

Just send an e-mail to admin (at) ffnord.net. Please include your desired hostname, the IPv6-address and an IPv4-address.
