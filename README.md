# doh.tiar.app

<p align="center">
	<a href="https://xkcd.com/624/"><img src="https://user-images.githubusercontent.com/787301/97881789-cccbbb80-1d5d-11eb-8c77-ed8b84a708c2.png"></a>
</p>

## Features

- [x] Filter: Ad, Ad-tracking and Malware (AdBlock)
- [x] DNS 0x20
- [x] DNSSEC Validation
- [x] No EDNS Client Subnet (ECS)
- [x] No logs
- [x] Free

## Table of Contents

* [Features](#features)
* [DNS](#features)
* [DNSCrypt](#dnscrypt)
* [DoH (DNS-over-HTTPS)](#doh-dns-over-https)
* [DoQ (DNS-over-QUIC)](#doq-dns-over-quic)
* [DoT (DNS-over-TLS)](#dot-dns-over-tls)
* [DNS Over Telegram](#dns-over-telegram)


## DNS

### IPv4

 `174.138.21.128 port 53 or port 5003`

### IPv6

 `[2400:6180:0:d0::5f6e:4001] port 53 or port 5003`

## DNSCrypt

### IPv4: 

~~~
sdns://AQMAAAAAAAAADjE3NC4xMzguMjEuMTI4IO-WgGbo2ZTwZdg-3dMa7u31bYZXRj5KykfN1_6Xw9T2HDIuZG5zY3J5cHQtY2VydC5kbnMudGlhci5hcHA
~~~

### IPv6:

~~~
sdns://AQMAAAAAAAAAG1syNDAwOjYxODA6MDpkMDo6NWY2ZTo0MDAxXSDvloBm6NmU8GXYPt3TGu7t9W2GV0Y-SspHzdf-l8PU9hwyLmRuc2NyeXB0LWNlcnQuZG5zLnRpYXIuYXBw
~~~

## DoH (DNS-over-HTTPS)

`https://doh.tiarap.org/dns-query` `(cached via Cloudflare.)`

`https://doh.tiar.app/dns-query`


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

quic://doh.tiar.app

~~~
sdns://BAMAAAAAAAAAEjE3NC4xMzguMjkuMTc1Ojc4NAAMZG9oLnRpYXIuYXBw
~~~


## DoT (DNS-over-TLS)

* `dot.tiar.app or doh.tiar.app port 853`
   
* `IPv4: 174.138.29.175 port 853`
   
   ~~~
   sdns://AwMAAAAAAAAADjE3NC4xMzguMjkuMTc1AAxkb3QudGlhci5hcHA
   ~~~

* `IPv6: [2400:6180:0:d0::5f73:4001] port 853`

   ~~~
   sdns://AwMAAAAAAAAAG1syNDAwOjYxODA6MDpkMDo6NWY3Mzo0MDAxXQAMZG90LnRpYXIuYXBw
   ~~~



## [DNS Over Telegram](https://t.me/dns_tgbot)


### Bot

![Screen Shot 2020-09-14 at 2 59 40 PM](https://user-images.githubusercontent.com/787301/93053879-0ad02b80-f69b-11ea-9199-b7551568373c.png)

### Help

![Screen Shot 2020-09-14 at 2 52 30 PM](https://user-images.githubusercontent.com/787301/93053134-f50e3680-f699-11ea-9907-8f7691799f12.png)

### Query Domain

![Screen Shot 2020-09-14 at 2 55 49 PM](https://user-images.githubusercontent.com/787301/93053472-6cdc6100-f69a-11ea-8003-af96ffeee258.png)

### Answer Domain

![Screen Shot 2020-09-14 at 2 56 02 PM](https://user-images.githubusercontent.com/787301/93053504-78c82300-f69a-11ea-97ee-47a5d0122b31.png)

### Reverse DNS lookup

![Screen Shot 2020-09-14 at 3 06 16 PM](https://user-images.githubusercontent.com/787301/93054531-0c4e2380-f69c-11ea-93aa-74e7b5b1242c.png)

### Answer for Reverse DNS lookup

![Screen Shot 2020-09-14 at 3 06 29 PM](https://user-images.githubusercontent.com/787301/93054579-1b34d600-f69c-11ea-8a13-47ba5375c54d.png)


