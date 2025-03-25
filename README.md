# Electronic-Voting-Machine-using-8051-Microcontroller
This project is an Electronic Voting Machine (EVM) designed using the 8051 microcontroller to ensure a secure, reliable, and efficient voting process. The system allows users to cast votes through push buttons, display results in real-time on an LCD screen, and reset the system after each voting session.

---

## Key Features 
- **Secure Voting Process:** Prevents multiple votes using an initializing switch
- **Real-Time Display:** Displays voting status and results instantly on the LCD
- **Easy to Use:** Simple push-button interface for casting and tallying votes
- **Efficient Assembly Code:** Optimized for speed and low memory footprint
- **Reset Capability:** Allows quick clearing of votes for the next session

---

## **Novelty**
A key innovation in this project is the **"Initializing Switch"**, which prevents **multiple votes** from being counted due to **accidental or rapid inputs**. This ensures **each vote is counted accurately and securely**, setting this system apart from conventional EVM designs.

---

## Components and Software Required

### Hardware Components:

| S.No | Component                  | Quantity |
|------|----------------------------|----------|
| 1    | Aryabhatta 8051 Microcontroller | 1        |
| 2    | LCD Display                 | 1        |
| 3    | Push Buttons                | 6        |
| 4    | Resistor (1K Ohm)           | 1        |
| 5    | Potentiometer               | 1        |
| 6    | Jumper Wires                | -        |
| 7    | Breadboard                  | 1        |


### **Software Tools**
- **Keil uVision** (For Assembly programming and debugging)  
- **Proteus** (For circuit simulation)  
- **Flash Magic** (For microcontroller programming)  )

---

## Block Diagram:
![image](https://github.com/user-attachments/assets/d9b200bd-df24-4572-8366-e6284fb1f6a0)

---

## Algorithm:

![image](https://github.com/user-attachments/assets/452f207f-daa1-4add-90cb-fb640f7f05c3)

---

## Schematic (Proteus Simulation)
The **8051 microcontroller** ports are configured as follows:
| Port | Function |
|------|------------------------------------------------|
| **Port 1 (P1.x)** | Push buttons for party selection |
| **Port 2 (P2.x)** | LCD data lines |
| **Port 3 (P3.0 - P3.2)** | LCD control lines |
| **VCC & GND** | Power supply connections |

### Schematic using Proteus Simulation:
![image](https://github.com/user-attachments/assets/559928df-0d23-4fdd-ae65-ab96c6ed56e9)

---

## Hardware Implementation
The hardware setup includes:
- **Aryabhatta 8051 Microcontroller Board** (Central unit for handling operations)  
- **LCD Display** (Shows voting prompts and results)  
- **Switches** (For user input and system control)  
- **Breadboard and Jumper Wires** (For circuit assembly)  
- **Potentiometer and Resistor** (To optimize LCD performance)  

### Hardware Setup:
![image](https://github.com/user-attachments/assets/5b024cf8-9687-48bd-b786-c7020f3e2f26)




