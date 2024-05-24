# SEQAX408DevOpsTechVagrant

## Getting started
- Clone the  HelloHttp repo from: `https://github.com/drines-uc/hello_http`
- Clone this repo in the same base directory as the HelloHttp repo
- `cd SEQAX408DevOpsTechVagrant`
- Run `vagrant up` to create, configuration, and provision a guest machine according to the Vagrantfile
- Run `vagrant ssh` to establish an SSH session into a running VM to get access to the shell
- Move into out app directory `cd /hello_http` 
- Run `gcc -o dummyserv dummy_serv.c` to compile the dummyserv
- Run `./dummyserv` to start the process

Note:
- Using `gyptazy/ubuntu22.04-arm64` is it compatible with Apple's M1/M2 chips.
 
