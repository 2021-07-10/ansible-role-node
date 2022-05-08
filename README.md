# Ansible Role: Node 16.x

Installs Node 16.x on Ubuntu 20.04

## Requirements

None

## Role Variables

* `node_version`: 配置 `node` 版本

## Dependencies

None

## Example Playbook

```yaml

- hosts: servers
  roles:
     - { role: guxiaobai.node, node_version: 16.x }
```

## License

BSD

## Ref

* [Node.js Binary Distributions](https://github.com/nodesource/distributions/blob/master/README.md)