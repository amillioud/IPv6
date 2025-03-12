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
4. 13 * 16 + 11 = 219 = 0xDB
