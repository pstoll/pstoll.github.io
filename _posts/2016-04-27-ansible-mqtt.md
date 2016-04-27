---
layout:     post
title:      "MQTT and Ansible"
date:       2016-04-27 08:00:00 +04:00
keywords:   ansible, mqtt
---

## Ansible MQTT 

We are bringing some goodness to our infrastructure at work. So we're digging into [Ansible](http://docs.ansible.com/ansible/intro.html) for real.

We use [MQTT](http://mqtt.org) in our system to send messages around
from our drones. MQTT is an IoT messaging bus that is for realz. If
you needed any more proof, Amazon AWS offers [IOT as a
service](http://docs.aws.amazon.com/iot/latest/developerguide/what-is-aws-iot.html),
which is effectively MQTT as a service in the cloud.

Strangely, there doesn't seem to be a reasonable ansible playbook for
MQTT that I can ~steal~^H^H^H^H^Hget inspiration from, even on [Ansible
Galaxy](https://galaxy.ansible.com).

## Inspiration

As we learn more about ansible, we'll release it. There are some good
places to look for inspiration on how to write a reusable ansible,
e.g. [nginx role](https://github.com/geerlingguy/ansible-role-nginx)
and [ssl certs
role](https://github.com/jdauphant/ansible-role-ssl-certs).

here and here.

We'll release our MQTT 
Now don't get me wrong. We did look to be inspired by some other work
on ansible.  Ansible-spiration if you will. And man, this is a cool
source [Raspberry Pi Dramble](https://github.com/geerlingguy/raspberry-pi-dramble).


