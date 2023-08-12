# Raspberry Pi - Message Of The Day

Scripts to generate a pretty dynamic "message of the day" (motd) for your Raspberry Pi.

![dynamic motd](motd.png)

## Install

```
sudo cp 10-motd-berry /etc/update-motd.d/
```

```
sudo rm /etc/motd
sudo rm /etc/update-motd.d/10-uname
```