Role Name
=========

Configure my private Macbook Pro (Asgaard)

Network
=======

Home Network ( 10.100.0.0/24 )
------------------------------

| IP  | Hostname         | MAC Address       |
| --- | ---------------- | ----------------- |
| 1   | router           |                   |
| 10  | gniotek          | 9C-B6-54-07-DD-A2 |
| 11  | raspbmc          | B8-27-EB-62-F4-78 |
| 12  | hp-lan           | 8C-DC-D4-5B-24-E3 |
| 13  | ps4-lan          | 70-9E-29-EE-E4-D5 |
| 14  | pstv-lan         | 00-D9-D1-4F-E5-0E |
| 15  | ps3-lan          |                   |
| 20  | asgaard          | 20-C9-D0-7C-F4-5F |
| 21  | toficzek         | 9C-F3-87-B3-9A-90 |
| 30  | windows10        | 52-54-00-5E-9E-70 |
| 40  | iP6-Greyer       | A8-5B-78-A5-15-AD |
| 41  | iPadMini-Greyer  | 24-A2-E1-45-5F-D0 |
| 42  | iP5s-Paulina     | 48-74-6E-51-9D-81 |
| 43  | iPadMini-Paulina | C8-B5-B7-96-BC-FA |
| 44  | iP3G-Michal      | 00-21-E9-A1-0B-9C |
| 45  | iPad-Michal      |                   |
| 50  | hp-wifi          | 38-B1-DB-A6-55-76 |
| 51  | ps4-wifi         | E8-61-7E-96-0F-8D |
| 52  | pstv-wifi        | EC-0E-C4-C8-B1-58 |
| 53  | ps3-wifi         |                   |

Port forwarding table
---------------------

| PubPort | IntPort | IntIP       | Proto | Comment        |
| ------- | ------- | ----------- | ----- | -------------- |
| 22      | 22      | 10.100.0.10 | TCP   | SSH Gniotek    |
| 80      | 80      | 10.100.0.10 | TCP   | HTTP Gniotek   |
| 443     | 443     | 10.100.0.10 | TCP   | HTTPS Gniotek  |
| 1194    | 1194    | 10.100.0.10 | TCP   | VPN Gniotek    |
| 3389    | 3389    | 10.100.0.30 | TCP   | RDP Win8       |
| 88      | 8000    | 10.100.0.20 | TCP   | Django Panel   |
| 89      | 8080    | 10.100.0.20 | TCP   | Apache Asgaard |
| 6000    | 5900    | 10.100.0.10 | TCP   | VNC Win8       |
| 6010    | 5910    | 10.100.0.10 | TCP   | VNC Gniotek    |

Router switch
-------------

| Port | Host    |
| ---- | ------- |
| 1    | gniotek |
| 2    | raspbmc |
| 3    | ps4     |
| 4    | pstv    |

Power cords
===========

| Port        | Description |
| ----------- | ----------- |
| **Desk**    |             |
| 1           | Lamp        |
| 5           | Macbook     |
| **Servers** |             |
| 1           | router      |
| 2           | gniotek     |
| 3           | HP-Print    |
| 4           | Samsung LCD |
| 5           | PSTV        |
| **TV**      |             |
| 1           | Behind      |
| 2           | TV          |
| 3           | raspbmc     |
| 4           | fan         |
| **Behind**  | ?           |
| 1           | STB?        |
| 2           | PS4?        |
| 3           | HDMI?       |
| 4           |             |
