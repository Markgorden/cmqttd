## Overview 

cmqttd is a massively scalable and clusterable MQTT V3.1/V3.1.1 broker written in ANSI C.

cmqttd is fully open source and licensed under the Apache Version 2.0. cmqttd implements both MQTT V3.1 and V3.1.1 protocol specifications, and supports WebSocket, STOMP, SockJS, CoAP and MQTT-SN at the same time.

cmqttd written in ANSI c, no especially requires.

## Cluster

Create the project that the goal is to cluster deployment. all service instances are stateless


## Goals

The cmqttd project is aimed to implement a scalable, distributed, extensible open-source MQTT broker for IoT, M2M and Mobile applications that hope to handle millions of concurrent MQTT clients.

* Easy to install
* Massively scalable
* Easy to extend
* Solid stable
* stateless
* cluster deployment

## Features(plan)

* Full MQTT V3.1/V3.1.1 protocol specification support
* QoS0, QoS1, QoS2 Publish and Subscribe
* Session Management and Offline Messages
* Retained Message
* Last Will Message
* TCP/SSL Connection
* MQTT Over WebSocket(SSL)
* HTTP Publish API
* MQTT-SN Protocol
* STOMP protocol
* STOMP over SockJS
* $SYS/# Topics
* ClientID Authentication
* IpAddress Authentication
* Username and Password Authentication
* Access control based on IpAddress, ClientID, Username
* Authentication with LDAP, Redis, MySQL, PostgreSQL and HTTP API
* Cluster brokers on several servers
* Bridge brokers locally or remotely
* mosquitto, RSMB bridge
* Extensible architecture with Hooks, Modules and Plugins
* Passed eclipse paho interoperability tests

## Modules

Coming here

## Dashboard

A Web Dashboard will be loaded when the emqttd broker started successfully.

The Dashboard helps monitor broker's running status, statistics and metrics of MQTT packets.

Default Address: http://localhost:18083

Default Login/Password: admin/public

## Design

![emqttd architecture](http://emqtt.io/static/img/architecture.png)

## QuickStart

Coming here

## Contributors

wait for you 


## Author

huamanlou(ZhangXuelian) <39514004@qq.com>

## License

Apache License Version 2.0

