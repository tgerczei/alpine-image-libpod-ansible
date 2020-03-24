# alpine-image-libpod-ansible: a simple playbook to automate container image building based on Alpine Linux

## Usage

### Pre-requisites
<ul>
<li>Ansible 2.9+</li>
<li>libpod</li>
<li><i>directory</i> <strong>$HOME</strong>/alpine-<strong>package_name</strong></li>
<li><i>file</i> <strong>$HOME</strong>/alpine-<strong>package_name</strong>/Dockerfile</li>
</ul>

Developed and tested on Gentoo GNU/Linux with ZFS via fuse-overlayfs and crun in rootless mode.

### Variables
<ul>
<li>default_alpine_version</li>
<li>package_name</li>
</ul>

### Invocation
ansible-playbook alpine-image.yaml

#### Credits
Gerard Lynch for the [HTML parsing hint](https://gist.github.com/halberom/e8748635d8dd6e363b208a810eb70bc7)
