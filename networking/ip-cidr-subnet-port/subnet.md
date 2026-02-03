
# ✅ README.md — Subnet (Full Concept)

---

## ✅ SUBNET (Full Concept)

---

## 1. What is a Subnet?

A **Subnet** means:

> A smaller network created inside a big network.

Subnet = **Sub Network**

It divides one large network into many smaller networks.

---

## 2. Definition of Subnet

A subnet is a part of an IP network created by dividing the network into smaller groups.

---

## 3. Why Subnet is Needed? (Importance)

Subnetting is needed because:

1. To reduce network traffic
2. To manage networks easily
3. To improve security
4. To use IP addresses efficiently
5. To divide a network into departments

Example:

A company has one network
But wants separate networks for:

* HR Department
* Accounts Department
* IT Department

So they create subnets.

---

## 4. What is Subnetting?

Subnetting is the process of dividing a large network into smaller subnets.

---

# ✅ SUBNET MASK

---

## 5. What is Subnet Mask?

Subnet Mask tells:

* Which part of IP is **Network**
* Which part of IP is **Host**

Subnet Mask is used to separate:

✅ Network ID
✅ Host ID

---

## 6. Subnet Mask Format

Example:

```
255.255.255.0
```

It looks like an IP address.

---

## 7. Subnet Mask in Bits

Subnet mask is also 32 bits.

Example:

```
255.255.255.0
```

Binary form:

```
11111111.11111111.11111111.00000000
```

Meaning:

* 24 bits = Network part
* 8 bits = Host part

---

# ✅ NETWORK ID and HOST ID

---

## 8. Network ID

Network ID identifies the network.

Example IP:

```
192.168.1.10
```

Subnet Mask:

```
255.255.255.0
```

Network part becomes:

```
192.168.1.0
```

---

## 9. Host ID

Host ID identifies the device in the network.

Example:

```
.10 is host part
```

So device number is 10.

---

# ✅ CIDR Notation

---

## 10. What is CIDR?

CIDR is a short way of writing subnet mask.

Example:

```
192.168.1.0/24
```

Here:

* `/24` means first 24 bits are network bits

Subnet Mask:

```
255.255.255.0
```

---

## 11. Common CIDR Values

| CIDR | Subnet Mask      |
| ---- | ---------------- |
| /8   | 255.0.0.0        |
| /16  | 255.255.0.0      |
| /24  | 255.255.255.0    |
| /32  | Single host only |

---

# ✅ How Many Hosts in a Subnet?

---

## 12. Formula to Calculate Hosts

Hosts =

```
2^n - 2
```

Where **n** = number of host bits

---

### Example: /24

Subnet Mask:

```
255.255.255.0
```

Host bits = 8

So:

```
2^8 - 2 = 256 - 2 = 254 hosts
```

So `/24` network gives **254 usable devices**.

---

# ✅ Subnet Example (Very Easy)

---

## 13. Example IP

IP Address:

```
192.168.1.10
```

Subnet Mask:

```
255.255.255.0
```

Binary:

IP:

```
11000000.10101000.00000001.00001010
```

Mask:

```
11111111.11111111.11111111.00000000
```

Network part (AND operation):

```
192.168.1.0
```

So:

✅ Network ID = 192.168.1.0
✅ Host ID = 10

---

# ✅ Types of Subnetting

---

## 14. Fixed Length Subnet Mask (FLSM)

All subnets have the same size.

---

## 15. Variable Length Subnet Mask (VLSM)

Different subnets can have different sizes.

Used in modern networks.

---

# ✅ Advantages of Subnetting

---

## 16. Benefits

1. Reduces network congestion
2. Improves network performance
3. Provides better security
4. Efficient use of IP addresses
5. Easy network management

---

# ✅ Final Summary

| Term        | Meaning                          |
| ----------- | -------------------------------- |
| Subnet      | Small network inside big network |
| Subnet Mask | Separates network and host       |
| CIDR        | Shortcut of subnet mask          |
| Network ID  | Network identification           |
| Host ID     | Device identification            |
| Formula     | 2^n - 2 hosts                    |

---

# ✅ Exam Answer (5 Marks)

Subnetting is the process of dividing a large IP network into smaller networks called subnets.
It is used to reduce network traffic, improve performance, and manage IP addresses efficiently.
A subnet mask helps identify network and host portions of an IP address.
CIDR notation like `/24` shows the number of network bits.
Subnetting improves security and organization of networks.

---
