<span style="font-size:2em; font-weight: bold;">API RTU Setup</span>

Last modified: May 2, 2024

# Model: USR-N520

### Application Case

> Port1: Virtual serial port

> Port2: Modbus TCP/RTU gateway.
>> - Ethernet: Modbus TCP server (slave)
>> - Serial: Modbus RTU master

## Table of Contents

- [Status](#Status)
- [Network](#Network)
- [Port](#Port)
- [Gateway](#Gateway)
- [Cloud Service](#Cloud-Service)
- [System](#System)

---

## Status
- Model Name: USR-N520
- Firmware Version: V2.0.8
- Type: H7

## Network

>### IP Config
>- Method of IP Obtaining: Static IP
>- DNS: Auto
>- IP Address: 192.168.0.7
>- Subnet mask: 255.255.255.0
>- Gateway: 192.168.0.1
>- Preferred DNS Server: 168.126.63.1
>- Alternative DNS Server: 223.5.5.5

## Port
> ### Port1
>> #### Port
>>> - Baud rate: 9600
>>> - Data bits: 8
>>> - Parity: None
>>> - Stop bits: 1
>>> - Serial Mode: DIP Switch
>>> - Current Serial Mode: RS485
>>> - Flow ctrl: NONE
>>> - UART Packet Length: 0
>>> - UART Packet Time: 0
>>> - Sync Baudrate(RFC2217): ON
>>> - Enable UART Heartbeat: [ ]
>
>> #### Socket
>>> Socket A
>>>> - Working Mode: TCP Server / None
>>>> - Maximum Sockets supported: 16 / Exceeding Maximum: KICK
>>>> - Local Port Number: **23**
>>>> - PRINT: OFF
>>>> - Modbus Poll [ ] / Response Timeout: 2000
>>>> - Enable Net Heartbeat [ ]
>
>>> Socket B
>>>> - Operating Mode: None
> ### Port2
>> #### Port
>>> - Baud rate: 9600
>>> - Data bits: 8
>>> - Parity: None
>>> - Stop bits: 1
>>> - Serial Mode: DIP Switch
>>> - Current Serial Mode: RS485
>>> - Flow ctrl: NONE
>>> - UART Packet Length: 0
>>> - UART Packet Time: 0
>>> - Sync Baudrate(RFC2217): ON
>>> - Enable UART Heartbeat: [ ]
>
>> #### Socket
>>> Socket A
>>>> - Working Mode: TCP Server / ModbusTCP
>>>> - Maximum Sockets supported: 16 / Exceeding Maximum: KICK
>>>> - Local Port Number: **502**
>>>> - PRINT: OFF
>>>> - Modbus Poll [ ] / Response Timeout: 2000
>>>> - Modbus TCP Exception [v]
>>>> - Enable Net Heartbeat [ ]
>
>>> Socket B
>>>> - Operating Mode: None
>
> ### Websocket to Serial
>> *Diagnostic Page*

## Gateway
> ### MQTT Gateway
>> #### Basic configuration
>>> - Enable MQTT: Disable
> ### Edge Computing
>> #### Edge Computing
>>> - Enable Edge Computing: Disable

## Cloud Service
> ### USR Cloud
>> #### USR Cloud setting
>>> - USR Cloud: OFF
> ### Alibaba Cloud
>> #### Basic configuration
>>> - Enable Service: Disable
> ### AWS IoT
>> #### Basic configuration
>>> - Enable Service: Disable 

## System
> ### System Setting
>> - Model Name: USR-N510
>> - Websocket Port: 6432
>> - Websocket Direction: UART1
>> - Webserver Port: 80
>> - User Name: admin
>> - UART Cache: OFF
>> - Restarting Without Data: 0
>> - SNMP: OFF
>> - Telnet: OFF
>> - NTP: ON
>> - NTP Server Address: cn.ntp.org.cn
>> - NTP Timezone Setting: UTC+9
>> - 485 Anit-Collision: ON
>> - 485-Idle Time: 10

> ### Management
>>> Firmware upgrade
>
>>> Reset
>
>>> Restart
>


---
