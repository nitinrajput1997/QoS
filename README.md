# QoS

![](/photos/QoS.png)

It is the technology that manages the data trafficc to achieve the desired performance.

5G uses QoS Flows (QFI) to make it performance better in different data traffic.

QFI provides different Flow ID to each services so that each services has difference between them and does not affect each other services through which they will achieve the desired performance.

***Radio Bearer*** - They are used only for the transmission of RRC and NAS messages.

***N3 tunnel***    - All QoS Flows of a UE is bundled inside a N3 GTP-U tunnel between the gNB and the UPF in a 5G core network.

 #### Types of QoS Flow
 
 1. GBR :- This is used in application which rrequires guaranteed bit rate.
 
 2. Non-GBR :- This is used for the traffic having bursty in nature.
 
 3. Delay Critical :- This is used for the mission critical application. 
