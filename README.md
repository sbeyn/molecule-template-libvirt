# molecule-template-libvirt Ansible Project

## Included content/ Directory Structure

The directory structure follows best practices recommended by the Ansible
community. Feel free to customize this template according to your specific
project requirements.

```shell
.
├── ansible.cfg
├── collections
│   ├── ansible_collections
│   │   └── sbeyn
│   │       └── molecule-template-libvirt
│   │           ├── CHANGELOG.md
│   │           ├── galaxy.yml
│   │           ├── meta
│   │           │   └── runtime.yml
│   │           ├── README.md
│   │           └── roles
│   │               └── run
│   │                   ├── README.md
│   │                   └── tasks
│   │                       └── main.yml
│   └── requirements.yml
├── inventory
│   ├── group_vars
│   │   └── all.yml
│   ├── hosts.yml
│   └── host_vars
├── molecule
│   └── default
│       ├── create.yml
│       ├── destroy.yml
│       ├── molecule.yml
│       └── templates
│           ├── meta-data.j2
│           ├── network-config.j2
│           ├── user-data.j2
│           └── vm.xml.j2
├── README.md
└── site.yml

```

## Compatible with Ansible-lint

Tested with ansible-lint >=24.2.0 releases and the current development version
of ansible-core.
