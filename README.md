# KVM_Libvirt
code created for Issues with LVM/libvirt

#error:
Virtual Machines > select guest > create sanpshot > give descritption >click create
Troubleshoot KVM snapshot time out
Error message: Timed out during operation: cannot acquire state change lock (held by monitor=remoteDispatchDomainSnapshotCreateXML)

Attempt with virsh
https://www.linuxtechi.com/create-revert-delete-kvm-virtual-machine-snapshot-virsh-command/

Command:
virsh snapshot-create PiHole

virsh snapshot-list PiHole

seems cockpit had made one anyway

#unbound installation
installed and configured and processing requests.
