# vipctl
## Summary
* VIPCTL helps to apply and remove the server loopback IP address to the server network easy
* And you can control the VIP Group of the LoadBalancer in the Client via VIPCTL by health check control

## Demo
[![asciicast](https://asciinema.org/a/f2sauf1embqkkwybnwny23hcf.png)](https://asciinema.org/a/f2sauf1embqkkwybnwny23hcf)

## Download & install 
```
curl -sL bit.do/vipctl -o ~/vipctl     
chmod 755 ~/vipctl                     
sudo cp ~/vipctl /etc/init.d/vipctl
```

## How to use
* You can change that configuration in that file before below command
```
service vipctl start
```
