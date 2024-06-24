# Alternatives to MICROSOFT

## OS
Custom a distro with centralized authentification and sync file system, using :
- [Ansible](https://github.com/ansible/ansible) or [Salt](https://github.com/saltstack/salt) for the management and configuration of the users fleet
- [Kerberos](https://web.mit.edu/kerberos/) for local authentification
- [OpenLDAP](https://www.openldap.org/) for centralized authentification
- [CAS](https://github.com/apereo/cas) or [Authelia](https://github.com/authelia/authelia) for web authentification
- [seafile](https://github.com/haiwen/seafile) for file system

# SECURITY

## Office suite
[ONLY OFFICE](https://github.com/ONLYOFFICE/DocumentServer)

[CollaboraOnline](https://github.com/CollaboraOnline/online)

## INTERNAL COMMUNICATION
[Mattermost](https://github.com/mattermost/mattermost)

[Zulip](https://github.com/zulip/zulip)

## EXTERNAL COMMUNICATION
SMTP Server with [JMAP](https://jmap.io/) support like [StalwartLabs Mail Server](https://github.com/stalwartlabs/mail-server) or [Apache James](https://github.com/apache/james-project)

Self made client with a specifity to reduce pollution : don't send throught smpt the internal emails.

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