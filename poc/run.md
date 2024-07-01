# Run the POC

## Lauch the stack 

```bash
docker-compose up --build
```

## Create LDAP entries

You can use phpldapadmin to add users and groups.

## Configure Kerberos

```bash
docker exec -it kerberos kadmin.local -q "addprinc user/admin"
docker exec -it kerberos kadmin.local -q "addprinc -randkey host/debian-client.myorg.com"
```