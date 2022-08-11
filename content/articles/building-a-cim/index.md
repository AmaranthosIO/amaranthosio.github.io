+++
title = "Building a Composable Information Machine"
description = "A distributed knowledge encapsulation system based on Functional Reactive Programming and Event Sourcing"
date = 2022-08-03
weight = 0
draft = false
in_search_index = true
# Template to use to render this page.
template = "md-page.html"

[taxonomies]
  tags = ["cim", "composable", "act", "game theory", "devops"]
  people = ["steele"]

[extra]
   image = "limits-and-boundaries.webp"
   chapters = "/articles/building-a-cim/chapters.json"
+++

## Building a Composable Information Machine

This is the outline we will follow:

   1. ## Definition and Design
      * Structure - [Type System](https://typedefs.com)
      * Mapping and flow - [n8n](https://n8n.io)
      * documentation - [NetBox](https://docs.netbox.dev/en/stable/) and [git](https://git-scm.com)
      * Content-Addressing - [IPLD](https://ipld.io)
   2. ## Software Defined Network
      * [relationships](/library/conceptual-spaces) of compute resources
      * [IPAM](https://www.infoblox.com/glossary/ipam-ip-address-management/), [VLAN](https://www.guru99.com/vlan-definition-types-advantages.html), [DNS](https://www.cloudflare.com/learning/dns/what-is-dns/), [DHCP](https://www.lifewire.com/what-is-dhcp-2625848), [VPN](https://www.cisco.com/c/en/us/products/security/vpn-endpoint-security-clients/what-is-vpn.html)
      * Inventory - [NetBox](https://docs.netbox.dev/en/stable/)
   3. ## Power
      * Sources and capabilities
         * Solar
         * Wind
         * Generator
         * Grid
   4. ## Computing Devices
      * Hardware and identification
      * Virtual network endpoints  
   5. ## Definition of components
      * [What makes up a device](https://docs.netbox.dev/en/stable/core-functionality/device-types/)
      * Setting [limits](/library/limits) and [boundaries](/library/boundaries) for spaces
      * Continuous integration and deployment
   6. ## Secure communication
      * Private, queued, bus channel between nodes
      * Command and control separation (different private channels)
      * [Identity and Access Management](https://webofidentity.com/blog/self-sovereign-digital-identity/)
      * [FRP](http://neilsculthorpe.com/publications/safe-efficient-FRP.pdf)
   7. ## Persistance
      * [System of Record](/library/sor) binding multiple [Sources of Truth](/library/sot)
      * [Command, Query, Response Segregation](https://www.geeksforgeeks.org/what-is-cqrs/) + [Event Sourcing](/library/event-sourcing.md)  
      * Content-Addressing [IPFS](https://ipfs.io)  
      * addressable blocks [IPLD](https://ipld.io)
   8. ## Proofs
      * Proofs of operations
        * [How does it work](https://typedefs.com/)
      * monitoring
        * [Show me that it works](https://checkmk.com/)
      * causality
        * [What made it do that](https://www.amazon.com/Book-Why-Science-Cause-Effect/dp/046509760X)
      * game theory
        * [What if it does this](https://arxiv.org/abs/1711.07059v2)
