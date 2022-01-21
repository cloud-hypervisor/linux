# Cloud Hypervisor Linux Fork

Contains patches for:

* virtio-iommu from https://jpbrucker.net/git/linux/log/?h=virtio-iommu/acpi (7616abe11cd1e0224bbd150626564db70bb07c31)
* Support for virtio-watchdog
* Bug fix: to support using ACPI reboot rather than EFI reboot
* Log boot time via debug port `0x80` (details: https://github.com/cloud-hypervisor/cloud-hypervisor/blob/main/docs/debug-port.md)
