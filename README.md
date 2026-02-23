Windows Active Directory Domain Services Lab
Overview

This project demonstrates the design and implementation of an enterprise-style Windows Server environment focused on centralized identity management, policy enforcement, and network resource administration.

The lab simulates real-world Active Directory operations, administrative delegation, and Group Policy deployment commonly found in production domain environments.

Environment Architecture

Deployed a Domain Controller with:

Active Directory Domain Services (AD DS)

DNS Server

DHCP Server

Designed a structured Organizational Unit (OU) hierarchy for:

Users

Administrative roles

Policy scoping

Created domain users, security groups, and role-based access model

Group Policy Implementation

Designed and applied Group Policy Objects (GPOs) within a controlled OU structure to simulate enterprise policy management.

Key configurations include:

Account Lockout Policy
Configured authentication protection mechanisms to mitigate brute-force login attempts and unauthorized access risks.

User Account Management Scenarios
Demonstrated password reset workflows, account unlock procedures, and forced password changes at next logon.

Policy Scoping & Inheritance
Implemented GPO linking strategy and inheritance planning for targeted policy application.

Delegation of Control

Implemented a least-privilege administrative model by delegating permissions to an IT Security group.

Delegated capabilities include:

User account management within designated OU

Password resets and account unlock operations

Group membership modification

Controlled object administration without Domain Admin privileges

Delegation behavior was validated using RSAT tools from a domain-joined client machine.

Network Shares & Drive Mapping

Configured centralized network resources and automated access provisioning.

Created shared folders on the server

Deployed drive mappings via Group Policy Preferences

Used Item-Level Targeting to control department-specific access

Validated user experience through domain logon testing

DHCP & Core Network Services

Configured DHCP services to support domain operations.

DHCP options configured:

Default Gateway

DNS Server

Domain Name Assignment

This ensured automatic client configuration and proper domain integration.

Administrative Tools & Validation

Management and testing performed using:

Remote Server Administration Tools (RSAT)

Active Directory Users and Computers (ADUC)

Group Policy Management Console (GPMC)

Validated:

Delegated permissions

Policy application behavior

Identity management workflows

Key Learning Outcomes

Designed structured OU and policy hierarchy

Implemented least-privilege delegation model

Practiced enterprise authentication security controls

Automated resource access using GPO & targeting

Understood interaction between AD DS, DNS, and DHCP

Technologies Used

Active Directory • Group Policy • DNS • DHCP • RSAT • Windows Server
