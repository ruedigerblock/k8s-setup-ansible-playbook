# Vagrantfile + Ansible Playbook to set up a K8S locally using Virtual Box

tested on:

Darwin Rudigers-MBP.fritz.box 21.5.0 Darwin Kernel Version 21.5.0: Tue Apr 26 21:08:22 PDT 2022; root:xnu-8020.121.3~4/RELEASE_X86_64 x86_64

(might also work on M1's and M2's)

inspired by <https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant> and adapted to work with CRI-O instead of Docker.

## Prerequisites

```
brew install virtualbox ansible vagrant
```

## How To

Clone repo change into the folder containing the repository and `vagrant up`

