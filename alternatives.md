# Alternatives to MICROSOFT : myrProject

## OS : myrOS
Custom a distro with centralized authentification and sync file system, using :

## FLEET
[Ansible](https://github.com/ansible/ansible) for the management and configuration of the users fleet
[Other](https://github.com/fleetdm/fleet)
> [Salt](https://github.com/saltstack/salt) or [Puppet](https://github.com/puppetlabs/puppet)
> [GLPI](https://github.com/glpi-project/glpi)

## FILE SYSTEM : Dryve
[Ceph](https://github.com/ceph/ceph) for file system
- Possibility to give each user a specific subfolder access
- Provides Block Storage and object gateway Storage (S3)

> Others : [seafile](https://github.com/haiwen/seafile)

### SPACE TO EXCHANGE FOLDER
Self Made client which combines Ceph and KaniDM to provide a space
to exchange files and folders in a mail for example, driven by an API
Interface is opened from webmail and user can chose to give access to
current version only or the new versions.

## AUTH
The os should support 2 layers for Authorization and Identification
For one, the only all in one tool is : [KaniDm](https://github.com/kanidm/kanidm)
Rust, self made db with backups, one common db for web + pam, dedicated unix daemon
Provides a read-only ldap for specific use cases
radius support for vpn

> Others : [CAS](https://github.com/apereo/cas) or [Authelia](https://github.com/authelia/authelia) or [Ory network](https://www.ory.sh/docs/ecosystem/projects) for web-auth and [Kerberos](https://web.mit.edu/kerberos/) for unix authentification

## Office suite
[ONLY OFFICE](https://github.com/ONLYOFFICE/DocumentServer)

[CollaboraOnline](https://github.com/CollaboraOnline/online)

## INTERNAL COMMUNICATION
### LINGORA PROJECT
[Linagora project](https://github.com/linagora/twake-workplace)

### TEXT
[Mattermost](https://github.com/mattermost/mattermost)

[Zulip](https://github.com/zulip/zulip)

Self made client with :
- presence status linked to badging hours
- direct messages
- meetings creation with group created
- integrated calendar

### VIDEO
[BigBlueButton](https://github.com/bigbluebutton/bigbluebutton)
> Others : [Jisti Meet](https://github.com/jitsi/jitsi-meet), [NextCloud Talk](https://github.com/nextcloud/spreed)

### BOTH : Tym
[Element](https://github.com/element-hq)
> Others : [Wire](https://github.com/wireapp/wire)

### Ressources and community discussion
A [wiki](https://github.com/requarks/wiki/tree/main)
[Discourse](https://github.com/discourse/discourse) for internal community discussion

### PDF Operations
[Stirling PDF](https://github.com/Stirling-Tools/Stirling-PDF)
[Xournal](https://github.com/xournalpp/xournalpp/)

## EXTERNAL COMMUNICATION : Mayl
SMTP Server with [JMAP](https://jmap.io/) support like [StalwartLabs Mail Server](https://github.com/stalwartlabs/mail-server) or [Apache James](https://github.com/apache/james-project)

Self made client with a specifity to reduce pollution : don't send throught smtp the internal emails, report spam and phishing, and use JMAP protocol for the external emails. Internal mails : dont send attachments, use a link using the dedicated API to the file in the Dryve

## HR TOOLS: hR
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
    - create Job offerts and manage the recruitment process like Workday
    - emit pay sheets upload into the employee drive

## SIGNING TOOL
-> firefox can become a pdf viewer
[Docuseal](https://github.com/docusealco/docuseal)

## EMPLOYEES BENEFITS
[Password manager](https://github.com/dani-garcia/vaultwarden)
[Personnal drive with 5GO for example, linked with HR emitted documents](https://github.com/newtondotcom/CoffreTonDoc)

## SECURITY
[ossec-hids](https://github.com/ossec/ossec-hids)
[wazuh](https://github.com/wazuh/wazuh)
[openedr](https://github.com/ComodoSecurity/openedr)

## DOCKER REGISTRY
[harbor](https://github.com/goharbor/harbor)

## FORMS

## ORGANIGRAMME pour permissions de congé etc, organigramme web

## Unified Push System 
[gotify](https://github.com/gotify/server)
[ntfy](https://github.com/binwiederhier/ntfy)
