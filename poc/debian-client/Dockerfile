FROM debian:bullseye

RUN apt-get update && apt-get install -y \
    krb5-user \
    libpam-krb5 \
    libpam-ldapd \
    nslcd \
    ldap-utils \
    && rm -rf /var/lib/apt/lists/*

COPY nslcd.conf /etc/nslcd.conf
COPY krb5.conf /etc/krb5.conf
COPY pam.d/* /etc/pam.d/

RUN echo "session required pam_mkhomedir.so skel=/etc/skel umask=0022" >> /etc/pam.d/common-session

CMD ["bash"]
