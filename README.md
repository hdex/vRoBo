vRoBo
=====

WebApp to perform basic remote management on remote virtualisation Hosts

Scope
-----
vSphere hosts (possibly Hyper-V later).
Goal is to provide basic remote management (Host/VM Usage, remote console) without the need for proprietary and expensive solutions.
Other OSS management can be used but tend to cover more than basic needs with added complexity (databases, management packs etc ...)
vRoBo is only a set of scripts gathering information and presenting it in an nice and simple web interface.

Why
---
vCenter and SCVMM are great tools but do require extra licensing.
Why should you need a full license if the only thing you have at a remote site is a single server (meaning no need for more than 32GB, vMotion, DRS, HA etc) and the need to check how things are running.
Why should you need to run Nagios or ZenOSS (both great tools) if you only want basic monitoring and don't need the extra complexity in managing full blown management platforms.

