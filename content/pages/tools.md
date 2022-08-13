+++
title = "Tooling"
path = "tools"
template = "empty.html"
+++
Everything we use here is [Open Source](https://opensource.com/resources/what-open-source), 
we have specific places where each of these fit into a [Composable Information Machine](/library/cim).

To obtain the things we want requires resources, and the process of transforming what we have into what we want
is often an intricate one.

## Consider the following three questions you might ask yourself:

  * **Given what I have:**
    * Is it possible to get what I want?
    * What is the cost to get what I want?
    * What is the set of ways to get what I want?

We have a formalism for expressing recipes—methods for transforming one set of resources into another—and for deriving new recipes from old. These fill a role or ingredient in the recipe and are often replaceable.

  * [Event Store](https://eventstore.com/)
    An Event Store acts as the [System of Record](/library/sor)  
  * [NetBox](https://docs.netbox.dev/en/stable/)
    [Source of Truth](/library/sot) for [infrastructure](/library/irm) 
  * [n8n](https://n8n.io/)
    Automation tool to model and create the arrows 
  * [searX](https://searx.thegpm.org/)
    Search everything locally and remotely securely and privately
  * [checkmk](https://checkmk.com/)
    Monitor all the things
  * [Rust](https://rust-lang.org)
    Our preferred development language
  * [Docker](https://docker.com)
    Containerization in general is more accurate, we use [Virtual Machines](https://www.linux-kvm.org/page/Main_Page), [Kubernetes](https://kubernetes.io/) and [LXC](https://linuxcontainers.org/) too.
  * [IPLD](https://ipld.io)
    Inter Planetary Linked Data - Defining Content Structure
  * [IPFS](https://ipfs.io)
    Inter Planetary File System - [Content-Addressing](/library/content-addressing)
  * [git](https://git-scm.com)
    Distributed Version Control
  * [Decentralized Identifiers](https://www.w3.org/TR/did-core/)
    A new type of identifier that is globally unique, resolvable with high availability, and cryptographically verifiable. DIDs are typically associated with cryptographic material, such as public keys, and service endpoints, for establishing secure communication channels. - [DID Primer](https://w3c-ccg.github.io/did-primer/)
  * [Self Sovereign Identity](https://101blockchains.com/self-sovereign-identity/)
    A self-sovereign identity literally translates into an identity that is under your ownership. However, one could reasonably ask about the need for identity like SSI when you have your national ID card, gym membership card, and student ID in your pockets. This is where you need to consider the pitfalls associated with physical and digital IDs used commonly today.
  * [OpenAPI Generator](https://openapi-generator.tech/)
    Generate clients, servers, and documentation from OpenAPI 2.0/3.x documents
  * [VSCode](https://code.visualstudio.com/)
    Code editor with good features for development. Free. Built on open source. Runs everywhere.
  * [Typedefs](https://typedefs.com)
    Typedefs is a programming language agnostic, algebraic data type definition language
  * [Gherkin](https://www.guru99.com/gherkin-test-cucumber.html)
    [Reference Language](https://cucumber.io/docs/gherkin/reference/) for creating acceptance tests.
  * [Zola](https://getzola.org)
    [Rust](https://rust-lang.org) based single executable with Sass compilation, syntax highlighting, table of contents for websites.
  * [Jupyter](https://jupyter.org/)
    Creating and sharing computational documents. It offers a simple, streamlined, document-centric experience.
  * [Ubiquiti](https://store.ui.com/collections/unifi-network-unifi-os-consoles)
    [Consoles](https://ui.com/consoles) for network access
  * [StarLink](https://starlink.com)
    High-speed, low-latency broadband internet in remote and rural locations across the globe.

To build the [Composable Information Machine](/library/cim) we assemble and 
configure these tools in a specific way and they serve a specific purpose 
Each element of a [cim](/library/cim), there is a [repository](https://git-scm.com/docs/git) and [development
environment](/library/devcontainer) created to work speficifically with this ecosystem.
