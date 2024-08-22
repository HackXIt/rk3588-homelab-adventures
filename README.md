# rk3588-homelab-adventures

My personal adventures with the turing pi rk1 with individual projects placed in submodules.

This repository serves as a high-level overview of the projects I am working on with the RK3588. Further information and notes about a project can be found in the README files of the corresponding submodules.

It is also my point of reference for anything found online that I might want to revisit later. _The README files of the individual projects only contain directly relevant links to resources used in the project._

# Quest pool

These are the individual projects that I think about doing with the RK3588. I will be updating this list as I go along.

Once a project has been started it will be checked off here and a link to the corresponding submodule will be added.
**A checked off item in this list does not mean it is complete, check out the submodule for more information.**

_The list is in no particular order, allthough I try to keep it somewhat organized/coherent._

- [ ] Setup a custom dietpi image for the RK3588
- [ ] Test out the RK3588 open-source NPU driver on a single node
- [ ] Setup automation for image building and deployment for the RK3588
- [ ] Getting the RK3588 open-source NPU driver working on all nodes
- [ ] Running a ML model (YOLOv8 or later) on RK3588 open-source driver (or at least getting it running)
- [ ] Setting up a cluster with the turing pi 2 (preferably using docker swarm CE)
- [ ] Running a distributed ML model on the RK3588 cluster
- [ ] Setup stable diffusion with web on the RK3588 cluster
- [ ] Setup a CI/CD pipeline for the RK3588 cluster

# Completed adventures

_Someday there might be success visible here, but as of right now there isn't much to be seen._

# References

The following is a list of references that I have found and collected. I try to keep it somewhat categorized to the topics that I am working on.

## Reference-of-references

- [Useful information & development links (reddit)](https://www.reddit.com/r/RockchipNPU/comments/1butgqh/useful_information_development_links/)

## Custom DietPi image

- [DietPi Image Request for RK1 (also with user guide)](https://dietpi.com/forum/t/new-turingpi-rk1/19142/7)

## Open-source RK3588 NPU driver

- [Author's Blog on rockchip NPU kernel driver](https://blog.tomeuvizoso.net/2024/06/rockchip-npu-update-4-kernel-driver-for.html)
- [Review process of NPU kernel driver (Mailing list)](https://lore.kernel.org/all/20240612-6-10-rocket-v1-0-060e48eea250@tomeuvizoso.net/#r)
- [Pull Request of NPU kernel driver](https://gitlab.freedesktop.org/mesa/mesa/-/merge_requests/29698)

## NPU

- [RK3588 reverse engineering RKNN](https://jas-hacks.blogspot.com/2024/02/rk3588-reverse-engineering-rknn.html)

## Machine learning

- [RKNN-Toolkit2 (GitHub)](https://github.com/airockchip/rknn-toolkit2)
- [airockchip - RKNN LLM (GitHub)](https://github.com/airockchip/rknn-llm)
- [Rockchip RK3588 performance with llama.cpp (GitHub issue)](https://github.com/ggerganov/llama.cpp/issues/722)

### Distributed ML

...

### YOLO

...

### Stable diffusion

- [RK3588 stable diffusion GPU](https://github.com/happyme531/RK3588-stable-diffusion-GPU)

## Cluster automation and orchestration

- [Jeff Geerling's SBC review of RK1](https://github.com/geerlingguy/sbc-reviews/issues/38)
- [Jeff Geerling's Turing Pi Blog](https://www.jeffgeerling.com/tags/turing-pi)