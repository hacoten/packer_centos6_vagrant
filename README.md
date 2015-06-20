# packer_centos6_vagrant

Created Vagrant Box Image.
Recommended you use Ansible. (Provisioning tools)

## Install(Mac OSX)

    $ brew tap homebrew/binary
    $ brew install packer

## Build Packer

    $ git clone biz1@biz1.git.backlog.jp:/DEVNOTE/packer_centos6_vagrant.git
    $ cd packer_centos6_vagrant
    $ packer build template.json

* If you want to build only virtualbox or vmware.

        $ packer build -only=virtualbox-iso template.json
        $ packer build -only=vmware-iso template.json

