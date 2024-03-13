# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.

## ALGORITHM:

## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.

   
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.


## PROGRAM - ARP
![Screenshot 2024-03-13 113403](https://github.com/tharunkumaran2006/2c.ARP_RARP_PROTOCOLS/assets/151625188/3f99903b-f3b4-4c47-ae63-ec8e26c0b45b)

## OUTPUT - ARP
  ![Screenshot 2024-03-13 113431](https://github.com/tharunkumaran2006/2c.ARP_RARP_PROTOCOLS/assets/151625188/2b6ccf58-b06d-43e5-b8de-3436dc85bd05)

## PROGRAM - RARP
![Screenshot 2024-03-13 113410](https://github.com/tharunkumaran2006/2c.ARP_RARP_PROTOCOLS/assets/151625188/d40737b2-3b9d-4d05-90f8-46c236d4397f)

## OUTPUT -RARP
![Screenshot 2024-03-13 113440](https://github.com/tharunkumaran2006/2c.ARP_RARP_PROTOCOLS/assets/151625188/81721af4-db39-4519-8391-4507dfc4f34f)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
