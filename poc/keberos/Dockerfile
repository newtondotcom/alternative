FROM debian:bullseye

RUN apt-get update && apt-get install -y \
    krb5-kdc \
    krb5-admin-server \
    && rm -rf /var/lib/apt/lists/*

COPY kdc.conf /etc/krb5kdc/kdc.conf
COPY kadm5.acl /etc/krb5kdc/kadm5.acl
COPY krb5.conf /etc/krb5.conf

RUN krb5_newrealm <<EOF
admin
admin
EOF

EXPOSE 88 464

CMD ["krb5kdc", "-n"]
