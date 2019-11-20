## Debian Stretch 64 Vagrant Basebox
Based on https://github.com/chef/bento
Use https://www.packer.io to build box

### Build Box via Packer
```packer build -only=virtualbox-iso debian-9.11-amd64.json```