Requirements
-------------

**Website e-shop**
Simple web site with back-end database running on a database server.

- connectivity requirements : 
 - management network only reachable by *netsys admins* (working within the organization) : webserver, database,
   - 172.16.1.0/24 through VPN or DirectConnect (DX), all *netsys admins* are using a bastion on 172.16.2.0/24
 - Users facing networks - *webserver*
   - reachable internally (172.16.100.0/24) within the company by *employee* through VPN or DirectConnect (DX), internal networks are within RC1918,
   - reachable externally for *customers* over Internet



