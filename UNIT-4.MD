# UNIT-4

## 1. Draw and explain IEEE 802.11 Architecture and its Services

IEEE 802.11 is a set of standards for implementing wireless local area networking (WLAN) communication. It is commonly known as Wi-Fi. The IEEE 802.11 architecture defines the framework and services for wireless communication. Let's break down the architecture and services of IEEE 802.11:

IEEE 802.11 Architecture:

1. **Station (STA):**
   - A Station is a device that has the capability to use the IEEE 802.11 protocol. It can be a laptop, smartphone, tablet, or any device that supports Wi-Fi.

2. **Basic Service Set (BSS):**
   - BSS is the basic building block of an IEEE 802.11 wireless LAN. It can be either Independent BSS (IBSS) or Infrastructure BSS.

   - **Independent BSS (IBSS):**
     - Also known as ad-hoc mode.
     - In IBSS, stations communicate directly with each other without the need for an access point (AP).

   - **Infrastructure BSS:**
     - In this mode, stations communicate through an access point (AP).
     - The AP acts as a central hub for coordinating communication between stations.

3. **Extended Service Set (ESS):**
   - ESS is a set of interconnected BSSs. It allows users to roam seamlessly between different APs within the same network.

4. **Distribution System (DS):**
   - DS connects a set of BSSs to form an ESS. It provides the infrastructure for inter-BSS communication.

5. **Access Point (AP):**
   - An access point is a networking hardware device that allows a Wi-Fi device to connect to a wired network. It bridges the wireless and wired networks.

6. **Wireless Distribution System (WDS):**
   - WDS allows wireless interconnection of APs to extend the coverage area of a network.

7. **Independent Basic Service Set (IBSS):**
   - This is the term used for an ad-hoc network where devices communicate directly with each other without the need for an AP.

IEEE 802.11 Services:

1. **Station Services:**
   - Association and disassociation of stations with a BSS.
   - Reassociation of stations, allowing for seamless roaming.
   - Distribution of association-related information.

2. **Distribution Services:**
   - Forwarding of data frames between stations within the same BSS or between BSSs.
   - Integration of an IEEE 802.11 network with a distribution system (DS).

3. **Integration Services:**
   - Connection of an IEEE 802.11 network to a wired LAN.
   - The ability to provide end-to-end delivery of data frames.

4. **Privacy and Security Services:**
   - Authentication and deauthentication of stations.
   - Privacy and security mechanisms, including encryption and key management.

5. **Automatic Channel Selection:**
   - Mechanisms for selecting and changing channels to optimize network performance.

6. **Load Balancing:**
   - Distributing the load among APs to avoid congestion and optimize resource utilization.

IEEE 802.11 standards continue to evolve with new amendments and improvements, providing faster and more reliable wireless communication. Understanding the architecture and services is crucial for designing and managing efficient wireless networks.

## 2. Compare Wi fi and Wi Max

| Feature               | Wi-Fi                                          | WiMAX                                         |
|-----------------------|------------------------------------------------|-----------------------------------------------|
| **Definition**        | Wireless LAN technology, used for local access  | Wireless broadband technology, for long-range |
| **Standard**          | IEEE 802.11 family                             | IEEE 802.16 family                            |
| **Range**             | Short-range (typically up to 100 meters)       | Long-range (up to 50 km in optimal conditions)|
| **Frequency Bands**   | 2.4 GHz and 5 GHz bands (varies by standard)   | 2-66 GHz bands (varies by standard)           |
| **Topology**          | Point-to-Point and Point-to-Multipoint         | Point-to-Multipoint                           |
| **Data Rates**        | Varies (typically from 1 Mbps to several Gbps) | Varies (typically from 1 Mbps to 1 Gbps)      |
| **Modulation**        | OFDM, DSSS, FHSS, etc.                         | OFDM, QPSK, 16-QAM, 64-QAM, etc.              |
| **Mobility Support**  | High mobility support with roaming             | Supports mobility with handovers             |
| **Deployment**        | Localized (homes, offices, hotspots)           | Wide-area coverage (metropolitan, rural)      |
| **Typical Applications**| Home and enterprise networking, hotspots      | Broadband internet access, backhaul          |
| **Interference**      | Susceptible to interference in crowded areas   | Less susceptible to interference              |
| **QoS Support**       | Supports QoS but can vary in implementations  | Better support for QoS                       |
| **Security**          | WEP, WPA, WPA2, WPA3                           | Supports advanced security features         |
| **Scalability**       | Limited scalability for large areas            | Scalable for large coverage areas             |
| **Backward Compatibility** | Generally backward compatible            | Dependent on the specific standard adopted   |
| **Cost**              | Lower infrastructure cost, suitable for homes | Higher infrastructure cost, suitable for ISPs|
| **Popularity**        | Ubiquitous, widely used globally               | Less widespread, more in specific deployments|
