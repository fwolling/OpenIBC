# OpenIBC
## OpenIBC: Open-Source Wake-Up Receiver for<br/>Capacitive Intra-Body Communication

<img src="https://github.com/fwolling/OpenIBC/blob/main/fig/openibc_0v1.png" alt="OpenIBC prototype V0.1" width="600" style="float: center;" />

### Description
Intra-Body Communication (IBC) uses the human body as a part of the physical transmission channel for a more efficient and secure on-body communication. Since its introduction in 1995, it has evolved into an alternative to traditional wired and wireless techniques. In contrast to the ubiquitous radio-frequency identification (RFID) and near-field communication (NFC), IBC has, however, not reached the market yet. Therefore, possible applications remain underinvestigated.<br/>
In this GitHub repository, we present the *OpenIBC* project and a first open-source intra-body communication (IBC) receiver that is based on a repurposed off-the-shelf low-power RFID/NFC wake-up receiver front-end, the AS3930. In the evaluation, the prototype achieved a data rate of 4096 bit/s with a packet error rate of 320.0E−6 at a low power of 7.4μW in listening mode and 8.4μW when receiving data. We encourage researchers to replicate and improve on our work, to develop open-source IBC transceivers and to explore their potential applications. The design files and source code of the prototype V0.1 are made available for download below.

### Disclaimer
You may use the design files and source code of the developed *OpenIBC* prototypes for scientific, non-commercial purposes, provided that you give credit to the owners when publishing any work based on it. We would also be very interested to hear back from you if you use our prototype or files in any way and are happy to answer any questions or address any remarks related to it.


### History
#### <a href="#prototype-v01">Prototype V0.1 -- 2022-10-05</a>
The *OpenIBC* project will be presented at the <a href="https://ewsn2022.jku.at/" target="_blank">EWSN</a> conference in Linz, Austria on Wednesday, October 5, 2022. The design files and source code will be published at the moment of the presentation.


### <a id="prototype-v01">Prototype V0.1</a>
The first open-source IBC receiver, based on the repurposed off-the-shelf low-power RFID/NFC wake-up receiver front-end AS3930. In the evaluation, the prototype achieved a data rate of 4096 bit/s with a packet error rate of 320.0E−6 at a low power of 7.4μW in listening mode and 8.4μW when receiving data.

#### Citation
"[OpenIBC: Open-Source Wake-Up Receiver for Capacitive Intra-Body Communication](https://www.eti.uni-siegen.de/ubicomp/papers/ewsn_openibc22.pdf)", <a href="https://ubicomp.eti.uni-siegen.de/home/team/fwolling.html.en" target="_blank">Florian Wolling</a>, Florian Hauck, <a href="https://www.eti.uni-siegen.de/emas/mitarbeiter/schroeder/index.html.en" target="_blank">Günter Schröder</a>, and <a href="https://ubicomp.eti.uni-siegen.de/home/team/kristof.html.en" target="_blank">Kristof Van Laerhoven</a>. In *Proceedings of the 2022 International Conference on Embedded Wireless Systems and Networks (EWSN 2022)*, Linz, Austria, ACM, October 2022. <!--<a href="https://doi.org" target="_blank">https://doi.org</a>-->

#### Design Files

#### Source Code
