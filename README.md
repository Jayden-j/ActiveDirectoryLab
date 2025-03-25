<h1>Basic Home Lab - Active Directory Setup (Oracle VirtualBox)</h1>

    <h3><a href="#">YouTube Demonstration</a> *(Insert Link Here)*</h3>

    <h2>Description</h2>
    <p>This project provides a step-by-step guide for setting up a home lab running Active Directory using Oracle VirtualBox. The lab simulates a small Windows domain environment, allowing users to practice system administration, group policies, and cybersecurity techniques in a safe, controlled setup. The virtual environment consists of a Windows Server Domain Controller and a Windows Client machine.</p>

    <h2>Technologies and Tools Used</h2>
    <ul>
        <li><b>Oracle VirtualBox</b> - Virtualization platform</li>
        <li><b>Windows Server 2019/2022</b> - Active Directory Domain Services</li>
        <li><b>Windows 10/11</b> - Domain-joined client machine</li>
        <li><b>PowerShell</b> - Scripting and configuration</li>
        <li><b>Group Policy Management</b> - Security and policy enforcement</li>
        <li><b>DNS & DHCP</b> - Network configuration</li>
    </ul>

    <h2>Environments Used</h2>
    <ul>
        <li><b>Host OS:</b> Windows 10/11, Linux, or macOS</li>
        <li><b>Guest OS:</b> Windows Server 2019/2022, Windows 10/11</li>
    </ul>

    <h2>Lab Setup Walk-through</h2>

    <h3>1. Download and Install VirtualBox</h3>
    <ul>
        <li>Download and install <a href="https://www.virtualbox.org/">Oracle VirtualBox</a></li>
        <li>Install the VirtualBox Extension Pack for USB and network support</li>
    </ul>

    <h3>2. Create Virtual Machines</h3>
    <ul>
        <li>Create a VM for Windows Server (2 CPU, 4GB RAM, 60GB HDD)</li>
        <li>Create a VM for Windows Client (2 CPU, 2GB RAM, 40GB HDD)</li>
    </ul>

    <h3>3. Configure the Domain Controller</h3>
    <ul>
        <li>Install Windows Server and configure Active Directory Domain Services (AD DS)</li>
        <li>Promote the server to a domain controller</li>
        <li>Set up DNS and DHCP (if needed)</li>
    </ul>

    <h3>4. Configure the Client Machine</h3>
    <ul>
        <li>Install Windows 10/11</li>
        <li>Join the client to the domain</li>
        <li>Verify connectivity and authentication</li>
    </ul>

    <h3>5. Implement Group Policies</h3>
    <ul>
        <li>Create security policies and apply them to domain users</li>
        <li>Configure password policies and account lockout settings</li>
        <li>Set up login scripts and mapped network drives</li>
    </ul>

    <h3>6. Testing and Security Configuration</h3>
    <ul>
        <li>Verify domain authentication and user policies</li>
        <li>Test remote desktop and administrative tools</li>
        <li>Harden security with firewall rules and auditing</li>
    </ul>

    <h2>Screenshots</h2>
    <p>(Insert relevant setup screenshots here)</p>

    <h2>Future Enhancements</h2>
    <ul>
        <li>Adding Linux machine for cross-platform testing</li>
        <li>Configuring additional security policies (SIEM, IDS/IPS)</li>
        <li>Automating setup with PowerShell scripts</li>
    </ul>

    <h2>Credits</h2>
    <p>This lab is inspired by cybersecurity training labs and system administration best practices.</p>

    <hr>
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
