# Firewall-Lab
Build and Configure a Firewall

## Objective

The Firewall Lab project aimed to build and configure a Firewall to protect a network from unauthorized access and potential threats. In this lab, we set up and configured a firewall on an Ubuntu system using UFW (Uncomplicated Firewall)

### Skills Learned

- Understanding of how to set up and configure a firewall.
- Allowing and denying traffic through protocols, ports, or IP addresses.
- Setting default policies for incoming and outgoing traffic.

### Tools Used

- UFW (Uncomplicated Firewall) on an Ubuntu system.

## Steps

Step 1: First, I ensure my system is up to date by using the apt update and the apt upgrade command. 
<img width="698" height="200" alt="Screenshot 2024-12-07 at 10 49 37 PM" src="https://github.com/user-attachments/assets/a7f0a432-5dd4-4f62-ac27-02192cac3227">
<img width="698" height="200" alt="Screenshot 2024-12-07 at 10 53 05 PM" src="https://github.com/user-attachments/assets/d086ad93-7ee7-45d6-b90a-c1c2cc48fdbc">

Step 2: Then install UFW.

<img width="698" height="200" alt="Screenshot 2024-12-07 at 10 57 55 PM" src="https://github.com/user-attachments/assets/bfbddc88-3b99-49f5-963d-a818577822da">


Step 3: Enable UFW.

<img width="698" alt="Screenshot 2024-12-07 at 11 00 24 PM" src="https://github.com/user-attachments/assets/5d9bbe0d-827f-4486-8ec7-408265c617ce">

Step 4: I can now configure the UFW; for example, I can allow or deny SSH connections.

<img width="698"  alt="Screenshot 2024-12-07 at 11 07 00 PM" src="https://github.com/user-attachments/assets/dc5171d3-c5cb-48ae-8144-08164560db79">

Allow or deny HTTP and HTTPS traffic.

<img width="698"  alt="Screenshot 2024-12-07 at 11 12 17 PM" src="https://github.com/user-attachments/assets/8ff3cbee-9b4e-401f-9f3c-28b245ed300c">

Allow or deny specific ports or a range of ports.

<img width="698" alt="Screenshot 2024-12-07 at 11 21 32 PM" src="https://github.com/user-attachments/assets/58e5f9ae-9fcc-4e54-85c4-0a35198d129e">
<img width="698" alt="Screenshot 2024-12-07 at 11 25 05 PM" src="https://github.com/user-attachments/assets/fb773280-b8c5-4f83-b65b-6e5b4ca3d432">

Allow or deny specific IP addresses.

<img width="698"  alt="Screenshot 2024-12-07 at 11 32 21 PM" src="https://github.com/user-attachments/assets/dca67e4b-5b82-4ede-a905-5616b9afc693">

Allow or deny specific subnets.

<img width="698" alt="Screenshot 2024-12-07 at 11 34 00 PM" src="https://github.com/user-attachments/assets/3863dbcb-e876-4899-af5c-70f92f187b6e">
        
Step 5: View UFW status and rules.

<img width="698" alt="Screenshot 2024-12-07 at 11 47 54 PM" src="https://github.com/user-attachments/assets/0ab61143-c38f-4dcc-9c02-4d95ec24451d">
<img width="698" alt="Screenshot 2024-12-07 at 11 49 53 PM" src="https://github.com/user-attachments/assets/6bed269e-77a6-4b1e-9560-fc332b161165">

Step 6: Set the default policy to allow or deny.

<img width="698" alt="Screenshot 2024-12-08 at 12 10 08 AM" src="https://github.com/user-attachments/assets/78dcf435-3895-44db-bdc2-d145d50f3a9a">
<img width="698" alt="Screenshot 2024-12-08 at 12 08 46 AM" src="https://github.com/user-attachments/assets/887b2ee5-6313-4550-b106-6902548aaddb">


Step 7: View the application policy list.

<img width="698" alt="Screenshot 2024-12-08 at 12 15 36 AM" src="https://github.com/user-attachments/assets/72fb3ac3-7bf6-4c9a-b373-298d387d6a59">

Step 8: Tesing the Firewall, check for open ports by using nmap from a different machine.

![Screenshot 2024-12-14 182803](https://github.com/user-attachments/assets/078d383a-dbd3-4630-a9c6-3952c56e3d5d)

![Screenshot 2024-12-14 182848](https://github.com/user-attachments/assets/cb7c4e62-6587-4ed9-99e2-a41b98dd2e25)

![Screenshot 2024-12-14 182927](https://github.com/user-attachments/assets/239ea71c-169e-4e85-9d7e-5d7f0cc4a7d0)

Step 9: Observe open ports.

![Screenshot 2024-12-14 184920](https://github.com/user-attachments/assets/9efdfc06-f867-4d5d-8c2c-e42ff0592994)
        
Step 10: Change setting to close open port.

<img width="571" alt="Screenshot 2024-12-14 at 6 46 39 PM" src="https://github.com/user-attachments/assets/f6372664-78b7-45e8-b7cb-b9021fd593a2" />

Step 11: Observe the updated open ports.

![Screenshot 2024-12-14 184954](https://github.com/user-attachments/assets/f4efd773-49ae-49b2-a00f-a81dda405710)

In conclusion, this was a successful set up and configuration of a firewall on a Ubuntu system using UFW. This setup will help protect a network from unauthorized access and potential threats. 
