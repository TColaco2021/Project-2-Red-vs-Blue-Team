# Project-2-Red-vs-Blue-Team

# Unit Description

In this project week, I worked on a Red Team vs. Blue Team scenario in which I played the role of both pentester and SOC analyst.

As the Red Team, I attacked a vulnerable VM within a network environment, ultimately gaining root access to a virtual machine. As the Blue Team, I used Kibana to review logs taken during my Day 1 engagement activities. I used the logs to extract hard data and visualizations for my report.

Then, I interpreted my log data to suggest mitigation measures for each exploit that I successfully performed.

# This project prompted me to apply knowledge of the following skills and tools:

Penetration testing with Kali Linux.

Log and incident analysis with Kibana.

System hardening and configuration.

Reporting, documentation, and communication.

# Lab Environment

In this unit, we used a pre-designed Red vs Blue lab environment located in Windows Azure Lab Services. 

    # We were able to RDP into the Windows RDP host machine using the following credentials:

    Username: azadmin
    Password: p4ssw0rd*
    
# Open the Hyper-V Manager to access the nested machines:

    # ELK machine credentials: The same ELK setup that we created in a previous project held various Kibana dashboards.

    - Username: vagrant
    - Password: vagrant
    - IP Address: 192.168.1.100

    # Kali: A standard Kali Linux machine for use in the penetration test on Day 1.

    - Username: root
    - Password: toor
    - IP Address: 192.168.1.90
    
    # Capstone: Filebeat and Metricbeat are installed and will forward logs to the ELK machine.

    - IP Address: 192.168.1.105
    - Please note that this VM wass in the network solely for the purpose of testing alerts.

    # Target 1: Exposes a vulnerable WordPress server.

    - IP Address: 192.168.1.110

# This porject covered portions of the following domains on the Security+ exam:

    - 1.0 Attacks, Threats, and Vulnerabilities
    - 2.0 Architecture and Design
    - 3.0 Implementation
    - 4.0 Operations and Incident Response
