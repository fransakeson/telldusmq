# Dockerfile for telldusmq

Dockerfile for containerising the telldus daemon and telldusmq MQTT client.


The default [tellstick.conf](tellstick.conf) and [telldusmq.json](telldusmq.json) supplied here needs to be modified for your setup.

Refer to [telldus](https://github.com/telldus/telldus) regarding the daemon, and [telldusmq](https://github.com/hnesland/telldusmq) regarding the MQTT client.

The container image, built for the Raspberry Pi armhf ABI, is available on
[Docker Hub](https://hub.docker.com/r/fransakeson/telldusmq/)
