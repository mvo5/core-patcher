# Core patcher will patch an existing core snap with new snapd

This is a helper script that can be used to take an existing "core"
snap and update it with a new version of snapd from a deb. This
is useful for testing and also for creating targeted security updates
to core that do not involve re-building the entire rootfs of core
which may involve pulling in new packages.

To use it, edit the `{OLD,NEW}_VER` version and then download the
updated debs from Launchpad or a private PPA for all the supported
architectures in the same directory that the tool run from.
