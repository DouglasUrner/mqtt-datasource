# Installation Instructions for [mqtt-datasource][repo]

Starting from notes by [whbruce on GitHub][install-issue].

## Linux (Raspberry Pi)

### Install [Node.js][node.js] LTS from NodeSource

```sh
sudo bash
curl -fsSL https://deb.nodesource.com/setup_20.x | bash - &&\
apt-get install -y nodejs
```
This also installs Corepack.

The official instructions and list of supported platforms are here: [NodeSource Node.js Binary Distributions][nodesource-distributions]

### Build with [Yarn][yarn]

```sh
corepack enable

```

The offical instructions are here [][yarn-install]

[install-issue]: <https://github.com/grafana/mqtt-datasource/issues/15#issuecomment-894477802>
[node.js]: <>
[nodesource-distributions]: <https://github.com/nodesource/distributions?tab=readme-ov-file>
[repo]: <https://github.com/grafana/mqtt-datasource>
[yarn]: <>
[yarn-install]: <https://yarnpkg.com/getting-started/install>
