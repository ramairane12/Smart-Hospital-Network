# Smart Hospital Network

### Designing a Secure and Scalable Hospital Network Using Cisco Packet Tracer

## Project Overview

This project demonstrates the design and configuration of a secure,
scalable hospital network using **Cisco Packet Tracer**. The network
connects different hospital departments and applies routing, network
access controls, and basic device-security measures to support reliable
communication while restricting unauthorized access.

The simulated network uses routers, switches, and PCs to represent the
hospital's network infrastructure.

## Objectives

-   Design a structured network for multiple hospital departments.
-   Enable communication between authorized departments.
-   Use dynamic routing to support communication between network
    segments.
-   Provide automatic IP address allocation to selected departments.
-   Apply access-control rules to restrict selected inter-department
    traffic.
-   Improve device and switch-port security.

## Hospital Departments

The network includes the following departments: - Doctors - Nurses -
Administration - Pharmacy - Laboratory - Security / CCTV

## Technologies and Concepts

-   **Cisco Packet Tracer** -- network design and simulation
-   **OSPF** -- dynamic routing between routers
-   **DHCP** -- automatic IP address allocation for configured
    departments
-   **ACLs (Access Control Lists)** -- traffic filtering between
    selected networks
-   **SSH** -- secure remote management for a configured switch
-   **Port Security** -- restricting access on a configured switch port
-   **Routers, switches, and PCs** -- network infrastructure

## Main Implemented Features

-   Three-router design using the devices named `R1-HOSPITAL`,
    `R2-EMERGENCY`, and `R3-ADMIN`.
-   OSPF configured between routers. The OSPF neighbor relationship
    between R1 and R2 was verified as **FULL** during testing.
-   DHCP configured for the Doctors and Nurses networks.
-   ACL rules configured to restrict selected traffic, including
    Nurses-to-Doctors communication and the configured network
    restrictions between networks 40/30 and 60/50.
-   SSH enabled on the configured Doctors switch (`SW1-DOCTORS`).
-   Port security configured on a port of the Security/CCTV switch
    (`SW6`).


## How to Open the Project

1.  Install and open **Cisco Packet Tracer**.
2.  Download or clone this repository.
3.  Open the `.pkt` file in Cisco Packet Tracer.
4.  Review the topology and device configurations.
5.  Use Packet Tracer simulation mode and device command-line interfaces
    to test connectivity and security rules.

## Verification and Testing

When reviewing the project, you can verify: - OSPF neighbor status
between the configured routers. - DHCP address assignment for Doctors
and Nurses devices. - Connectivity between permitted networks. -
Blocking of traffic restricted by the configured ACLs. - SSH access to
the configured switch. - Port-security behavior on the configured
Security/CCTV switch port.

Actual test results depend on the uploaded Packet Tracer file and its
current configuration.

## Learning Outcomes

This project provided practical experience in: - Planning and building a
multi-department network. - Configuring routers and switches. -
Understanding dynamic routing and DHCP. - Applying ACLs to control
network traffic. - Using SSH and port security for basic network
protection. - Testing and troubleshooting network connectivity.

## Author

**Ramai Rane**

## Disclaimer

This is an educational network simulation created using Cisco Packet
Tracer. It is not a production hospital network and should not be used
to manage real patient data or critical healthcare systems.
