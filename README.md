Woomm
====================

TLDR; Dockerize your apps in order to standardize different build and CI/CD environments.

Throughout my career, I have seen too many times the struggle standardizing developers' build environments. Be it, team members, using slightly different versions of libraries or frameworks or figuring out why builds work locally but fail in the CI pipeline.

> But it **Wo**rks **o**n **m**y **m**achine

The dreaded phrase, sometimes whispered in despair, sometimes shouted angrily through the engineering department's hallways. 

I have seen project teams setting up heavyweight developer VMs, which were shared over (then lightning-fast) USB 2.0 drives containing "all the right" tools with exactly all the right versions and configurations. Replacing everyone's (virtual) machine with the head developer's version every couple of weeks and forcing the team to live with the inefficiencies resulting from this practice.

I have seen developers arguing over one differences essential tool between different operating systems and venting their frustration during the team meetings.

### Dockerizing environments
_Woomm_ is a simple collection of dockerized CLI commands that help standardize your CLI environment between different execution environments.

_Woomm_ aims to remove the hurdle of different versions, operating systems, CPU architectures and configurations, in the end, improving developer satisfaction and productivity.


Commands
--------------------



Contribution
--------------------
Feel free to use this code wherever you like.

Contributions of new commands via Merge Request are highly appreciated


### Request new apps

If you want to request an app or a tool that is not part of this collection, feel free to request it via a ticket right here on Gitlab

