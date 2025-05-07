# duckdns4docker
## A simple [DuckDNS](http://duckdns.org/) application on Docker

The compose file or .YAML deploys a working duckdns application.  

DuckDNS is a free service that points an IP of your choosing to a [duckdns.org](http://duckdns.org/) subdomain. To use this service, tou must first login into [duckdns.org](http://duckdns.org/), register a domain and retreive yout token.  

Once you have your token and your domain registered, you can edit the duckdns4docker.yaml file and replace this lines with your own token and subdomain (if you have more than one, sepparate them with a comma):  

https://github.com/cuenca125/duckdns4docker/blob/7f0ad1ae4cfeff0793b9792c50c2eed71b5d5f7e/duckdns4docker.yaml#L10-L11   

This YAML file can be run on docker with the following command: 
```
docker compose -f duckdns4docker.yaml up
```
> [!IMPORTANT]
> **(Make sure you are on the same directory as the duckdns4docker.yaml file before you run the command)**.  

<!-- With luv cuenca -->
