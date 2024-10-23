```markdown
  (  (_)        /    .-._.   .-.       /       .-._.   .-.  
   `-.         /    (   )    /  )     /       (   )    /  ) 
 _    )      _/_.-   `-'    /`-'   .-/._       `-'    /`-'  
(_.--'                     /      (_/  `-            /      
```


## SlopTop

Welcome to SlopTop—your secure workstation designed for private browsing and managing Litecoin. This guide will walk you through setting up your system for a safe and anonymous experience.

For any questions and concerns, don't hesitate to reach out.

raposo.ryan@gmail.com
- Pre-configured
- BYOM (Bring Your Own Machine)
- Support

Everything is negotiable.

<a href="https://www.buymeacoffee.com/ryanraposo" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 40px; width: 150px;" >
</a>

---

### Table of Contents

1. Overview
2. Getting Started
3. Setting Up Whonix
4. Using Tor Safely
5. Managing Litecoin
6. Good Practices
7. Shutting Down Properly
8. Need Help?

### 1. Overview

Your workstation includes:

- **Ubuntu MATE**: The main operating system.
- **Whonix**: A secure environment utilizing Tor for anonymous internet access.
- **Whonix-Gateway**: Connects to the Tor network.
- **Whonix-Workstation**: For secure browsing and Litecoin management.
- **Electrum-LTC Wallet**: A secure wallet for Litecoin transactions.

### 2. Getting Started

#### First-Time Setup

1. **Power On the Laptop**
   - Press the power button to start.
2. **Log into Ubuntu MATE**
   - Username: `user`
   - Password: `changeme`
3. **Change Your Passwords**
   - **For Ubuntu MATE:**
     - Open the Terminal (black screen icon).
     - Type `passwd` and press Enter.
     - Follow prompts to set a new password.
   - **For Whonix VMs:**
     - You'll change these later during Whonix setup.

### 3. Setting Up Whonix

#### Start the Secure Environment

1. **Open VirtualBox**
   - Click on the VirtualBox icon or find it in the applications menu.
2. **Launch Whonix-Gateway**
   - In VirtualBox, double-click **Whonix-Gateway**.
3. **Launch Whonix-Workstation**
   - Once the gateway is running, double-click **Whonix-Workstation**.

#### Logging into Whonix

- Username: `user`
- Password: `changeme`

#### Change Passwords in Whonix

1. Open the Terminal in both **Whonix-Gateway** and **Whonix-Workstation**.
2. Type `passwd` and press Enter.
3. Set new, strong passwords for both.

### 4. Using Tor Safely

#### Browsing Anonymously

1. **Open Tor Browser**
   - Inside **Whonix-Workstation**, click on the Tor Browser icon.
2. **Safe Browsing Tips**
   - Avoid logging into personal accounts.
   - Do not share personal information.
   - Use the browser only for activities requiring anonymity.

### 5. Managing Litecoin

#### Setting Up Electrum-LTC Wallet

1. **Open Electrum-LTC**
   - Find it in the applications menu within **Whonix-Workstation**.
2. **Create a New Wallet**
   - Follow the on-screen instructions.
3. **Backup Your Seed Phrase**
   - Write down the 12-word recovery phrase on paper.
   - Store it in a safe place—do not save it on the computer.
4. **Set a Strong Password**
   - Use a mix of letters, numbers, and symbols.

#### Making Transactions

- **Receiving Litecoin**
  - Click on the **Receive** tab to get your wallet address.
- **Sending Litecoin**
  - Use the **Send** tab.
  - Double-check all addresses before sending.

### 6. Good Practices

#### Security First

- **Keep Passwords Secure**
  - Use unique passwords for each account.
  - Consider using a password manager like KeePassXC.
- **Regular Updates**
  - **Ubuntu MATE:**
    - Open **Software Updater** to install updates.
  - **Whonix:**
    - Updates are prompted automatically; follow the instructions.

#### Protect Your Privacy

- **Stay Anonymous**
  - Don't mix personal and anonymous activities.
  - Use this workstation only for private tasks.
- **Physical Security**
  - Keep your laptop in a safe place.
  - Be cautious when using public Wi-Fi.

#### Safe Internet Use

- **Avoid Suspicious Links**
  - Don't click on unknown links or download untrusted files.
- **Use Trusted Sources**
  - Only download software from official websites.

### 7. Shutting Down Properly

1. **Close Applications**
   - Exit all programs in **Whonix-Workstation**.
2. **Shut Down Whonix VMs**
   - In VirtualBox, select each VM.
   - Choose **Close > Power Off**.
3. **Shut Down Ubuntu MATE**
   - Click the power icon.
   - Select **Shut Down**.

### 8. Need Help?

- **Whonix Support:** [whonix.org/wiki/Support](https://www.whonix.org/wiki/Support)
- **Electrum-LTC Help:** [electrum-ltc.org](https://electrum-ltc.org)
- **Tor Project:** [torproject.org](https://www.torproject.org)

Keep this guide handy for top-to-bottom SlopTop excellence. Get yours today!

### Quick Reference Guide

#### A. Initial Setup Steps

1. **Power On and Log In**
   - Username: `user`
   - Password: `changeme`
   - **Change Passwords Immediately** using the `passwd` command in the terminal.
2. **Start Whonix Virtual Machines**
   - Open **VirtualBox**.
   - Start **Whonix-Gateway** first.
   - Then start **Whonix-Workstation**.
3. **Update Systems**
   - **Ubuntu MATE:**
     - Open **Software Updater** and install updates.
   - **Whonix VMs:**
     - Follow on-screen prompts to update upon startup.
4. **Set Up Electrum-LTC Wallet**
   - Open **Electrum-LTC** in **Whonix-Workstation**.
   - Create a new wallet and backup your seed phrase.
   - Set a strong password.

#### B. Good Practices

1. **Security**

   - **Passwords**
     - Use strong, unique passwords.
     - Consider a password manager like KeePassXC.
   - **Seed Phrase**
     - Write it down and store it securely offline.
   - **System Updates**
     - Regularly update all software.

2. **Privacy**

   - **Separate Activities**
     - Use this workstation solely for private tasks.
   - **Anonymity**
     - Do not reveal personal information while using Tor.

3. **Safe Browsing**

   - **Tor Browser**
     - Use for all internet activities within Whonix.
   - **Avoid Plugins/Add-ons**
     - Stick to default browser settings.

4. **Physical Security**

   - **Secure Storage**
     - Keep the laptop in a safe place when not in use.
   - **Trusted Networks**
     - Connect only to secure Wi-Fi networks.

#### C. Troubleshooting Tips

- **Internet Connection Issues**
  - Restart **Whonix-Gateway** and **Whonix-Workstation**.
- **Software Problems**
  - Check official documentation or support forums.

#### D. Contact for Assistance

- **Technical Support:** [Your Contact Information]
- **Useful Resources:**
  - **Whonix:** [whonix.org](https://www.whonix.org)
  - **Electrum-LTC:** [electrum-ltc.org](https://electrum-ltc.org)
  - **Tor Project:** [torproject.org](https://www.torproject.org)

Keep this guide handy for top-to-bottom SlopTop excellence.

For any questions and concerns, don't hesitate to reach out.

---

raposo.ryan@gmail.com
- Pre-configured
- BYOM (Bring Your Own Machine)
- Support

Everything is negotiable.
