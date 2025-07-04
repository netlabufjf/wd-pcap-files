# wd-pcap-files

Archive of the PCAP files created as part of the evaluation of a 5G simulated environment created by the [free5GC auto deploy](https://github.com/oliveiraleo/free5gc-auto-deploy) tool

## File naming pattern

The packets captured while using [UERANSIM](https://github.com/aligungr/UERANSIM) have the `3gpp` prefix, while the `non-3gpp` prefix refers to the packets captured using the [TNGFUE](https://free5gc.org/guide/TNGF/tngfue-installation/)

The suffix contains the interface name where the capture was performed: 

- `loopback`: packets transmitted between the 5GC NFs
- `upfgtp`: packets that leave the 5GC to reach the internet (via UPF)
- `enp0s3`: packets used by the VM to communicate with the real host (internet access, etc)
