```mermaid
sequenceDiagram
participant Attacker->>BotNet
participant BotNet->> WebServer
participant WebServer->> Firewall
participant Firewall--x webserver
```
The attacker is often the person in control of botnets which are usually hijakced devices thata re used to carry out attacks. 
The botnets are the primary way that these acts are carried out. The attacker will hack into computers or other  devices and then will install a malicous peice of code or malware called a bot. The affected devices from that network become botnets. 
The botnets send requests to the targetted IP address on the webserver which can potentially cause the network or server to become overwhelmed, which can result in a denial of service to normal traffic. 
A firewall can be configured to where it filters out network traffic by blocking out packets that meet a certain rule. These actions help block some illegitimate traffic used by the DDOS attacker. A firewall also limits the number of simulatious connections
from a single IP address and or a subnet. 
