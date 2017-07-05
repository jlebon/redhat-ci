# Supported distros

Below is a full list of valid values for the `distro` key in
the YAML:

- `fedora/24/cloud`
- `fedora/25/atomic`
- `fedora/25/cloud`
- `centos/7/atomic`
- `centos/7/cloud`
- `centos/7/atomic/alpha`
- `centos/7/atomic/continuous`

It follows a consistent pattern:

```
$distro/$releasever/$variant[/$stream]
```

The images are automatically updated whenever the upstreams
update them.

## Fedora streams:

### fedora/25/atomic

This is the officially supported Atomic image from Fedora.
They are usuall updated
[every two
weeks](https://fedoraproject.org/wiki/Changes/Two_Week_Atomic).
You can download the image yourself from
https://getfedora.org/en/atomic/download/.

### fedora/24/cloud, fedora/25/cloud

These are the officially supported Cloud images from Fedora.
They are not usually updated after initial release. You can
download the image yourself from
https://alt.fedoraproject.org/en/cloud/.

## CentOS streams:

### centos/7/atomic

This is the official CentOS Atomic Host release. It follows
the component versions of Red Hat Enterprise Linux Atomic
Host and is usually updated every 2 to 6 weeks after RHEL
releases. You can download the image yourself from
https://wiki.centos.org/SpecialInterestGroup/Atomic/Download.

### centos/7/cloud

This is the official CentOS Cloud variant. Also usually
updated every 2 to 6 weeks after RHEL releases. You can
download the image yourself from
https://wiki.centos.org/Download.

### centos/7/atomic/alpha, centos/7/atomic/continuous

These images are built much more frequently and closely
track the master branch of the git repositories of many core
components of Atomic Host. For more information about these
streams, and to download the images yourself, see
https://wiki.centos.org/SpecialInterestGroup/Atomic/Devel.
