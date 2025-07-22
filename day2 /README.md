🛠️ Setting Up VirtualBox and Kali Linux for Ethical Hacking
Creating a virtual lab is a safe and legal way to practice ethical hacking. Here's how to download and set up VirtualBox and Kali Linux:

🧰 Step 1: Download VirtualBox
Visit the VirtualBox Downloads Page.

Choose the version for your operating system (Windows, macOS, Linux).

Download and install the VirtualBox Extension Pack for added features (like USB support).

🐉 Step 2: Download Kali Linux
Go to the Kali Linux Get Page.

Choose the VirtualBox image under the "Virtual Machines" section.

Download the .7z file and extract it using software like 7-Zip.

🖥️ Step 3: Import Kali Linux into VirtualBox
Open VirtualBox and click File > Import Appliance.

Select the extracted .ova or .vbox file.

Follow the prompts to import the virtual machine.

Adjust settings like RAM (at least 2GB recommended) and network adapter (use NAT or Host-only for isolation).

🔐 Step 4: Start Kali Linux
Launch the Kali VM from VirtualBox.

Default username: kali

Default password: kali

Update the system using:

bash
sudo apt update && sudo apt upgrade -y
🧪 Why Use a Virtual Lab?
Safe environment to test tools and techniques.

No risk to your host system or public networks.

Ideal for learning penetration testing, vulnerability scanning, and digital forensics.
