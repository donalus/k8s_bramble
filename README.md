# Yet another Raspberry Pi Kubernetes Cluster

Pi k8s brambles are everywhere. There seems to be just as many ansible scripts to set them up. This configuration works for me. If you take this work targeted at 

I really just wanted to play with ansible, kubernetes, and eventually terraform while justifying the stack of pis that seems to keep growing.

My goal was to have a  link to where I found the information, but I was probably lazy in many cases. It is reasonable to assume that if anything looks particularly clever that I found it somewhere else and don't deserve any credit.

## Ingredients

My cluster currently has one (1) controller and two (2) nodes. There is room in my [Zebra Bramble Cluster Case](https://www.c4labs.com/product/zebra-bramble-case-raspberry-pi-3-b-color-and-stack-options/) for one more RPi and at some point I'll get around to adding it.

This pi is made of:
    - three (3) [Raspberry Pi 4 4GB](https://www.adafruit.com/product/4296)
    - three (3) [Raspberry Pi PoE Hats](https://www.adafruit.com/product/3953)
    - one (1) TP-Link TL-SG105PE 5 Port Gigabit Managed PoE Switch
    - [Ubuntu 20.10 Server](https://ubuntu.com/download/server/arm)
    - kubernetes v1.20.5
    - [flannel v0.13.0](https://github.com/flannel-io/flannel)
    - [metallb v0.9.6](https://metallb.universe.tf/)

There are smarter people with better write-ups. I recommend searching for them.
