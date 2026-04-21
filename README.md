# ConfiguringStaticRouting

Building and Configuring Static Routing

In this lab I configure static routing in my network topology which helps with security by not advertising routes over the network.
  
<img width="614" height="409" alt="image" src="https://github.com/user-attachments/assets/8939077e-2e64-4b7e-a8d1-76b2e606fdde" />

RA configurations

<img width="717" height="475" alt="image" src="https://github.com/user-attachments/assets/3e3e146b-1b71-4fde-948f-09c4403006c2" />
 

PodA Configurations

 <img width="866" height="584" alt="image" src="https://github.com/user-attachments/assets/8fd48e2c-0805-4c51-8d90-3580ee0648ff" />


RB Configurations 

<img width="722" height="651" alt="image" src="https://github.com/user-attachments/assets/bae6e0ec-01cb-4751-88bc-f9b9dceb54a1" />
 

PodB Configurations

 <img width="873" height="583" alt="image" src="https://github.com/user-attachments/assets/03979cb5-8f60-4a62-9b4b-1136addcd9f8" />


RC Configurations

 <img width="873" height="568" alt="image" src="https://github.com/user-attachments/assets/7098c09e-d08b-404c-8e0e-f5ba0d294a51" />



I then viewed the routing tables for the routers using the sh ip route command

RA route table

<img width="768" height="481" alt="image" src="https://github.com/user-attachments/assets/07ccafd8-c176-41e3-a949-89639e314492" />
 

PodA route table

 <img width="629" height="526" alt="image" src="https://github.com/user-attachments/assets/52e5b41c-00bf-484d-a154-0e34e85341ca" />


RB route table

 <img width="624" height="542" alt="image" src="https://github.com/user-attachments/assets/2613c9b1-c816-40fe-9446-a787cb874e13" />


PodB route table

 <img width="662" height="618" alt="image" src="https://github.com/user-attachments/assets/df8b9fb8-ec9a-485a-83fb-00c602cd4803" />


RC route table

 <img width="754" height="703" alt="image" src="https://github.com/user-attachments/assets/2fafd76e-a2f4-4d2e-a030-d8c871ada830" />

 
When trying to ping between two nodes I got request timed out responses

 <img width="996" height="578" alt="image" src="https://github.com/user-attachments/assets/69886d4d-ff21-43b1-9c84-af0caa451c69" />

