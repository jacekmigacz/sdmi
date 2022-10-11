systemd-mkosi-init

```
Usage: sdmi: [-i ghID|-i bzID]
```

```sh
iptables -A FORWARD -o eno1 -i ve-* -j ACCEPT
iptables -A FORWARD -i eno1 -o ve-* -j ACCEPT
iptables -t nat -A POSTROUTING -s 192.168.254.2/30 -o eno1 -j MASQUERADE

sysctl -w net.ipv4.ip_forward=1

setenforce 0
```
