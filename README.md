# Small Business IT Infrastructure Lab

## Active Directory – Windows Server

### Project Overview
A virtual IT infrastructure lab created to practise Windows Server administration and basic system integration tasks.

### Environment
- Domain: `firma.test`
- Domain Controller: `DC01` (`192.168.10.20`)
- Additional Windows Server: `WIN-SRV22` (`192.168.10.21`)

### Implemented Tasks
- Configured and tested an Active Directory domain.
- Created organisational units for IT and Accounting.
- Created test users: `it.test` and `buchhaltung.test`.
- Created security groups: `GG_IT` and `GG_Buchhaltung`.
- Configured the network share `\\DC01\Firma` with separate IT and Accounting folders.
- Tested access to shared folders.
- Joined `WIN-SRV22` to the domain.
- Verified the domain secure channel with `nltest /sc_verify:firma.test`.
- Added Windows Server monitoring with Checkmk.

### Skills Practised
- Windows Server
- Active Directory and domain administration
- User and group management
- File sharing and access permissions
- Domain joining and troubleshooting
- Infrastructure monitoring

### Lab Status
Core Active Directory configuration and domain connectivity checks have been completed in a virtual lab.

This project is for learning and demonstration purposes. No passwords or credentials are included.

## Active Directory – Organisational Units

The following screenshot shows the organisational structure configured in the lab.

![Active Directory organisational units](active-directory-ous.png)
