# Day03-NetworkInterfaces
Cybersecurity Day 03 assignment covering network interfaces, Ethernet, cables, and fiber-optic networking.

# Day 03 Assignment – Network Interfaces and Cables

---

# THEORY

## 1. What is a Network Interface Card?

A Network Interface Card (NIC) is a hardware component that allows a computer or other device to connect to a network. It can provide wired or wireless network connectivity.

## 2. What is Ethernet?

Ethernet is a technology used for communication between devices over a wired Local Area Network (LAN). It uses Ethernet cables and network interfaces to transfer data.

## 3. What is RJ-45?

RJ-45 is the connector commonly used with Ethernet network cables. It connects an Ethernet cable to network ports on devices such as computers, switches, and routers.

## 4. What does UTP stand for?

UTP stands for **Unshielded Twisted Pair**. It is a type of copper network cable containing pairs of twisted wires that help reduce interference.

## 5. Name three common Ethernet cable categories.

Three commonly used Ethernet cable categories are:

- Cat5e
- Cat6
- Cat6a

## 6. What is a straight-through cable?

A straight-through cable has the same wiring arrangement at both ends. It is commonly used to connect different types of network devices, such as a computer to a switch.

## 7. What is a crossover cable?

A crossover cable has different wiring arrangements at each end, allowing transmit and receive pairs to be crossed. It was traditionally used to directly connect similar devices, such as two computers.

## 8. Explain Auto MDI-X.

Auto MDI-X is a feature that automatically detects the transmit and receive requirements of an Ethernet connection. This allows devices to work with different cable types without manually selecting a straight-through or crossover cable.

## 9. Difference between copper and fiber-optic networking?

Copper networking uses electrical signals travelling through copper wires, while fiber-optic networking uses light signals travelling through optical fiber.

Copper is commonly used for shorter network connections, while fiber is suitable for higher bandwidth and longer-distance communication.

## 10. What is multimode fiber?

Multimode fiber allows multiple light paths to travel through the fiber. It is commonly used for shorter-distance network connections, such as connections within buildings and data centers.

## 11. What is single-mode fiber?

Single-mode fiber is designed to carry light mainly through a single path. It is commonly used for longer-distance communication because it has lower signal dispersion.

## 12. Two advantages of fiber-optic networking

Two advantages of fiber-optic networking are:

- It provides high bandwidth and supports high-speed data transmission.
- It is resistant to electromagnetic interference because it uses light instead of electrical signals.

## 13. Why is understanding network interfaces important for cybersecurity?

Understanding network interfaces helps cybersecurity professionals understand how systems connect to networks and how traffic enters and leaves a device. This knowledge is useful for network monitoring, troubleshooting, investigating suspicious connections, and identifying unauthorized network activity.

---

# PRACTICAL IDENTIFICATION

## 14. Identify your active network adapter

I checked my network configuration using the Windows `ipconfig /all` command.

**Active Network Adapter:** Wi-Fi

## 15. Network Information

**Network Adapter:** Wi-Fi

**IPv4 Address:** `10.10.143.178`

**Default Gateway:** `10.10.143.1`

> **Privacy note:** Sensitive information such as MAC addresses and IPv6 addresses has been hidden in the public GitHub screenshot.

---

# SCREENSHOT

## `ipconfig /all`

I used the following command to view detailed information about my network adapters:

```cmd
ipconfig /all
