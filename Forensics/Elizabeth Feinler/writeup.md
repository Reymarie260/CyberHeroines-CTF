#  CyberHeroines CTF - Elizabeth Feinler

## Problem Statement

We found this PCAP but we did not know what to name it. Return the flag to this [Internet Hall of Famer](https://www.youtube.com/watch?v=idb-7Z3qk_o)

## Information

**Point Value**: 200 points

**Category**: Forensics

**Difficulty**: Easy/Medium

## Solution

Download the file `NoName.pcap` and open it in Wireshark. In there you select `Analyze > Follow > UDP Stream` and it will present you the domain names. Retrieve the numbers before the domain names and decode them from Octal.

## Flag
chctf{cr3at0r_0f_d0main_n4m3_syst3m}
