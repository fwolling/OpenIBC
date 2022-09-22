# OpenIBC
## OpenIBC: Open-Source Wake-Up Receiver for<br/>Capacitive Intra-Body Communication

<img src="https://github.com/fwolling/OpenIBC/blob/main/fig/openibc_0v1.png" alt="OpenIBC prototype V0.1" width="600" style="float: center;" />

### Description
Intra-Body Communication (IBC) uses the human body as a part of the physical transmission channel for a more efficient and secure on-body communication. Since its introduction in 1995, it has evolved into an alternative to traditional wired and wireless techniques. In contrast to the ubiquitous radio-frequency identification (RFID) and near-field communication (NFC), IBC has, however, not reached the market yet. Therefore, possible applications remain underinvestigated.<br/>
In this GitHub repository, we present the *OpenIBC* project and a first open-source intra-body communication (IBC) receiver that is based on a repurposed off-the-shelf low-power RFID/NFC wake-up receiver front-end, the AS3930. In the evaluation, the prototype achieved a data rate of 4096 bit/s with a packet error rate of 320.0×10−6 at a low power of 7.4μW in listening mode and 8.4μW when receiving data. We encourage researchers to replicate and improve on our work, to develop open-source IBC transceivers and to explore their potential applications. The design files and software of the prototype are made available for download below.

### Download
#### Version V0.1 -- 2022-10-05
The design and source files will be published on Wednesday, October 5, 2022.

<!--<a href="#ref_s01"><b>[1]</b></a>  ...  [Pickle file](/src/gla716_sub23.p).-->

### Citation
"[OpenIBC: Open-Source Wake-Up Receiver for Capacitive Intra-Body Communication](https://www.eti.uni-siegen.de/ubicomp/papers/ewsn_openibc22.pdf)", <a href="https://ubicomp.eti.uni-siegen.de/home/team/fwolling.html.en" target="_blank">Florian Wolling</a>, Florian Hauck, <a href="https://www.eti.uni-siegen.de/emas/mitarbeiter/schroeder/index.html.en" target="_blank">Günter Schröder</a>, and <a href="https://ubicomp.eti.uni-siegen.de/home/team/kristof.html.en" target="_blank">Kristof Van Laerhoven</a>. In *Proceedings of the 2022 International Conference on Embedded Wireless Systems and Networks (EWSN 2022)*, Linz, Austria, ACM, October 2022. <!--<a href="https://doi.org" target="_blank">https://doi.org</a>-->

<!--### Disclaimer
You may use the source code of the developed synchronization tool *PulSync* for scientific, non-commercial purposes, provided that you give credit to the owners when publishing any work based on it. We would also be very interested to hear back from you if you use our tool or alignment method in any way and are happy to answer any questions or address any remarks related to it.-->

<!--### Teaser Video
The 1-minute teaser for the [PerHealth'21](https://sites.google.com/view/perhealth2021/) workshop can be found on [YouTube](https://www.youtube.com/watch?v=TENI1LUWinA).

<a href="https://www.youtube.com/watch?v=TENI1LUWinA" target="_blank"><img src="https://raw.githubusercontent.com/fwolling/PulSync/main/fig/youtube_teaser.png" alt="PerHealth'21 Teaser - PulSync: The Heart Rate Variability as a Unique Fingerprint for the Alignment of Sensor Data Across Multiple Wearable Devices" width="600" style="float: center;" /></a>

### Full Presentation Video
The full 15-minute presentation for the [PerHealth'21](https://sites.google.com/view/perhealth2021/) workshop can be found on [YouTube](https://www.youtube.com/watch?v=QiZApuLrRic), as well.

<a href="https://www.youtube.com/watch?v=QiZApuLrRic" target="_blank"><img src="https://raw.githubusercontent.com/fwolling/PulSync/main/fig/youtube_full.png" alt="PerHealth'21 Full Presentation - PulSync: The Heart Rate Variability as a Unique Fingerprint for the Alignment of Sensor Data Across Multiple Wearable Devices" width="600" style="float: center;" /></a>-->

### Design Files
<!--The *PulSync* processing pipeline has been evaluated using the dataset 716 of Howell and Porr from the University of Glasgow <a href="#ref_s01">**[1]**</a>. It contains ECG measurements from 25 subjects, recorded with two independent, pretended synchronous sensing devices in Einthoven II and resembled V2-V1 lead configurations. The "sitting" subset contains manually annotated peak labels with a precision of ±1 sample. Those were used to generate the heart rate variability (HRV) interval functions that are utilized to align the recordings.-->

### Software


### Results
<!--The evaluation of the data-driven alignment method *PulSync* resulted in a promising accuracy of -0.71 ± 3.44 samples, respectively -2.86 ± 11.43 ms at a sampling rate of 250 Hz and with the HRV interval functions resampled at 25 Hz. The initial misalignment of the original recordings was determined with a mean of 15.328 ± 428.023 samples, 0.061 ± 1.712 s respectively. The smallest initial misalignment was present in the recordings of subject 5 with 0.038 s, while subject 19 showed the largest offset of even 4.969 s.-->


<!--### References
<a id="ref_s01"><b>[1]:</b></a> "[High precision ECG Database with annotated R peaks, recorded and filmed under realistic conditions](http://researchdata.gla.ac.uk/716/)", Luis Howell and Bernd Porr. University of Glasgow, 2018. <a href="http://dx.doi.org/10.5525/gla.researchdata.716" target="_blank">http://dx.doi.org/10.5525/gla.researchdata.716</a>-->
