# Topics
1. 集群中多智能体的策略共享和更新.
2. 集群中的大规模算力共享.
3. 

unikernel

in-kernel D-Bus

# ebpf-notes

## eBPF VM

- Event-driving Progamming

[Cilium](https://github.com/cilium/cilium)

[BPF and XDP Reference Guide](https://docs.cilium.io/en/latest/bpf/#instruction-set)

[bpf.h](https://github.com/torvalds/linux/blob/v4.20/include/uapi/linux/bpf.h#L45)

`kernel/bpf/verifier.c`: verifies the bytecode that received from the usersapce.

[libbpf](https://github.com/torvalds/linux/tree/v4.20/tools/lib/bpf)

[libbcc](https://github.com/iovisor/bcc)

[BPFftrace](https://github.com/iovisor/bpftrace)

[IOVisor](https://www.iovisor.org/)

[uBPF](https://github.com/iovisor/ubpf)

[ply](https://github.com/wkz/ply)

[gobpf](https://github.com/iovisor/gobpf)

## eBPF Examples
- [v4.20](https://github.com/torvalds/linux/tree/v4.20/samples/bpf)

## References
- [eBPF Introduction - 1](https://www.collabora.com/news-and-blog/blog/2019/04/05/an-ebpf-overview-part-1-introduction/)
- [eBPF Introduction - 2](https://www.collabora.com/news-and-blog/blog/2019/04/15/an-ebpf-overview-part-2-machine-and-bytecode/)
- [eBPF Introduction - 3](https://www.collabora.com/news-and-blog/blog/2019/04/26/an-ebpf-overview-part-3-walking-up-the-software-stack/)
- [eBPF Introduction - 4](https://www.collabora.com/news-and-blog/blog/2019/05/06/an-ebpf-overview-part-4-working-with-embedded-systems/)
- [eBPF Introduction - 5](https://www.collabora.com/news-and-blog/blog/2019/05/14/an-ebpf-overview-part-5-tracing-user-processes/)
- [eBPF Features by Linux Kernel Version](https://github.com/iovisor/bcc/blob/master/docs/kernel-versions.md)