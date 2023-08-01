# Great Plains Extended Network of GPUs for Interactive Experimenters (GP-ENGINE)

The GP-ENGINE project advances the adoption of advanced computing and data resources in the [Great Plains Network](https://www.greatplains.net/) region.

## Status

- [x] Gather requirements for nodes
- [x] Procurement Process
- [ ] Receive Hardware
- [ ] Pre-Install Hardware
    - [ ] Acquire site-specific configurations
- [ ] Send servers to final sites

## Requirements for Deployment

- Incoming and outgoing connections without firewalls.  The GP-Engine node should be in the site's [Science DMZ](https://fasterdata.es.net/science-dmz/).
- IPMI access to the node.  We can work with jump hosts, if necessary.  Otherwise, an ACL on a switch would be fine.
- [Jumbo packets](https://en.wikipedia.org/wiki/Jumbo_frame) enabled on the route to the WAN.
