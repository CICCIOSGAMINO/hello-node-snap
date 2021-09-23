hello-node-snap
===============

Simple node hello snap, build with latest node.js versions

```bash
# clone the template
git clone --depth=1 https://github.com/CICCIOSGAMINO/hello-node-snap.git  . && rm -rf ./.git

# locally build the snap
snapcraft --debug

# locally install the snap
snap install --devmode hello-node-snap_1.0.0_amd64.snap
```