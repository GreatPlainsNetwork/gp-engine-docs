# Great Plains Extended Network of GPUs for Interactive Experimenters (GP-ENGINE)

The [GP-ENGINE](https://gp-engine.org) project advances the adoption of advanced computing and data resources in the [Great Plains Network](https://www.greatplains.net/) region.

Additional information available at https://gp-engine.umsystem.edu/

## Status

- [x] Gather requirements for nodes
- [x] Procurement Process
- [x] [Receive Hardware](node-configuration.md)
- [x] Pre-Install Hardware
    - [x] Acquire site-specific configurations
- [x] Send servers to final sites
- [x] (Ongoing) Site trainings

## Trainings

Training materials are available on [Github](https://github.com/MUAMLL/gp-engine-tutorials)

- University of Nebraska-Lincoln: January 18th, 2024
- University of South Dakota: March 26-27, 2025

## Requirements for Deployment

The GP-ENGINE nodes are added to the [National Research Platforms's](https://nationalresearchplatform.org/) (NRP) Nautilus kubernetes.  The NRP has their own [requirements](https://nrp.ai/documentation/admindocs/participating/new-contributor-guide/) for nodes found on their documentation.  The requirements can be summarized as:

- Incoming and outgoing connections without firewalls.  The GP-Engine node should be in the site's [Science DMZ](https://fasterdata.es.net/science-dmz/).
- IPMI access to the node.  We can work with jump hosts, if necessary.  Otherwise, an ACL on a switch would be fine.
- [Jumbo packets](https://en.wikipedia.org/wiki/Jumbo_frame) enabled on the route to the WAN.
