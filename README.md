[![Source Repo](https://img.shields.io/badge/fork%20on-gitlab-important?logo=gitlab)](https://gitlab.com/systemkern/works-on-my-machine)
[![Gitlab Pipelines](https://gitlab.com/systemkern/works-on-my-machine/badges/master/pipeline.svg)](https://gitlab.com/systemkern/works-on-my-machine/-/pipelines)
[![Twitter @systemkern](https://img.shields.io/badge/follow-%40systemkern-blue?logo=twitter)](https://twitter.com/systemkern)
[![LinkedIn @systemkern](https://img.shields.io/badge/contact%20me-%40systemkern-blue?logo=linkedin)](https://linkedin.com/in/systemkern)


<div align="center">
![Works on My Machine Logo](public/works-on-my-machine-logo.png)
</div>

Works on my machine
=============================


**TLDR;** Dockerize your apps in order to standardize different build and CI/CD environments.

Throughout my career, I have seen too many times the struggle standardizing developers' build environments. 
Be it, team members, using slightly different versions of libraries or frameworks or figuring out why builds work locally but fail in the CI pipeline.

> But it Works on my machine  `¯\_(ツ)_/¯`

The dreaded phrase, sometimes whispered in despair, sometimes shouted angrily through the engineering department's hallways. 

I have seen project teams setting up 100 Gigabyte heavyweight developer VMs, which were shared over (then lightning-fast) USB 2.0 drives containing "all the right" tools with exactly all the right versions and configurations.
Replacing everyone's (virtual) machine with the head developer's version every couple of weeks and forcing the team to live with the inefficiencies resulting from this practice.

I have seen developers arguing over one differences essential tool between different operating systems and venting their frustration during the team meetings.

### Dockerizing environments
The _Works on my machine_ repo is a collection of dockerized CLI commands that help standardize your CLI environment between different execution environments.

_Works on my machine_ aims to remove the hurdle of different versions, operating systems, CPU architectures and configurations, in the end, improving developer satisfaction and productivity.


Commands
--------------------

### Curl

`bin/curl`

Uses the image `curlimages/curl`

### Gradle
`bin/gradle`

Uses the official Gradle image and outputs the build artiacts as exepected to ./build.
Can be used to replace gradlew

### Hugo
[https://gohugo.io/](https://gohugo.io/)

> The world’s fastest framework for building websites

`bin/hugo`
The default Hugo command used for building your static site

### Npm
`bin/npm `


Contribution
--------------------
Feel free to use this code wherever you like.

Contributions of new commands via Merge Request are highly appreciated


### Request new apps

If you want to request an app or a tool that is not part of this collection, feel free to request it via a ticket right here on Gitlab


Is it any good?
--------------------
[Yes](https://news.ycombinator.com/item?id=3067434)
