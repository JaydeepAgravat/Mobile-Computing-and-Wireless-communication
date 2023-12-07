# UNIT-3

## 1. Draw and explain GSM architecture

The GSM (Global System for Mobile Communications) architecture consists of several key components:

![GSM Architecture](https://i.imgur.com/U9Kufb6.png)

- **Mobile Station (MS):**
  - Represents the mobile device (phone) used by the subscriber.

- **Base Station Subsystem (BSS):**
  - **Base Transceiver Station (BTS):** Controls the radio link with the Mobile Station and handles radio protocols.
  - **Base Station Controller (BSC):** Manages multiple BTS and performs handovers.

- **Network Switching Subsystem (NSS):**
  - **Mobile Switching Center (MSC):** Connects calls, manages call location updates, and handovers.
  - **Home Location Register (HLR):** Stores subscriber information and current locations.
  - **Visitor Location Register (VLR):** Temporary storage for subscriber information within a specific location area.

- **Authentication Center (AUC):**
  - Verifies the identity of the subscriber.

- **Equipment Identity Register (EIR):**
  - Manages a list of valid mobile equipment on the network.

- **Operation and Maintenance Center (OMC):**
  - Monitors and controls the network elements.

## 2. Show the use of below GSM Identifiers.i) IMEI ii) IMSI iii) MSISDN iv) MSRN

- **IMEI (International Mobile Equipment Identity):**
  - A unique identifier for mobile devices.
  - Used to block stolen phones.

- **IMSI (International Mobile Subscriber Identity):**
  - Identifies the subscriber in the network.
  - Stored in the SIM card.

- **MSISDN (Mobile Station International Subscriber Directory Number):**
  - The telephone number of the subscriber.
  - What we commonly know as the phone number.

- **MSRN (Mobile Subscriber Roaming Number):**
  - Used during call setup to route calls to the subscriber.

## 3. Illustrate different scenarios of Roaming and Handoff in GSM with proper Examples. OR Explain GSM call routing

- **Roaming:**
  - **Scenario 1: Home Network Call:**
    - A subscriber makes a call within their home network.
  - **Scenario 2: Visited Network Call:**
    - A subscriber makes a call in a different network (visited), and the VLR communicates with the HLR for subscriber information.

- **Handoff:**
  - **Scenario 1: Intra-BSC Handoff:**
    - A mobile device moves between cells controlled by the same BSC.
  - **Scenario 2: Inter-BSC Handoff:**
    - A mobile device moves between cells controlled by different BSCs but within the same MSC.
  - **Scenario 3: Inter-MSC Handoff:**
    - A mobile device moves between cells controlled by different MSCs.

## 4. Compare GSM and CDMA technology

| Feature                   | GSM                                | CDMA                                     |
|---------------------------|------------------------------------|------------------------------------------|
| **Multiple Access Scheme** | Time Division Multiple Access (TDMA) | Code Division Multiple Access (CDMA)     |
| **Subscriber Identity**   | Uses SIM cards for subscriber info  | Subscriber identity embedded in the device|
| **Network Architecture**  | Cell-based architecture            | Cell-based architecture                  |
| **Handset Compatibility** | Easier to switch between handsets   | Handsets tied to specific carriers        |
| **Global Adoption**       | Widespread globally                | Dominant in North America and some areas  |
| **Interference**          | Susceptible to interference         | More resistant to interference           |

## 5. Explain the functional architecture of the GSM system and types of services provided by GSM

The GSM functional architecture includes:

- **Mobile Equipment (ME):**
  - The physical device used by the subscriber.

- **Subscriber Identity Module (SIM):**
  - Contains the subscriber's information.

- **Base Station Subsystem (BSS):**
  - Manages radio communication.

- **Network Switching Subsystem (NSS):**
  - Handles call switching, registration, and handovers.

- **GSM Services:**
  - Telephony, SMS, Data Services, Supplementary Services (call waiting, conference calling, etc.).

This architecture ensures seamless communication, mobility, and a variety of services for GSM subscribers.

## 6. Explain the handover process in the cellular system

The handover process in cellular systems, including GSM, involves transferring an ongoing call or data session from one cell to another to maintain seamless communication. The process typically consists of the following steps:

1. **Measurement:**
   - The mobile station continuously measures the signal strength and quality of neighboring cells.

2. **Triggering:**
   - When the signal strength of the current cell falls below a certain threshold or the quality degrades, a handover is triggered.

3. **Selection:**
   - The mobile station and the network select a target cell for the handover based on measured parameters and network policies.

4. **Initiation:**
   - The network initiates the handover, informing both the source and target cells about the upcoming transfer.

5. **Preparation:**
   - Resources in the target cell are prepared for the handover.

6. **Execution:**
   - The handover is executed, and the communication is transferred from the source to the target cell.

7. **Verification:**
   - The network verifies the success of the handover and adjusts parameters if necessary.

8. **Completion:**
   - The handover process is completed, and the communication continues in the target cell.

## 7. Explain the purpose of the Home Location Register (HLR). List the information stored in the Home Location Register (HLR)

**Purpose:**

- The HLR is a database used for storage and management of subscriber information within a GSM network.

**Information Stored in HLR:**

1. **Subscriber Identity:** IMSI (International Mobile Subscriber Identity).
2. **Subscriber Services:** Services subscribed by the user (e.g., call forwarding, call waiting).
3. **Location Information:** Current VLR (Visitor Location Register) where the subscriber is registered.
4. **Authentication Key:** Used for secure communication between the mobile device and the network.
5. **Subscriber State:** Whether the subscriber is reachable, unreachable, or busy.
6. **Supplementary Services Information:** Information related to additional services.

## 8. Explain Addresses and Identifiers used in GSM with Example

- **International Mobile Equipment Identity (IMEI):**
  - Unique identifier for mobile devices.
  - Example: 123456789012345

- **International Mobile Subscriber Identity (IMSI):**
  - Identifies the subscriber in the network.
  - Example: 310150123456789

- **Mobile Station ISDN Number (MSISDN):**
  - The phone number of the subscriber.
  - Example: +1234567890

- **Mobile Subscriber Roaming Number (MSRN):**
  - Used during call setup to route calls to the subscriber.
  - Example: 9876543210

## 9. Discuss the network elements in GPRS that are different from GSM. Also, discuss applications and limitations of GPRS

**Different Network Elements in GPRS:**

1. **Serving GPRS Support Node (SGSN):**
   - Manages the delivery of data packets.
2. **Gateway GPRS Support Node (GGSN):**
   - Interfaces between the GPRS network and external packet-switched networks.
3. **GPRS Support Nodes (GSN):**
   - Generic term for SGSN and GGSN.

**Applications:**

- **Internet Browsing:** Accessing the internet on mobile devices.
- **Email:** Sending and receiving emails.
- **Instant Messaging:** Real-time text communication.
- **Location-Based Services:** Utilizing location information for various applications.

**Limitations:**

- **Limited Speeds:** Slower compared to modern 4G and 5G networks.
- **Packet Loss:** GPRS may experience packet loss, affecting data transmission.
- **Limited Capacity:** Limited compared to newer technologies, leading to potential congestion.

## 10. Draw and explain the GPRS transmission plane protocol model

The GPRS Transmission Plane Protocol Model includes the following protocols:

1. **Subnetwork Dependent Convergence Protocol (SNDCP):**
   - Handles protocol conversion and compression.

2. **Logical Link Control (LLC):**
   - Provides a reliable link between the mobile station and the network.

3. **Base Station Subsystem GPRS Protocol (BSSGP):**
   - Manages the delivery of user data between the SGSN and the BSS.

4. **Mobile Station - Base Station Subsystem Protocol (MS-BSSGP):**
   - Ensures the integrity and sequence of data during transmission.

5. **Radio Link Control (RLC):**
   - Manages error correction and retransmission on the radio link.

6. **Radio Resource Control (RRC):**
   - Controls radio resources, including allocation and release.

This model ensures the efficient and reliable transmission of data in the GPRS network.

## 11. List and explain the functionality of Serving GPRS Support Node (SGSN) and Gateway GPRS Support Node (GGSN)

Serving GPRS Support Node (SGSN):

1. **Mobility Management:**
   - Manages the location update and tracking of mobile stations.

2. **Session Management:**
   - Establishes, maintains, and releases sessions for data transfer.

3. **Authentication and Authorization:**
   - Authenticates users and authorizes data sessions.

4. **Ciphering and Compression:**
   - Ensures secure data transmission by implementing ciphering and compression.

5. **Error Handling and Recovery:**
   - Handles errors and ensures reliable data transfer.

6. **Charging and Billing Data Collection:**
   - Collects charging and billing data related to the usage of GPRS services.

7. **Interfacing with Home Location Register (HLR):**
   - Communicates with the HLR for subscriber information.

Gateway GPRS Support Node (GGSN):

1. **Interface with External Networks:**
   - Interfaces with external packet-switched networks, such as the internet.

2. **IP Address Assignment:**
   - Assigns IP addresses to mobile stations for data communication.

3. **Packet Routing:**
   - Routes data packets from the SGSN to the appropriate external network.

4. **Charging and Billing Functions:**
   - Handles charging and billing functions related to external data transfer.

5. **Mobility Management with External Networks:**
   - Manages mobility when a mobile station moves between different external networks.

6. **Security:**
   - Implements security measures to protect data during transmission.

## 12. Explain Voice and Data Routing in GPRS with a proper diagram

**Voice Routing:**

- Traditional voice calls are routed through the circuit-switched network (using GSM).
- GPRS is primarily designed for packet-switched data services, and voice calls are handled separately.

**Data Routing:**

1. **Data Packet Transmission:**
   - User data is divided into packets and transmitted through the GPRS network.

2. **SGSN Routing:**
   - SGSN routes the data packets based on the destination address.

3. **GGSN Routing:**
   - GGSN acts as a gateway between the GPRS network and external packet-switched networks (e.g., the internet).

4. **External Network Communication:**
   - GGSN routes the data packets to the appropriate external network based on the destination IP address.

5. **Return Path:**
   - The return path follows a similar route in reverse, with GGSN directing packets back to the SGSN and eventually to the mobile station.

![GPRS Routing Diagram](https://i.imgur.com/srHMwFv.png)

## 13. Discuss briefly: Limitations of GPRS

1. **Limited Speeds:**
   - GPRS offers slower data transfer rates compared to modern technologies like 4G and 5G.

2. **Packet Loss:**
   - GPRS may experience packet loss, affecting the quality of data transmission.

3. **Limited Capacity:**
   - Limited capacity, leading to potential congestion in densely populated areas.

4. **Technology Aging:**
   - GPRS is an older technology, and the infrastructure may not support the demands of modern applications.

## 14. How billing and charging functions are handled in GPRS

1. **Charging for Data Volume:**
   - Users are charged based on the volume of data transferred, typically measured in kilobytes or megabytes.

2. **Charging for Time:**
   - Users may be charged based on the duration of their GPRS session.

3. **Event-Based Charging:**
   - Charging may occur based on specific events, such as the initiation or termination of a data session.

4. **Roaming Charges:**
   - Additional charges may apply when users access GPRS services while roaming in a different network.

5. **Billing Integration:**
   - GPRS charging and billing information is integrated with the overall mobile network billing system.

6. **Prepaid and Postpaid Options:**
   - Users may have the option for prepaid or postpaid billing, depending on their subscription plans.

Billing and charging systems play a crucial role in managing the costs associated with GPRS services and ensuring accurate billing for users.
