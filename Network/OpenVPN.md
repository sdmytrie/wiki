:openvpn:nmcli:

# OpenVPN

## Add config

```
 nmcli connection import type openvpn file ./openvpn.ovpn
 
```

## Configure QOpenVPN

    cp openvpn.ovpn openvpn.conf

*   Edit `openvpn.conf` add `auth-user-pass auth`
*   Create file `auth` :

    <!---->
    
    username
    password
