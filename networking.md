## OpenShift Container Platform only supports the following bond modes:

mode=1 active-backup

mode=2 balance-xor

mode=4 802.3ad

mode=5 balance-tlb

mode=6 balance-alb

ocp virt supports LACP (IEEE802.3ad) - OpenShift Container Platform uses nmstate to report on and configure the state of the node network
