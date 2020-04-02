# qperf
Ubuntu 18.04 based qperf container

Arguments for qperf: https://linux.die.net/man/1/qperf

Example:

Server:
qperf

Client:
qperf localhost -t 10 -ub tcp_bw tcp_lat udp_lat
