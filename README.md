# Tunnel to SOCKS5

This script sets up a tunnel to route all networking to a SOCKS5 proxy. Unlike the solutions, which enable SOCKS5 proxy just for a selected app (bash, browser or apt), here the entire system networking gets forwarded to SOCKS5 proxy, including e.g. system services. Furthermore, both TCP and UDP protocols are supported, which enables many important features, such as DNS requests forwarding, system time synchronization and VoIP. From the user-side, it looks mostly like a VPN connection.

The solution is based on [badvpn-tun2sock](https://github.com/ambrop72/badvpn/blob/master/tun2socks/badvpn-tun2socks.8).

## Usage

Get a copy of [tun2sock](tun2sock), and adjust it for your needs.

