# Networking-Scenario-Solutions-on-AWS

### <h1 align="center"></h1>
### <ol>Scenario#1: <a href="https://docs.aws.amazon.com/vpn/latest/s2svpn/Examples.html">**Can you setup a Site to Site VPN connection from AWS to On-Prem Data Center without using Internet Gateway?**</a></ol>
```python
    Answer: YES
    Reference : https://aws.amazon.com/vpc/faqs/
    Explanation : An AWS Site-to-Site VPN connection connects your VPC to your datacenter. Amazon supports Internet Protocol Security (IPSec) VPN connections. Data transferred between your VPC and datacenter routes over an encrypted VPN connection to help maintain the confidentiality and integrity of data in transit. An internet gateway is not required to establish an AWS Site-to-Site VPN connection. 
    Architecture: Site-to-Site VPN connection , Site-to-Site VPN connection with a transit gateway
```
![Single S2S VPN Connection](https://docs.aws.amazon.com/images/vpn/latest/s2svpn/images/vpn-basic-diagram.png)

### <ol>Problem 2: <a href="https://github.com/Iamtripathisatyam/100_Days_Code_Challenge/blob/main/DAYS/Day1/Factorial_Of_Number.py">**Program to find Factorial of number.**</a></ol>
```python
    Input: Enter a Number: 5
    Output: 5! = 120
```
