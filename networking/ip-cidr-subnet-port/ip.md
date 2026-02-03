

# ✅ README.md — IP Address (Internet Protocol Address)

---

## ✅ IP Address (Internet Protocol Address) – Full Concept

---

## 1. Definition of IP Address

An **IP Address** is a **unique number** given to every device connected to a network or the internet.

It helps in:

* Identifying the device
* Communicating with other devices
* Sending and receiving data

---

## 2. What is an IP Address?

An IP address is like the **home address** of your device.

Just like:

* Your home address helps people reach your house
* An IP address helps data reach your computer/mobile

---

## 3. Why IP Address is Needed?

IP address is needed because:

* Many devices are connected to the internet
* Every device must have a unique identity
* Data must know where to go

Without an IP address:

* Internet communication is not possible

---

## 4. Main Uses of IP Address

IP address is used for:

1. Device Identification
2. Location Addressing
3. Data Routing
4. Internet Communication
5. Network Management

---

## 5. Types of IP Address

There are mainly **two versions**:

1. **IPv4 (Internet Protocol Version 4)**
2. **IPv6 (Internet Protocol Version 6)**

---

# ✅ IPv4 Address

---

## 6. What is IPv4?

IPv4 is the most commonly used IP address format.

It is a **32-bit address**.

Example:

```
192.168.1.10
```

---

## 7. IPv4 Format

IPv4 is written in:

* Decimal format
* 4 parts separated by dots

Format:

```
A.B.C.D
```

Each part is called an **Octet**.

Example:

```
192 . 168 . 1 . 10
```

---

## 8. Size of IPv4 Address

IPv4 uses:

* 32 bits total
* 4 octets
* Each octet = 8 bits

So:

```
8 + 8 + 8 + 8 = 32 bits
```

---

## 9. Range of Each Octet

Each octet ranges from:

```
0 to 255
```

Because maximum 8-bit binary:

```
11111111 = 255
```

---

## 10. IPv4 Bits Representation

Example IPv4:

```
192.168.1.10
```

Binary conversion:

| Decimal | Binary (8-bit) |
| ------- | -------------- |
| 192     | 11000000       |
| 168     | 10101000       |
| 1       | 00000001       |
| 10      | 00001010       |

Full 32-bit binary:

```
11000000.10101000.00000001.00001010
```

---

## 11. Decimal to Binary Conversion Rule

Binary place values:

```
128 64 32 16 8 4 2 1
```

Example: Convert 192

```
192 = 128 + 64
```

Binary:

```
11000000
```

---

# ✅ Classes of IPv4 Address

---

## 12. IPv4 Address Classes

IPv4 addresses are divided into classes:

| Class | Range     | Use             |
| ----- | --------- | --------------- |
| A     | 1 – 126   | Large networks  |
| B     | 128 – 191 | Medium networks |
| C     | 192 – 223 | Small networks  |
| D     | 224 – 239 | Multicasting    |
| E     | 240 – 255 | Reserved        |

Examples:

* `10.x.x.x` → Class A
* `172.16.x.x` → Class B
* `192.168.x.x` → Class C

---

# ✅ Public and Private IP Address

---

## 13. Public IP Address

A public IP address is given by ISP and works on the internet.

Used for:

* Accessing websites
* Global communication

---

## 14. Private IP Address

Used inside local networks like home or office.

Private IP ranges:

* `10.0.0.0 – 10.255.255.255`
* `172.16.0.0 – 172.31.255.255`
* `192.168.0.0 – 192.168.255.255`

Example:

```
192.168.1.5
```

---

# ✅ Static vs Dynamic IP

---

## 15. Static IP Address

* Fixed IP address
* Does not change
* Used for servers

---

## 16. Dynamic IP Address

* Changes automatically
* Assigned by DHCP
* Used for normal users

---

# ✅ IPv6 Address

---

## 17. Why IPv6 was Introduced?

IPv4 provides only:

```
2^32 = 4.3 billion addresses
```

Internet devices increased, so addresses became insufficient.

Thus IPv6 was introduced.

---

## 18. IPv6 Format

IPv6 is a **128-bit address**.

Example:

```
2001:0db8:85a3:0000:0000:8a2e:0370:7334
```

Written in:

* Hexadecimal
* Separated by colons (:)

---

## 19. IPv4 vs IPv6 Difference

| Feature   | IPv4           | IPv6         |
| --------- | -------------- | ------------ |
| Bits      | 32-bit         | 128-bit      |
| Format    | Decimal + dots | Hex + colons |
| Addresses | Limited        | Unlimited    |
| Example   | 192.168.1.1    | 2001:db8::1  |

---

# ✅ Important Networking Terms

---

## 20. Network ID and Host ID

IP address has two parts:

1. Network part
2. Host part

Example:

```
192.168.1.10
```

* Network: 192.168.1
* Host: 10

---

## 21. Subnet Mask

Subnet mask tells:

* Which part is network
* Which part is host

Example:

```
255.255.255.0
```

---

# ✅ Summary (Very Important)

| Topic             | Key Point                    |
| ----------------- | ---------------------------- |
| IP Address        | Unique address of device     |
| IPv4              | 32-bit, 4 octets             |
| IPv6              | 128-bit, large address space |
| Public IP         | Works on internet            |
| Private IP        | Used in local networks       |
| Static IP         | Fixed                        |
| Dynamic IP        | Changes automatically        |
| Binary Conversion | Each octet = 8 bits          |

---

# ✅ Exam Ready Answer (5 Lines)

An IP address is a unique numerical identifier assigned to devices on a network.
It helps in locating and communicating between computers on the internet.
IPv4 uses 32-bit addresses written in dotted decimal form like 192.168.1.1.
Each part is 8 bits.
IPv6 was introduced to overcome IPv4 address shortage and uses 128-bit addresses.

---

