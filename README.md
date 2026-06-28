# Windows95ForUTM

Pre-configured shell configuration files to run Windows 95 smoothly on UTM (MacBook), UTM (iOS/iPadOS), and UTM SE (iOS/iPadOS).

### Project Files

* **UTM Profile Shell:** Do not look for separate Google Drive links anymore. The clean, pre-configured setup shell can be downloaded directly from the **Releases** section of this repository.

---

### Important Notes

**Note 1:** If you are downloading the pre-configured file from Releases, you need to get the official operating system ISO in order to complete the setup. An ISO I highly recommend is this one legally preserved on the Internet Archive: https://archive.org/details/win-95-osr-2

A valid product key is provided directly in the description of that page.

**Note 2:** I have disabled networking by default because Windows 95 is ancient and lacks modern security. Enabling it exposes the VM to major security flaws. If you turn it on, malware inside the VM could try to scan your local network or target your router's IP address. For iOS and iPadOS users, Apple's strict sandboxing prevents the VM from accessing personal data like your messages or photos. However, running an unencrypted, legacy network stack on a Mac carries higher security risks for the host machine. These risks generally trigger only if you visit unsafe websites using Internet Explorer or run untrusted files inside Windows 95. If you choose to enable networking, you do so knowing these risks. The author bears absolutely zero responsibility for any security issues, network disruptions, or compromises to your Mac, iPhone, or local network. Proceed entirely at your OWN risk.

---

### How to Enable Networking

Follow these steps for enabling networking at your **OWN** risk:

* **Step 1:** Go to UTM settings.
* **Step 2:** Add a network interface.
* **Step 3:** Set the network card to **ne2k_pci**.
