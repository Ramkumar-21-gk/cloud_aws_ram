# ✅ README.md — CIDR (Classless Inter-Domain Routing)

---

## ✅ CIDR (Classless Inter-Domain Routing)

---

## 1. Definition of CIDR

CIDR stands for:

> **Classless Inter-Domain Routing**

CIDR is a method used to write IP addresses with subnet information in a shorter form.

---

## 2. What is CIDR?

CIDR is a new way of representing:

* IP Address
* Subnet Mask
* Network Size

in one format.

---

## 3. CIDR Format

CIDR format is written like this:

```
IP Address / Number
```

Example:

```
192.168.1.0/24
```

Here:

* `192.168.1.0` = Network address
* `/24` = Network bits

---

## 4. Meaning of /24 in CIDR

The number after `/` tells:

> How many bits belong to the network part.

Example:

```
/24 means first 24 bits = Network ID
Remaining 8 bits = Host ID
```

Because IPv4 total bits = 32

So:

```
32 - 24 = 8 host bits
```

---

## 5. CIDR vs Subnet Mask

CIDR is just a short form of subnet mask.

Example:

```
/24 = 255.255.255.0
```

---

## 6. CIDR Table (Very Important)

| CIDR | Subnet Mask     | Host Bits | Total Hosts |
| ---- | --------------- | --------- | ----------- |
| /8   | 255.0.0.0       | 24        | 2^24 - 2    |
| /16  | 255.255.0.0     | 16        | 2^16 - 2    |
| /24  | 255.255.255.0   | 8         | 2^8 - 2     |
| /26  | 255.255.255.192 | 6         | 2^6 - 2     |
| /28  | 255.255.255.240 | 4         | 2^4 - 2     |
| /30  | 255.255.255.252 | 2         | 2^2 - 2     |

---

## 7. Why CIDR is Used?

CIDR is used because:

1. IPv4 addresses are limited
2. Class-based system wastes IP addresses
3. CIDR allows flexible subnetting
4. Improves routing efficiency
5. Better address allocation

---

## 8. Why Classful Addressing Was Bad?

Old system had fixed classes:

* Class A
* Class B
* Class C

Example:

If a company needs 500 IPs:

* Class C gives only 254 → Not enough
* Class B gives 65,534 → Too many waste

So CIDR solves this problem.

---

## 9. CIDR is Classless

CIDR does not depend on classes.

It can create networks of any size like:

* /20
* /22
* /27
* /29

So IP usage becomes efficient.

---

# ✅ CIDR Example in Detail

---

## Example:

```
192.168.10.0/26
```

### Step 1: Network bits

```
/26 means 26 bits are network
```

### Step 2: Host bits

```
32 - 26 = 6 host bits
```

### Step 3: Hosts calculation

```
2^6 - 2 = 64 - 2 = 62 hosts
```

So this subnet can have:

✅ 62 devices

---

# ✅ How CIDR Helps in Subnetting

CIDR helps to create smaller subnets easily:

* /24 → 254 hosts
* /26 → 62 hosts
* /28 → 14 hosts
* /30 → 2 hosts

---

# ✅ CIDR Summary

| Point          | Meaning                        |
| -------------- | ------------------------------ |
| CIDR Full Form | Classless Inter-Domain Routing |
| Format         | IP/Number                      |
| /24 Meaning    | 24 network bits                |
| Purpose        | Efficient IP allocation        |
| Benefit        | Flexible subnetting            |

---

# ✅ Exam Answer (5 Marks)

CIDR stands for Classless Inter-Domain Routing.
It is a method of representing IP addresses along with subnet information using a slash notation like 192.168.1.0/24.
The number after the slash indicates the number of network bits.
CIDR was introduced to replace the classful addressing system and to reduce wastage of IP addresses.
It allows flexible subnetting and improves routing efficiency.

---
