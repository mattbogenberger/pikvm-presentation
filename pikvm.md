# Remote server access using PiKVM

## Preview

Bogey (Matt Bogenberger) will present: Remote server access using PiKVM

Consumer-grade motherboards are often lacking when it comes to OOB (out of band) management and LOM (lights out management). Aftermarket solutions like KVM switches exist, but they can be expensive, and those with network functionality even moreso.

The [PiKVM project](https://pikvm.org) aims to solve this problem using commonly available Raspberry Pi boards to add remote access to your existing hardware.

Bogey recently built a PiKVM kit and will walk you through the build process, setup, basic usage, and how to extend the functionality to multiple machines by using a KVM switch in tandem with the PiKVM.

## Presentation

### Introduction
### Background
#### Terminology
- [KVM](https://en.wikipedia.org/wiki/Rackmount_KVM): keyboard, video, and mouse
- [KVM over IP](https://en.wikipedia.org/wiki/KVM_switch#KVM_over_IP_(IPKVM)): allows remote control via the network
- [KVM switch](https://en.wikipedia.org/wiki/KVM_switch): allows multiple machines to be controlled via selection
- [OOB management](https://en.wikipedia.org/wiki/Out-of-band_management):
    - "out-of-band"
    - uses separate channel for management of machine
    - think IPMI vs VNC/SSH
- LOM:
    - "lights-out management"
    - used for remote/off-site managament of machines
### Build

Parts included in [PiKVM kit](https://www.pishop.us/product/pikvm-v3-hat-for-raspberry-pi-4/)
![Parts included in PiKVM kit](https://cdn11.bigcommerce.com/s-2fbyfnm8ev/images/stencil/1280x1280/products/1329/4653/kvm__87360.1622477569.jpg?c=2)

[Steel case](https://www.pishop.us/product/steel-case-for-pikvm/)
![Steel case](https://cdn11.bigcommerce.com/s-2fbyfnm8ev/images/stencil/1280x1280/products/1448/5343/1792-f__27222.1639412755.jpg?c=2)

Parts included with case
![Parts included with case](https://cdn11.bigcommerce.com/s-2fbyfnm8ev/images/stencil/1280x1280/products/1448/5342/1792-h__92809.1639412638.jpg?c=2)

### Setup
### Usage
### KVM switch
### Considerations
#### Video source
#### Concurrent usage
### Conclusion
