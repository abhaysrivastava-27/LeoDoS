# LeoDoS - The AQM&DoS Simulation Platform

The Active Queue Management and Denial-of-Service (AQM&DoS) Simulation Platform is based on the Network Simulation 2. It is able to simulate a variety of experimental scenarios related to Distributed Denial-of-Service (DDoS) attacks and Active Queue Management (AQM) algorithms.

[**Download**](leodos.zip?raw=true) | [**Introduction**](leodos/doc/leodos.pdf?raw=true) | [**Discussion**](http://groups.google.com/group/aqmdos-simulation-platform) | [**FAQs**](https://sites.google.com/site/cwzhangres/home/posts/frequentlyaskedquestionsfaqsabouttheaqmdossimulationplatform)

## Simulate numbers of Denial-of-Service attacks:

* Denial-of-Service (DoS) attacks
* Distributed Deinal-of-Service (DDoS) attacks
* Spoofing DoS or DDoS attacks
* Distributed Low-rate Denial-of-Service (DLDoS) attacks
* Spoofing LDoS or DLDoS attacks

## Simulate many Active Queue Management (AQM) algorithms:

* 1 DropTail; 2 RED; 3 RED/PD; 4 Blue; 5 SFB;
* 6 CBQ; 7 FQ; 8 SFQ; 9 DRR; 10 PI;
* 11 Vq; 12 REM; 13 GK; 14 SRR;
* 15 RED/Robust (RRED) 16 SFB/Robust (RSFB);

## Simulate a number of network topologies:

* Dumb Bell
* Tree
* Line
* Internet
* And you can define new topologies with ease.

To analyse the impact of DoS attacks on normal TCP flows , AQM algorithms, this platform also provides mechanisms to automatically calculate and record the average throughput of normal TCP flows before and after DoS attacks.

