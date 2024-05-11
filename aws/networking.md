
https://www.youtube.com/playlist?list=PL9nWRykSBSFhzwFa9Z5PqBM0XON8hpXE7

## VPC

https://www.youtube.com/watch?v=bGDMeD6kOz0&list=PL55RiY5tL51pgPovJKg6HFMFqiGNSZtQ5&index=8


## Subnet



## Security Group


## Internet gateway
Component that allows communications between the VPC & the internet. It also performs Network address translation()NAT for public instances.
one-to-one mapping with vpc. Not a physical device, so no cost.


## NAT Gateway
If some components of private subnet wants to communicate with public internet, It first goes to NAT gateway of the public subnet.
And then the NAT gateway goes to Internet gateway. Note that, it is only for outbound connection.
