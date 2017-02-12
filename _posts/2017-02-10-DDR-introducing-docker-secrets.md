---
layout: post
title: DDR - Introducing Docker Secrets
categories:
- blog
---

##### **What are Docker Secrets?**
Secrets manage any sensitive data which a container needs at runtime but you don’t want to store in the image or in source control, such as:

* Usernames and passwords
* TLS certificates and keys
* SSH keys
* Other important data such as the name of a database or internal server
* Generic strings or binary content (up to 500 kb in size)

##### **Note:**
* Available through Docker Swarm from Docker v1.13
* Available through Docker Compose from Docker Compose v1.11 (released 2 days ago)
* Not Available through non-swarm containers yet but PR being reviewed (https://github.com/docker/docker/pull/30637)

**Article Link:** <https://blog.docker.com/2017/02/docker-secrets-management/>  
**Docs:** <https://docs.docker.com/engine/swarm/secrets/>