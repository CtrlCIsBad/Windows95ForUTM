# Windows95ForUTM
Pre-installed Windows 95 for UTM (MacBook) UTM (iOS/iPadOS) and UTM SE (iOS/iPadOS)
If you also want to go through setup manually (eg., changing some settings) there is also an pre-configured .utm file

Pre-installed file: https://drive.google.com/file/d/19d9z-K6t2y9oGMy3qVUWDLTFl8aFydfT/view?usp=drivesdk

Pre-configured file: https://drive.google.com/file/d/1_5LlEOWCt2SVPpWxVthp2narA0sl4EKa/view?usp=drivesdk

Note: If you are downloading the pre-configured file, you need to get the iso in order to go through. An iso i recommend is this one from archive.org: https://archive.org/details/win-95-osr-2

Note 2: ⚠️ SECURITY WARNING & LIABILITY DISCLAIMER

• Network Vulnerabilities: Windows 95 is a completely obsolete operating system. It lacks modern security protocols, firewalls, and encryption standards. Enabling networking inside this Virtual Machine (VM) exposes the guest environment to severe security vulnerabilities.

• Malware Risk: Visiting modern websites via legacy browsers or running untrusted files within Windows 95 can expose the local VM network interface to malicious traffic.

• Local Network Exposure: If you configure the network adapter, malicious traffic inside the VM could theoretically scan your local network or router. 

• Host Isolation: While iOS/iPadOS sandboxing strictly prevents the VM from accessing your personal data (messages, photos, etc.), running outdated network stacks on any host machine carries inherent security risks.

• No Liability: This project is provided strictly for historical emulation, nostalgia, and educational purposes. The author and contributors of this repository bear absolutely zero responsibility for any data loss, network disruptions, router configuration changes, or security breaches on your host devices (MacBook, iPhone, iPad) resulting from altering these settings. You choose to enable networking entirely at your OWN RISK.

If you understand the security risks outlined above and still wish to proceed, follow these steps to add a network interface:

Step 1: Open UTM and select your Windows 95 virtual machine.
Step 2: Open the VM Settings configuration panel.
Step 3: Navigate to the Network tab and add a hardware interface.
Step 4: Set the Network Mode to "Shared Network (NAT)" for host isolation.
Step 5: Change the Emulated Network Card device type to "ne2k_pci".
Step 6: Save the settings and boot the VM.
