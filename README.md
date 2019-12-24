# confluent-platform-delopy-local

## What is this?

This is an example ansible playbooks to deploy Confluent Platform as a test.
Using this project, you can launch a standalone Kafka (Single process w/ Single ZooKeeper) .

## Requirements

- Ansible
- JDK

## How to use?

Execute the following command.

```
$ ansible-playbook playbooks/conf/confluent_standalone.yml -b -c local -K
```


## License

GNU General Public License v3.0 or later

Please read COPYING.txt for the detail.

<!-- vim: set et ts=2 sw=2: -->
