# Windows95ForUTM
Pre-installed Windows 95 for UTM (MacBook) UTM (iOS/iPadOS) and UTM SE (iOS/iPadOS)
If you also want to go through setup manually (eg., changing some settings) there is also an pre-configured .utm file

Pre-installed file: https://drive.google.com/file/d/19d9z-K6t2y9oGMy3qVUWDLTFl8aFydfT/view?usp=drivesdk

Pre-configured file: https://drive.google.com/file/d/1_5LlEOWCt2SVPpWxVthp2narA0sl4EKa/view?usp=drivesdk

Note: If you are downloading the pre-configured file, you need to get the iso in order to go through. An iso i recommend is this one from archive.org: https://archive.org/details/win-95-osr-2

Note 2: I have disabled networking by default because Windows 95 is ancient and lacks modern security. Enabling it exposes the VM to major security flaws. If you turn it on, malware inside the VM could try to scan your local network or target your router's IP address. For iOS and iPadOS users, Apple's strict sandboxing prevents the VM from accessing personal data like your messages or photos. However, running an unencrypted, legacy network stack on a Mac carries higher security risks for the host machine. These risks generally trigger only if you visit unsafe websites using Internet Explorer or run untrusted files inside Windows 95. If you choose to enable networking, you do so knowing these risks. The author bears absolutely zero responsibility for any security issues, network disruptions, or compromises to your Mac, iPhone, or local network. Proceed entirely at your OWN risk.

Step 1: Go to UTM settings.
Step 2: Add a network interface.
Step 3: Set the network card to ne2k_pci.
That's all!

