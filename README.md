# A DIY kit and protocol for detecting RNA viruses at home using PCR

The aim of this project is developing an affordable solution for COVID-19 diagnosis (and possibly other viruses) that is easy to use, accessible, fast, without needing any prior expertise and knowledge for the user.

## Mechanism

PCR is a fast and reliable technique for detection of RNA or DNA strands of interest in a matter of hours. For COVID-19, genes such as gene E have been considered as a biomarker that can be detected using RT-PCR. However, performing RT PCR for normal people without lab equipments and prior knowledge and lab skills is not feasible. However, in a pandemic at this scale we need testing at much higher volume which can not be organized in a central manner.

RT PCR consists of two main steps:

* Sample preparation: a bio sample is taken and several mixing and bio reactions are conducted including RNA extraction, making cDNA from the RNA, and finally adding master mix for the polymerase chain reaction and making the solution for thermocycler.
* Amplification of the cDNA in a thermocycler.

The first step needs several chemical and biological agents to be mixed in micro litre scale using micro samplers and lots of tedious pipetting. Here we want to remove these steps by designing a device that can automatically perform all the needed mixing steps. The device may look like a microfluidic device which can mix the solutions using a micropump (link 1) or capillary (utilizing paper like what is shown in link 2)

* [1] [Piezoelectric Micro Pump -Takasago Fluidic Systems-](https://youtu.be/u-h8dhvmB1E)
* [2]: [Paper Microfluidics](https://youtu.be/J5LwNGm0tbw)

For the second step we will design a small portable thermocycler with at least two wells similar to [PocketPCR](http://www.gaudi.ch/GaudiLabs/?page_id=873).

## Expertise

Expertise we need:

* Biologist or Biotechnologist
* Electrical engineer
* Chemical engineer
* Embedded software programmer

## Community (non-commercial) efforts for Covid19 detection

* [Low-cost & Open-Source Covid19 Detection kits](https://app.jogl.io/project/118) Developing and sharing open source methodologies to safely test for the presence of SARS-CoV-2 using multiple approaches.
* [NinjaPCR's fight with COVID 19](https://github.com/hisashin/NinjaPCR/wiki/NinjaPCR's-fight-with-COVID-19)


## Related Projects

* [Mini-PCR](https://www.minipcr.com/)
* [PocketPCR](http://www.gaudi.ch/GaudiLabs/?page_id=873)
* [NinjaPCR](https://ninjapcr.tori.st/)
* [OpenDrop](http://www.gaudi.ch/GaudiLabs/?attachment_id=421)
