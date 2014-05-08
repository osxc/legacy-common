osxc - simple configuration for os x
====================================

This is the main development repository for [osxc](//github.com/osxc).

* For the website:
  - [Head here to see it](//osxc.github.io)
  - [Head here to contribute to it](//github.com/osxc/osxc.github.io)
* For the bootstrap script: [Head here](//github.com/osxc/xc-boot)
* For the forkable/personal/custom repo: [Head here](//github.com/osxc/xc-common)

Installation & Usage
--------------------

[See this !](//osxc.github.io)

Roadmap
-------

1. Better roles (less destructive & more pluggable to the existing)
2. Instead of storing every role in one repo: split it to have one role per repo and publish them to ansible galaxy.
3. Update the install script to have:
  - A set of tools on the computer to manage the osxc installation: `osxc run/update/...`
  - A custom repository containing the custom user configuration
  - Many ansible roles in /etc/ansible/roles.

**Why ?** I want to tink that osxc is more of a set of tools instead of a standalone software. (i.e. I want this tools to be usable from any ansible playbook).
