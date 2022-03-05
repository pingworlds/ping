# ping


- [Chinese](README.md)
- [English](readme_en.md)



ping is an android web proxy client that supports the pong proxy protocol.
It is also compatible with vless,socks5,shadowsocks,qsocks proxy protocol.

ping uses [pong-go](https://github.com/pingworlds/pong) as the core network library.


Note: ping is a proxy tool and does not provide any nodes itself.


## Current version v1.0.0


Download link.


 <https://github.com/pingworlds/ping//releases/latest/download/ping.apk>


 
## transport protocols

The following transport protocols are supported.

- http2
- h2c
- http3
- ws
- wss
- https
- http
- tcp
- tls


## proxy protocols

pong supports the following proxy protocols.
- pong
  
  Recommended Preferred

- shadowsokcs 

    Only plaintext is supported

- vless

    Plaintext only

- socks5
    
    No authentication support

- qsocks 

A lite version of socks5 without handshake process 


Note: All proxy protocols, only plaintext is supported



## Settings

 
Try to keep the default settings, relatively stable 
 
  
### Suggestions for setting options 
 
- Traffic takeover mode 
  
    Recommended per-app proxy, global mode is still unstable.

- Doh service 

    Be careful to open, doh service is sensitive to network environment

          
- auto-try 
 
    It is recommended to turn on, auto-try means auto-proxy in case of direct connection failure, theoretically it can be used without blacklist. 

-Block mode 

    Recommended to turn on, advertising rarely misses

          
- rule set 
 
    Domain and IP rules are managed by blacklist, whitelist and block list respectively
 
- pass mode 
 
    Blacklist mode is recommended for domain names. ip whitelist mode
