#

## turn off green light 
- put into /etc/profile

```
echo sleep > /sys/class/leds/green/trigger

```

```
root@radxa_rock_pro:/ # ls /sys/class/leds
(null)
blue
cvbs
green
red

```


