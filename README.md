# doh.tiar.app

<p align="center">
	<a href="https://xkcd.com/624/"><img src="https://user-images.githubusercontent.com/787301/97881789-cccbbb80-1d5d-11eb-8c77-ed8b84a708c2.png"></a>
</p>

## Features

- [x] Filter: Ad, Ad-tracking and Malware (AdBlock).
- [x] DNS 0x20
- [x] DNSSEC Validation
- [x] No EDNS Client Subnet (ECS)
- [x] No logs
- [x] Free

## Table of Contents

* [Features](#features)
* [DNS](#features)
* [DNSCrypt](#dnscrypt)
* [DoH/DoH3 (DNS-over-HTTPS)](#dohdoh3-dns-over-https)
* [DoQ (DNS-over-QUIC)](#doq-dns-over-quic)
* [DoT (DNS-over-TLS)](#dot-dns-over-tls)


## DNS

### IPv4

~~~
 174.138.21.128 / 188.166.206.224 port 53 or port 5003
~~~

### IPv6

~~~
 [2400:6180:0:d0::5f6e:4001] port 53 or port 5003
~~~

## DNSCrypt

### IPv4

~~~
sdns://AQMAAAAAAAAAEzE3NC4xMzguMjkuMTc1OjE0NDMgAwQlHXHuBS3jFzDIgtQkjjhnDVSRDp1KT5rvzJC7Ne8YMi5kbnNjcnlwdC1jZXJ0LnRpYXIuYXBw
~~~

### IPv6

~~~
sdns://AQMAAAAAAAAAIFsyNDAwOjYxODA6MDpkMDo6NWY3Mzo0MDAxXToxNDQzIAMEJR1x7gUt4xcwyILUJI44Zw1UkQ6dSk-a78yQuzXvGDIuZG5zY3J5cHQtY2VydC50aWFyLmFwcA
~~~

## DoH/DoH3 (DNS-over-HTTPS)

~~~
https://doh.tiarap.org/dns-query (cached via Cloudflare.)
~~~

~~~
https://doh.tiar.app/dns-query
~~~

### IPv4 (doh.tiarap.org)

~~~
sdns://AgMAAAAAAAAADDEwNC4yMS42NS42MAAOZG9oLnRpYXJhcC5vcmcKL2Rucy1xdWVyeQ
~~~

### IPv4 (doh.tiar.app)

~~~
sdns://AgMAAAAAAAAADjE3NC4xMzguMjkuMTc1IEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffODGRvaC50aWFyLmFwcAovZG5zLXF1ZXJ5
~~~

### IPv6 (doh.tiarap.org)

~~~
sdns://AgMAAAAAAAAAG1syNjA2OjQ3MDA6MzAzNDo6NjgxNTo0MTNjXQAOZG9oLnRpYXJhcC5vcmcKL2Rucy1xdWVyeQ
~~~

### IPv6 (doh.tiar.app)

~~~
sdns://AgMAAAAAAAAAG1syNDAwOjYxODA6MDpkMDo6NWY3Mzo0MDAxXSA-GhoPbFPz6XpJLVcIS1uYBwWe4FerFQWHb9g_2j24OAxkb2gudGlhci5hcHAKL2Rucy1xdWVyeQ
~~~

## DoQ (DNS-over-QUIC)

~~~
quic://doh.tiar.app
~~~

port 784

~~~
sdns://BAMAAAAAAAAAEjE3NC4xMzguMjkuMTc1Ojc4NAAMZG9oLnRpYXIuYXBw
~~~

port 853

~~~
sdns://BAMAAAAAAAAAEjE3NC4xMzguMjkuMTc1Ojg1MwAMZG9oLnRpYXIuYXBw
~~~

## DoT (DNS-over-TLS)

~~~
dot.tiar.app
~~~

### IPv4

~~~
174.138.29.175 port 853
~~~
   
~~~
sdns://AwMAAAAAAAAADjE3NC4xMzguMjkuMTc1AAxkb3QudGlhci5hcHA
~~~

### IPv6

~~~
[2400:6180:0:d0::5f73:4001] port 853
~~~

~~~
sdns://AwMAAAAAAAAAG1syNDAwOjYxODA6MDpkMDo6NWY3Mzo0MDAxXQAMZG90LnRpYXIuYXBw
~~~

