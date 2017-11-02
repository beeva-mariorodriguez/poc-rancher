# Rancher 2.0alpha

Rancher is a complete container management platform, its current version is able to manage different container platforms (Mesos, kubernetes, docker swarm, cattle), but for version 2.0 RancherLabs decided to reengineer Rancher as a kubernetes management platform.

the tech preview for Rancher 2.0 was published in september 2017

goals: evaluate the new Rancher, keeping in mind it's an alpha version

[Rancher 2.0 Tecnhical architecture](doc/Rancher_2.0_Technical_Architecture-Sept_2017.pdf)

## tasks
* deploy Rancher HA => HA currently not working in Rancher 2.0 (last tested with alpha8)
* add existing kubernetes clusters => OK
* create new kubernetes clusters using rancher's embedded master => OK

