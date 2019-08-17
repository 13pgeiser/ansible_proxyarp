# ProxyARP

Bridge wired and wireless network using an ARP proxy.

See https://wiki.debian.org/BridgeNetworkConnectionsProxyArp

## Variables

To bridge wireless interface _wlp1s0_ with ethernet interface _enp1s0_

```
proxy_arp:
  wlan: wlp1s0
  interfaces:
    - enp1s0
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

