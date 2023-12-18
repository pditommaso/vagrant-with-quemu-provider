# vagrant-with-quemu-provider

Allow the use of x86 VMs on macOS Silicon via [Vagrant](https://www.vagrantup.com/) and [qemu](https://www.qemu.org/) [provider](https://github.com/ppggff/vagrant-qemu).


### Get started 

1. Install Vagrant and qemu 

    brew install vagrant qemu

2. Install Vagrant plugins 

    vagrant plugin install vagrant-vbguest
    vagrant plugin install vagrant-qemu


3. Clone this repo 

    git clone https://github.com/pditommaso/vagrant-with-quemu-provider \
      && cd vagrant-with-quemu-provider


4. Launch the VM

    vagrant up

5. SSH into it 

    vagrant ssh 


6. Shutdown 

    vagrant destroy 


### Links 

  * https://gist.github.com/beauwilliams/69eabc42e540a309f53d55c4b8e6ffe3
  * https://medium.com/@TETRA2000/do-m1-mac-dream-of-x86-linux-117478fc9623
  * https://github.com/ppggff/vagrant-qemu