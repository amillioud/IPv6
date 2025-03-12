# IPv6 Overview
Hexadecimal, Basics, Configuration, Global Unicast, Unique Local, Link Local, Multicast, IPv6 header, NDP, SLAAC, Static Routing

## Hexadecimal
**Decimal** is a base-10 numbering system. This means it uses ten distinct symbols (0 through 9) to represent values. Represented as **0d**.

**Binary** is a base-2 numbering system which uses only two symbols, typically 0 and 1. Each digit in a binary number represents a power of 2, with the rightmost digit representing 2^0, the next representing 2^1, and so on. Represented as **0b**.

**Hexadecimal** is a base-16 numbering system that uses sixteen distinct symbols: 0-9 to represent values zero to nine, and A-F to represent values ten to fifteen. Represented as **0x**.

## Binary to Hexadecimal
In the case of translating a binary octet to hexadecmial, the process goes as follows:

1. 0b11011011 (the **0b** just shows that the data is represented in binary)
2. The octet is split into two: 1101 and 1011.
3. 1101 = D(13) and 1011 = B(11)
4. 13 * 16 + 11 = 219 = **0xDB**

## Why IPv6?
The main reason for the development of IPv6 is the IPv4 address exhaustion problem. There are **4,294,967,262 (2^32)** IPv4 addresses available. 
Given the high demand of addresses in our hyperconnected world, most of these addresses are no longer available and soon there will be no more left. 

The solution for the address exhaustion is IPv 6. An IPv6 address is **128 bits** long. There are **340,282,366,920,938,463,463,374,607,431,768,211,456 (2^128)** possible IPv6 addresses. 

## Shortening
