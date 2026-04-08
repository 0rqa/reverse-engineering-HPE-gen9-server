# HPE-gen9-server-reverse-engineering

>[!NOTE]
> This repo is still under construction, or as some know WIP

<br>

# Fan pinout

 - series WTB BMI Fan Connectors
   - Amphenol G875C02141DEU - crimp terminal - tin version  
   - Amphenol G875C02142DEU - crimp terminal - gold plated version
   - Amphenol G875H10620DEU - 6 pin male crimp connector
   - Amphenol G86106413D2EU - 6 pin female THT recepticle
  
<br>

- To enable the fan detection, connect the detect pin directly to GND. The PWM signal is revesed eg. fans runs at 100% when pwm is at 0% compared to normal PC fan. So a some type of convertor will be necessary for fan swap.

   <br>
   
[![Image](https://github.com/0rqa/reverse-engineerin-HPE-gen9-server/blob/main/pdf/preview/HPE%20dl360%20gen9-fan%20connector.png)](https://github.com/0rqa/reverse-engineerin-HPE-gen9-server/blob/main/pdf/HPE%20dl360%20gen9-fan%20connector.pdf)

<br>

# 10pin backplane power connector

- series Micro-Fit 3.0
  - Molex 43030000 - crimp terminal
  - Molex 430251000 - 10 pin male crimp connector
  - Molex 430451013 - 10 pin female THT receptacle 

<br>

[![Image](https://github.com/0rqa/reverse-engineerin-HPE-gen9-server/blob/main/pdf/preview/HPE%20dl360%20gen9-10%20pin%20front%20disk%20backplane%20connector.png)](https://github.com/0rqa/reverse-engineerin-HPE-gen9-server/blob/main/pdf/HPE%20dl360%20gen9-10%20pin%20front%20disk%20backplane%20connector.pdf)

<br>

# 6+4pin 8SSF backplane power connector

- series Micro-Fit 3.0
  - Molex 43030000 - crimp terminal
  - Molex 0430250400 - 4 pin male crimp connector
  - Molex 0430450413 - 4 pin female THT receptacle
  - Molex 430250600 - 6 pin male crimp connector
  - Molex 430450612 - 6 pin female THT receptacle

<br>

[![Image](https://github.com/0rqa/reverse-engineerin-HPE-gen9-server/blob/main/pdf/preview/HPE%20dl360%20gen9-4%20%2B%206%20pin%208SFF%20backplane%20connectors.png)](https://github.com/0rqa/reverse-engineerin-HPE-gen9-server/blob/main/pdf/HPE%20dl360%20gen9-4%20%2B%206%20pin%208SFF%20backplane%20connectors.pdf)

<br>
  
# Front IO panel

 - Proprietary HPE connector?
 
<br>

[![Image](https://github.com/0rqa/reverse-engineerin-HPE-gen9-server/blob/main/pdf/preview/HPE%20dl360%20gen9-front%20panel%20IO%20connector-1.png)](https://github.com/0rqa/reverse-engineerin-HPE-gen9-server/blob/main/pdf/HPE%20dl360%20gen9-front%20panel%20IO%20connector.pdf)

[![Image](https://github.com/0rqa/reverse-engineerin-HPE-gen9-server/blob/main/pdf/preview/HPE%20dl360%20gen9-front%20panel%20IO%20connector-2.png)](https://github.com/0rqa/reverse-engineerin-HPE-gen9-server/blob/main/pdf/HPE%20dl360%20gen9-front%20panel%20IO%20connector.pdf)

<br>

# DL360 main raiser card

Surounding component with silkscreen of U2 = VHC125 TOS - IO buffer, U3 = 74LV165AD - 8bit serial register, and one unknow U4 = E3 8A


# TODO:

- [x] Map the pinout of front backplane connector
- [x] Map the pinout of port on 8SSF backplane
- [x] Map the pinout of front IO connector
- [x] Map the pinout of fan connector 
- [ ] Map the pinout of "Smart array connector"
- [ ] Map the pinout of main PCIE raiser card port
- [ ] Map the pinout of seccondart PCIE raiser card port
