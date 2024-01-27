# EnterpriseOS is a Fedora based project for business.

## Architecture

| Choose edition | EnterpriseOS Hub | EnterpriseOS Workstation | EnterpriseOS Kiosk | EnterpriseOS Server | EnterpriseOS Cloud |
| ---	| :-:	| :-:	| :-:	| :-:	| :-:	|
| Scope | Workstation | Workstation | POS | Intranet | Internet |
| Based on | .Net Framework | Fedora | Fedora | Fedora | Fedora |
| Zero telemetry |  | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:	|
| EnterpriseOS core |  | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:	|
| Minimal KDE |  | :heavy_check_mark: | :heavy_check_mark: | 	| 	|
| Office automation	| 	| :ballot_box_with_check:	| 	| 	| 	|
| WebApps Client 	| :ballot_box_with_check: | :ballot_box_with_check:	| 	| 	| 	|
| Network Tools	|	 | 	| 	| :ballot_box_with_check:	| 	|
| Webservers	| 	| 	| :ballot_box_with_check:	| :ballot_box_with_check:	| :ballot_box_with_check: |
| DBMS	| 	| 	| :ballot_box_with_check:	| :ballot_box_with_check:	| :ballot_box_with_check: |
| DevOps Tools	| 	| 	| | :ballot_box_with_check: | :ballot_box_with_check: |
| Control Panel	| 	| 	| :ballot_box_with_check: | :ballot_box_with_check: | :ballot_box_with_check: |
| No release available	| Download ISO | Download ISO | Download ISO | Download ISO | Download ISO |

:heavy_check_mark: Included 
:ballot_box_with_check:	Optional 
:link: Linked 

> Consider the fact that there is no release version yet, we are developing the first distribution.

### EnterpriseOS Hub

EnterpriseOS Hub offers an installation suite of client applications that can interact with the EnterpriseOS core infrastructure on Microsoft Windows &reg;

### EnterpriseOS Workstation

Designed to be a suitable installation for a work station, both for operators and administrators, it tries to have the necessary tools and the necessary requirements in a company.

### EnterpriseOS Kiosk

Designer for point of sale stations, order control, or self-service, ideal for unattended and public access computers.

### EnterpriseOS Server

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed facilisis sem ultrices augue vulputate, ut iaculis massa maximus. Sed ac eros sit amet nulla rhoncus iaculis. Pellentesque elementum iaculis odio ac ultrices. Morbi non sodales nunc, eget sodales elit. Integer pulvinar lacus massa, non ullamcorper ante efficitur eget. Nunc purus urna, malesuada ac est eget, pulvinar faucibus risus. Sed molestie fermentum iaculis. Sed et elit est. Suspendisse imperdiet nisi eros. Sed hendrerit ante erat, ac congue ipsum auctor convallis.

 ### EnterpriseOS Cloud

Etiam tristique dolor vel consequat fringilla. Integer id odio auctor, dictum elit quis, pharetra velit. Vivamus quis magna tortor. Ut ac purus nec purus consequat mattis vitae ornare ipsum. Nullam aliquam aliquam lacus, id malesuada sapien ullamcorper a. Sed sed lectus a nisl ullamcorper imperdiet. Sed felis ante, maximus sit amet tempus vitae, volutpat eget enim. Donec nunc elit, egestas vitae suscipit et, ullamcorper a ipsum. Aliquam mi dolor, semper eu sapien ut, vehicula tempus ex.

## The Infrastructure

### Server infrastructure

| Storage | Security | Intranet |  DMZ | Web | DBMS | DevOps | Virtualization |
|---	|---	|---	|---	|---	|---	|---	|---	|
| NFS | TPM 2.0 | Squid Proxy | Load Balancer | Apache | MySQL | Jenkins | KVM |
| iSCSI | FreeIPA | Captive portal | High availability | Nginx | PostgreSQL | TeamCity | Vagrant |
| GlusterFS | OpenLDAP | IP DVR | Multi WAN | Tomcat	|  | GitLab | Podman |
| Samba | Firewall | IP PBX | NAT | DNS Server |  | Redmine | Kubernetes |
| FTP Server | PPPoE Server | DHCP Server | VPN Server | Mail Server	|  	| |  |


🔴 🟠 ⚫ ⚪ 🟣 🟢 🟡 🔵
