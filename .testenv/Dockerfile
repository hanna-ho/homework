FROM rockylinux:9
RUN dnf -y install systemd procps-ng python3 python3-pip iproute && dnf clean all
STOPSIGNAL SIGRTMIN+3
CMD ["/usr/sbin/init"]
