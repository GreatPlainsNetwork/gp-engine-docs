# Great Plains Extended Network of GPUs for Interactive Experimenters (GP-ENGINE)

The [GP-ENGINE](https://gp-engine.org) project advances the adoption of advanced computing and data resources in the [Great Plains Network](https://www.greatplains.net/) region.

## Status

- [x] Gather requirements for nodes
- [x] Procurement Process
- [x] Receive Hardware
- [x] Pre-Install Hardware
    - [ ] Acquire site-specific configurations
- [ ] Send servers to final sites
- [ ] Site trainings

## Trainings

- University of Nebraska-Lincoln: January 18th, 2023

## Requirements for Deployment

The GP-ENGINE nodes are added to the [National Research Platforms's](https://nationalresearchplatform.org/) (NRP) Nautilus kubernetes.  The NRP has their own [requirements](https://docs.nationalresearchplatform.org/admindocs/participating/new-contributor-guide/) for nodes found on their documentation.  The requirements can be summarized as:

- Incoming and outgoing connections without firewalls.  The GP-Engine node should be in the site's [Science DMZ](https://fasterdata.es.net/science-dmz/).
- IPMI access to the node.  We can work with jump hosts, if necessary.  Otherwise, an ACL on a switch would be fine.
- [Jumbo packets](https://en.wikipedia.org/wiki/Jumbo_frame) enabled on the route to the WAN.
