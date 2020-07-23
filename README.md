# Simple DNS Server

This is a simple way to get a dns server up and running using [docker compose](https://docs.docker.com/compose/) and [Coredns](https://coredns.io). Feel free to fork this to you hearts desire, i'm putting this up as an example for my future self and other folks wanting to use core dns on docker.

You can add to the hosts file to specficy dns entries, this is an easy way to specify domain names for things in your local network. More details [here](https://coredns.io/plugins/hosts/). You can get way more complicated by making use of the various [plugins](https://coredns.io/plugins/) coredns offers. Want to learn more about coredns overall, go [here](https://coredns.io/manual/toc/#configuration)


## Running the dns server

Once you have configured this how you like, clone this repo to the machine you want to run it on, make sure that machine has docker installed then run `docker-compose up -d` and you should be good to go.