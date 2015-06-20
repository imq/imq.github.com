imq.github.com
==============

This is the repository of the official website www.linuximq.net

The IMQ device has two common usage cases: 

•Ingress shaping: With linux only egress shaping is possible (except for the ingress queue which can only do rate limiting). IMQ enables you to use egress qdiscs for real ingress shaping.

•Shaping over multiple interfaces: Qdiscs get attached to devices. A consequence of this is that one qdisc can only handle traffic going to the interface it is attached to. Sometimes it is desireable to have global limits on multiple interfaces. With IMQ you can use iptables to specify which packets the qdiscs sees, so global limits can be placed.

For more information about what is IMQ visit https://github.com/imq/linuximq/wiki/WhatIs


