# telegraf-snap
## How to build
```
sudo snap install snapcraft --classic
cd telegraf-snap
snapcraft
```
## Additional information
This snapcraft.yaml will build the latest stable version of telegraf.

At the time of its writing the `go` plugin didn't allow this kind of operations, so it's using the `nil` plugin with `override-build` instructions.
