# UNIT-5

## 1. Bluetooth Protocol Architecture:

The Bluetooth protocol architecture consists of several layers:

1. **Radio Layer:**
   - The lowest layer that defines the physical layer for Bluetooth communication.
   - Handles frequency hopping and modulation techniques.

2. **Baseband Layer:**
   - Manages the physical channels and link types.
   - Handles packet formatting, error detection, and correction.

3. **Link Manager Protocol (LMP):**
   - Responsible for link setup, authentication, encryption, and link management.
   - Manages power control and quality of service.

4. **Logical Link Control and Adaptation Protocol (L2CAP):**
   - Responsible for multiplexing and segmentation of data.
   - Provides protocol multiplexing and segmentation/ reassembly for upper-layer protocols.

5. **RFCOMM (Radio Frequency Communication):**
   - Emulates RS-232 serial ports, enabling legacy applications to run over Bluetooth.

6. **Service Discovery Protocol (SDP):**
   - Used for discovering available services on a Bluetooth device.

7. **Telephony Control Protocol (TCS):**
   - Supports telephony control functions for Bluetooth applications.

![Bluetooth Protocol Architecture](https://i.imgur.com/GwW37VC.png)

## 2. L2CAP Protocol of Bluetooth:

**L2CAP (Logical Link Control and Adaptation Protocol):**

- Provides both connection-oriented and connectionless services to upper-layer protocols.
- Key features include segmentation and reassembly, Quality of Service (QoS), and protocol multiplexing.

## 3. Power-Saving States of a Bluetooth Device:

Bluetooth devices have different power-saving states:

1. **Active Mode:**
   - The device is actively communicating and consuming power at the maximum rate.

2. **Sniff Mode:**
   - The device reduces its activity, periodically waking up to check for incoming data.
   - Consumes less power compared to active mode.

3. **Hold Mode:**
   - The device temporarily puts the connection on hold, consuming minimal power.
   - Useful for conserving power during short periods of inactivity.

4. **Park Mode:**
   - The device temporarily relinquishes its connection slot.
   - Consumes the least power but takes longer to re-establish communication.

## 4. Bluetooth Protocol Stack Layers:

The Bluetooth protocol stack consists of the following layers:

1. **Radio Layer:**
   - Defines the physical layer for Bluetooth communication.

2. **Baseband Layer:**
   - Manages the physical channels and link types.

3. **Link Manager Protocol (LMP):**
   - Handles link setup, authentication, encryption, and link management.

4. **Logical Link Control and Adaptation Protocol (L2CAP):**
   - Manages protocol multiplexing and segmentation/reassembly.

5. **RFCOMM (Radio Frequency Communication):**
   - Emulates RS-232 serial ports for legacy applications.

6. **Service Discovery Protocol (SDP):**
   - Discovers available services on Bluetooth devices.

7. **Telephony Control Protocol (TCS):**
   - Supports telephony control functions for Bluetooth applications.

## 5. Applications of Bluetooth and Piconet vs. Scatternet:

**Applications of Bluetooth:**
1. Wireless Headsets
2. File Transfer (OBEX)
3. Wireless Speakers
4. Wearable Devices
5. Bluetooth Low Energy (BLE) for IoT

**Piconet vs. Scatternet:**

- **Piconet:**
  - Consists of one master and up to seven active slave devices.
  - Master coordinates communication within the piconet.

- **Scatternet:**
  - Formed by connecting multiple piconets.
  - Devices can participate in multiple piconets simultaneously.

![Piconet and Scatternet](https://i.imgur.com/5se5eRE.png)

## 6. Functionality of the Service Discovery Protocol (SDP):

**Service Discovery Protocol (SDP):**

- **Functionality:**
  1. Allows Bluetooth devices to discover available services on other devices.
  2. Defines a service record, including information about the service.
  3. Provides a way for devices to negotiate the supported features and characteristics of services.

SDP enables devices to dynamically discover and connect to available services on other Bluetooth devices.
