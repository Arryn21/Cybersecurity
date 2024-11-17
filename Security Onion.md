# Installing Security Onion on Cloud (Digital Ocean - Droplets)

Setting up Security Onion on a Debian system

to update the repo list
> apt update

for downloading image of security onion
> wget https://download.securityonion.net/file/securityonion/securityonion-2.4.110-20241010.iso

find so-setup-network and run it
> ./so-setup-network

![continue to install](https://github.com/user-attachments/assets/e3368060-8591-44b3-9c99-68134d26cbfe)

![after allowing installation](https://github.com/user-attachments/assets/bba5a0fb-5e03-47ea-8eab-1c058da1480c)

Import - this mode is used to forensically analyze pcap and log files (we have selected this mode)

Evaluation - This is ideal for class or lab work and not designed for the production usage

Standalone - This is similar to evaluation mode but it is more ready for the producation usage
![installation mode](https://github.com/user-attachments/assets/ab8f869e-9186-45b5-bc91-c02dc32c00d2)

Enter the hostname (you can keep the same hostname or you can change it)
![hostname](https://github.com/user-attachments/assets/38cc03a9-5224-403e-b751-8cb4b38a7a57)

![setting configuration](https://github.com/user-attachments/assets/a3d95a28-2f82-49ef-835e-0ccfb50d8fdc)

![DHCP StaticIP waring](https://github.com/user-attachments/assets/8339b74b-5254-43c9-885c-47e96e29585a)

after this select the NIC card in terminal run command 
> ip a
and based on that select the NIC card

![nic card selection](https://github.com/user-attachments/assets/e01fc001-18be-46d7-b010-464dcc937847)




