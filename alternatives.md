# Alternatives to MICROSOFT

## OS
Custom a distro with centralized authentification and sync file system, using :

## FLEET
[Ansible](https://github.com/ansible/ansible) for the management and configuration of the users fleet

> [Salt](https://github.com/saltstack/salt) or [Puppet](https://github.com/puppetlabs/puppet)

## FILE SYSTEM
[Ceph](https://github.com/ceph/ceph) for file system
- Possibility to give each user a specific subfolder access
- Provides Block Storage and object gateway Storage (S3)

> Others : [seafile](https://github.com/haiwen/seafile) or 

## AUTH
The os should support 2 layers for Authorization and Identification
For one, the only all in one tool is : [KaniDm](https://github.com/kanidm/kanidm) 
Rust, self made db with backups, one common db for web + pam, dedicated unix daemon
Provides a read-only ldap for specific use cases
radius support for vpn

> Others : [CAS](https://github.com/apereo/cas) or [Authelia](https://github.com/authelia/authelia) or [Ory network](https://www.ory.sh/docs/ecosystem/projects) for web-auth and [Kerberos](https://web.mit.edu/kerberos/) for unix authentification


# SECURITY

## Office suite
[ONLY OFFICE](https://github.com/ONLYOFFICE/DocumentServer)

[CollaboraOnline](https://github.com/CollaboraOnline/online)

## INTERNAL COMMUNICATION

### TEXT
[Mattermost](https://github.com/mattermost/mattermost)

[Zulip](https://github.com/zulip/zulip)

Self made client with :
- presence status linked to badging hours
- direct messages
- meetings creation with group created
- integrated calendar

### VIDEO
[Wire](https://github.com/wireapp/wire)
> Others : [Jisti Meet](https://github.com/jitsi/jitsi-meet), [NextCloud Talk](https://github.com/nextcloud/spreed)

## EXTERNAL COMMUNICATION
SMTP Server with [JMAP](https://jmap.io/) support like [StalwartLabs Mail Server](https://github.com/stalwartlabs/mail-server) or [Apache James](https://github.com/apache/james-project)

Self made client with a specifity to reduce pollution : don't send throught smtp the internal emails.

## HR TOOLS
A unique tool which allows :
- employees to : 
    - badge in and out virtually
    - request remote work days
    - request some vacation days
    - report future absences
- managers to :
    - monitor badging in and out virtually
    - accept/refuse remote work days
    - accept/refuse some vacation days
    - monitor future absences
- HR to :
    - 
    - emit pay sheets upload into the employee drive

## EMPLOYEES BENEFITS
[Password manager](https://github.com/dani-garcia/vaultwarden)
[Personnal drive with 5GO for example, linked with HR emitted documents](https://github.com/newtondotcom/CoffreTonDoc)